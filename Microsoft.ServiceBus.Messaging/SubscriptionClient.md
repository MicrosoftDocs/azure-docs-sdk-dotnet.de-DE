<Type Name="SubscriptionClient" FullName="Microsoft.ServiceBus.Messaging.SubscriptionClient">
  <TypeSignature Language="C#" Value="public abstract class SubscriptionClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SubscriptionClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SubscriptionClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d3e8d-101">Stellt die Anchor-Klasse, die in der Laufzeit-Vorgänge, die im Zusammenhang mit themaabonnements verwendet.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-101">Represents the anchor class used in run-time operations related to a topic subscription.</span></span></summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            <span data-ttu-id="d3e8d-102">Erstellen von Abonnements Client SubscriptionClient MySubscriptionClient = Factory. CreateSubscriptionClient(mySubscription);</span><span class="sxs-lookup"><span data-stu-id="d3e8d-102">// Create subscription client SubscriptionClient mySubscriptionClient = factory.CreateSubscriptionClient(mySubscription);</span></span>
            
            <span data-ttu-id="d3e8d-103">Empfangen von Nachrichten für (Int Count = 0; Anzahl &lt; MsgCount; Anzahl ++) {Var Message = mySubscriptionClient.Receive(); message.Complete(); }</span><span class="sxs-lookup"><span data-stu-id="d3e8d-103">// Receive messages for (int count = 0; count &lt; MsgCount; count++) { var message = mySubscriptionClient.Receive(); message.Complete(); }</span></span>
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="subscriptionClient.Abandon lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-104">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-104">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="d3e8d-105">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-105">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="d3e8d-106">Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-106">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="d3e8d-107">Service Bus erhöht die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-107">Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="d3e8d-108">Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-108">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-109">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-109">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-110">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-110">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Abandon (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-111">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-111">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-112">Eine Auflistung von Property-Objekte geändert werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-112">A collection of property objects to be modified.</span></span></param>
        <summary><span data-ttu-id="d3e8d-113">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-113">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="d3e8d-114">Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-114">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="d3e8d-115">Service Bus erhöht die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-115">Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="d3e8d-116">Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-116">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-117">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-117">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="d3e8d-118">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-118">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-119">Eine Taskinstanz, die den asynchronen Abbruchvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-119">A task instance that represents the asynchronous abandon operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-120">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-120">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-121">Eine Auflistung von Property-Objekte geändert werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-121">A collection of property objects to be modified.</span></span></param>
        <summary><span data-ttu-id="d3e8d-122">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-122">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-123">Eine Taskinstanz, die den asynchronen Abbruchvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-123">A task instance that represents the asynchronous abandon operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-124">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-124">Accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-125">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-125">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="d3e8d-126">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-126">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="d3e8d-127">Akzeptiert eine nachrichtensitzung, die für die Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-127">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-128">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-128">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="d3e8d-129">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-129">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-130">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-130">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-131">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-131">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-132">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-132">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-133">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-133">Accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-134">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-134">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d3e8d-135">Wird ausgelöst, wenn ServerWaitTime nicht um ein positive TimeSpan-Wert ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-135">Thrown if serverWaitTime is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-136">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-136">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-137">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-137">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="d3e8d-138">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-138">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-139">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-139">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-140">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit dem angegebenen Bezeichner, und warten Sie Sitzungstimeout ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-140">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-141">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-141">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="d3e8d-142">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-142">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d3e8d-143">Wird ausgelöst, wenn ServerWaitTime nicht um ein positive TimeSpan-Wert ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-143">Thrown if serverWaitTime is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-144">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-144">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-145">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-145">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-146">Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-146">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-147">Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-147">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="d3e8d-148">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-148">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="d3e8d-149">Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-149">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-150">Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-150">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-151">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-151">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-152">Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-152">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-153">Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-153">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="d3e8d-154">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-154">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-155">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-155">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-156">Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-156">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-157">Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-157">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRule (description As RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.AddRule : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; unit" Usage="subscriptionClient.AddRule description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="d3e8d-158">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-158">The rule description that provides metadata of the rule to add.</span></span></param>
        <summary><span data-ttu-id="d3e8d-159">Fügt eine neue Regel, die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> mithilfe der angegebenen Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-159">Adds a new rule to the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> using the specified rule description.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="d3e8d-160">Wird ausgelöst, wenn <paramref name="description" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-160">Thrown if <paramref name="description" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="d3e8d-161">Wird ausgelöst, wenn <paramref name="description.Name.Name" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-161">Thrown if <paramref name="description.Name.Name" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d3e8d-162">Wird ausgelöst, wenn <paramref name="description.Name.Name" /> Länge überschreitet das Limit von 50 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-162">Thrown if <paramref name="description.Name.Name" /> length has exceeded the limit of 50 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-163">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-163">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-164">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-164">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="d3e8d-165">Wird ausgelöst, wenn versucht wird, eine andere Regel mit demselben Namen wie eine hinzufügen, die bereits hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-165">Thrown when an attempt is made to add another rule with same name as one that has already been added.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRule : string * Microsoft.ServiceBus.Messaging.Filter -&gt; unit" Usage="subscriptionClient.AddRule (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="d3e8d-166">Der Name der Regel hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-166">The name of the rule to add.</span></span></param>
        <param name="filter"><span data-ttu-id="d3e8d-167">Der Filterausdruck für den Nachrichten berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-167">The filter expression against which messages will be matched.</span></span></param>
        <summary><span data-ttu-id="d3e8d-168">Fügt eine Regel auf das aktuelle Abonnement mit dem angegebenen Namen und die Filter-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-168">Adds a rule to the current subscription with the specified name and filter expression.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="d3e8d-169">Wird ausgelöst, wenn <paramref name="filter" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-169">Thrown if <paramref name="filter" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="d3e8d-170">Wird ausgelöst, wenn <paramref name="ruleName" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-170">Thrown if <paramref name="ruleName" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d3e8d-171">Wird ausgelöst, wenn <paramref name="ruleName" /> Länge überschreitet das Limit von 50 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-171">Thrown if <paramref name="ruleName" /> length has exceeded the limit of 50 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-172">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-172">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-173">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-173">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="d3e8d-174">Wird ausgelöst, wenn versucht wird, eine andere Regel mit demselben Namen wie eine hinzufügen, die bereits hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-174">Thrown when an attempt is made to add another rule with same name as one that has already been added.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="d3e8d-175">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-175">The rule description that provides metadata of the rule to add.</span></span></param>
        <summary><span data-ttu-id="d3e8d-176">Fügt asynchron eine neue Regel, die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> mithilfe der angegebenen Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-176">Asynchronously adds a new rule to the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> using the specified rule description.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-177">Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-177">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="d3e8d-178">Der Name der Regel hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-178">The name of the rule to add.</span></span></param>
        <param name="filter"><span data-ttu-id="d3e8d-179">Der Filterausdruck für den Nachrichten berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-179">The filter expression against which messages will be matched.</span></span></param>
        <summary><span data-ttu-id="d3e8d-180">Fügt asynchron eine Regel auf das aktuelle Abonnement mit dem angegebenen Namen und den Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-180">Asynchronously adds a rule to the current subscription with the specified name and filter expression.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-181">Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-181">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="subscriptionClient.Complete lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Complete(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-182">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-182">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-183">Schließt die Verarbeitung einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-183">Completes processing of a message.</span></span></summary>
        <remarks> <span data-ttu-id="d3e8d-184">Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-184">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="d3e8d-185">Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-185">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-186">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-186">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-187">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-187">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="d3e8d-188">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-188">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-189">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-189">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-190">Schließt asynchron verarbeiten einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-190">Asynchronously completes processing of a message.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-191">Eine Taskinstanz, die den asynchronen schließen-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-191">A task instance that represents the asynchronous complete operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="subscriptionClient.CompleteBatch lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="d3e8d-192">Die Lock-Token, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-192">The lock tokens bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-193">Schließt die Verarbeitung eines Nachrichtenbatches an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-193">Completes processing of a batch.</span></span></summary>
        <remarks> <span data-ttu-id="d3e8d-194">Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-194">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="d3e8d-195">Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-195">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteBatchAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="d3e8d-196">Die Lock-Token, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-196">The lock tokens bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-197">Asynchron schließt die Verarbeitung eines Batches.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-197">Asynchronously completes processing of a batch.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-198">Eine Taskinstanz, die den asynchronen Abschluss Batchvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-198">A task instance that represents the asynchronous complete batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="d3e8d-199">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-199">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-200">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-200">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="d3e8d-201">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mit dem angegebenen Namen und Thema Pfad.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-201">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> with specified name and topic path.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-202">Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-202">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="d3e8d-203">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-203">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-204">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-204">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-205">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-205">The message receive mode.</span></span></param>
        <summary><span data-ttu-id="d3e8d-206">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mit dem angegebenen Namen, themenpfad und Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-206">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> with specified name, topic path and mode.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-207">Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-207">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="d3e8d-208">Vollständig qualifizierten Domänennamen für Sercvice Bus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-208">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="d3e8d-209">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="d3e8d-209">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-210">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-210">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-211">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-211">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="d3e8d-212">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-212">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="d3e8d-213">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-213">The client assertion certificate credential.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-214">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-214">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="d3e8d-215"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="d3e8d-215"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="d3e8d-216">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-216">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="d3e8d-217">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-217">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-218">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-218">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="d3e8d-219">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-219">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="d3e8d-220">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="d3e8d-220">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-221">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-221">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-222">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-222">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="d3e8d-223">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-223">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="d3e8d-224">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-224">The app credential.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-225">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-225">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="d3e8d-226"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="d3e8d-226"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="d3e8d-227">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-227">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="d3e8d-228">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-228">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-229">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-229">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="d3e8d-230">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-230">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="d3e8d-231">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="d3e8d-231">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-232">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-232">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-233">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-233">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="d3e8d-234">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-234">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="d3e8d-235">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-235">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="d3e8d-236">Die Kennwort-Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-236">The user password credential.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-237">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-237">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="d3e8d-238"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="d3e8d-238"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="d3e8d-239">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-239">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="d3e8d-240">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-240">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-241">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-241">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="d3e8d-242">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-242">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="d3e8d-243">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="d3e8d-243">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-244">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-244">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-245">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-245">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="d3e8d-246">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-246">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="d3e8d-247">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-247">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="d3e8d-248">Die RedrectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-248">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="d3e8d-249">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="d3e8d-249">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="d3e8d-250">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="d3e8d-250">User Identifier</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-251">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-251">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="d3e8d-252"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="d3e8d-252"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="d3e8d-253">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-253">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="d3e8d-254">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-254">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-255">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-255">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="d3e8d-256">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-256">The connection string.</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-257">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-257">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-258">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-258">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="d3e8d-259">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Thema Pfad und Name.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-259">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> from a connection string with specified topic path and name.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-260">Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-260">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="d3e8d-261">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-261">The connection string.</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-262">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-262">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-263">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-263">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-264">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-264">The message receive mode.</span></span></param>
        <summary><span data-ttu-id="d3e8d-265">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> von einer Verbindungszeichenfolge mit dem angegebenen themenpfad, Namen und Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-265">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> from a connection string with specified topic path, name and mode.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-266">Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-266">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity (Uri endpointAddress, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity (endpointAddress, topicPath, name, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="d3e8d-267">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-267">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="d3e8d-268">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="d3e8d-268">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="d3e8d-269">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-269">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="d3e8d-270">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-270">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="d3e8d-271">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-271">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="d3e8d-272"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="d3e8d-272"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="d3e8d-273">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-273">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="d3e8d-274">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-274">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-275">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-275">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="subscriptionClient.DeadLetter lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-276">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-276">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-277">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-277">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-278">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-278">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-279">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-279">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="d3e8d-280">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-280">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-281">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-281">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-282">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-282">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="d3e8d-283">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-283">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-284">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-284">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="d3e8d-285">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-285">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="d3e8d-286">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-286">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-287">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-287">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-288">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-288">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-289">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-289">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="d3e8d-290">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-290">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-291">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-291">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-292">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-292">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-293">Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-293">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-294">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-294">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-295">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-295">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="d3e8d-296">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-296">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-297">Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-297">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-298">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-298">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="d3e8d-299">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-299">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="d3e8d-300">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-300">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-301">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-301">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-302">Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-302">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="subscriptionClient.Defer lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-303">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-303">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-304">Wird die Verarbeitung einer Nachricht angehalten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-304">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="d3e8d-305">Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-305">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-306">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-306">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-307">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-307">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="d3e8d-308">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-308">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Defer (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-309">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-309">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-310">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-310">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="d3e8d-311">Wird die Verarbeitung einer Nachricht angehalten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-311">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="d3e8d-312">Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-312">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-313">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-313">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="d3e8d-314">Asynchron hält die Verarbeitung einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-314">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-315">Eine Taskinstanz, die den asynchronen darstellt zurückstellen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-315">A task instance that represents the asynchronous defer operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="d3e8d-316">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-316">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="d3e8d-317">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-317">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="d3e8d-318">Asynchron hält die Verarbeitung einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-318">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-319">Eine Taskinstanz, die den asynchronen darstellt zurückstellen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-319">A task instance that represents the asynchronous defer operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="d3e8d-320">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-320">The full pathname of the topic.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="d3e8d-321">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-321">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="d3e8d-322">Erstellt einen Format Name für unzustellbare Nachrichten Pfad unter Verwendung des angegebenen Thema Pfad und Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-322">Builds a format name deadletter path using the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-323">Die <see cref="T:System.String" /> geführt hat, aus dem Pfad den Format für unzustellbare Nachrichten unter Verwendung des angegebenen Thema Pfad und Abonnements erstellen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-323">The <see cref="T:System.String" /> resulted from building the format name deadletter path using the specified topic path and subscription name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatSubscriptionPath">
      <MemberSignature Language="C#" Value="public static string FormatSubscriptionPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatSubscriptionPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatSubscriptionPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatSubscriptionPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="d3e8d-324">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-324">The full pathname of the topic.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="d3e8d-325">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-325">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="d3e8d-326">Erstellt einen Format Name Abonnement Pfad unter Verwendung des angegebenen Thema Pfad und Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-326">Builds a format name subscription path using the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-327">Die <see cref="T:System.String" /> geführt hat, aus dem Pfad den Format-Abonnement unter Verwendung des angegebenen Thema Pfad und Abonnements erstellen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-327">The <see cref="T:System.String" /> resulted from building the format name subscription path using the specified topic path and subscription name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-328">Ruft die eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-328">Gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-329">Eine Nachricht, die Gruppierung von ermöglicht sitzungsbezogene Nachrichten zur Verarbeitung in einer einzelnen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-329">A message session that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="d3e8d-330">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-330">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="d3e8d-331">Ruft alle Nachrichten, deren Status der Sitzung, seit aktualisiert wurde, Sitzungen <paramref name="lastUpdatedTime" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-331">Retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-332">Eine Nachricht, die Gruppierung von ermöglicht sitzungsbezogene Nachrichten zur Verarbeitung in einer einzelnen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-332">A message session that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-333">Ruft die einer Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-333">Asynchronously gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-334">Eine Taskinstanz, die den asynchronen Ladevorgang Nachricht Sitzungen darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-334">A task instance that represents the asynchronous get message sessions operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="d3e8d-335">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-335">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="d3e8d-336">Ruft die einer Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-336">Asynchronously gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-337">Eine Taskinstanz, die den asynchronen Ladevorgang Nachricht Sitzungen darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-337">A task instance that represents the asynchronous get message sessions operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d3e8d-338">Ruft die messaging Factory, die für die Erstellung dieses Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-338">Gets the messaging factory used to create this subscription client.</span></span></summary>
        <value><span data-ttu-id="d3e8d-339">Der messaging-Factory für die Erstellung dieses Abonnement.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-339">The messaging factory used to create this subscription client.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d3e8d-340">Ruft die Meldung ab Empfangsmodus beim Verarbeiten der empfangenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-340">Gets the message receive mode when processing the received message.</span></span></summary>
        <value><span data-ttu-id="d3e8d-341">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> beim Verarbeiten der empfangenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-341">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> when processing the received message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d3e8d-342">Ruft den Namen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-342">Gets the name of the subscription.</span></span></summary>
        <value><span data-ttu-id="d3e8d-343">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-343">The name of the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="subscriptionClient.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-344">Führt die Aktion abbrechen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-344">Executes the abort action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAcceptMessageSession (sessionId, receiveMode, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="d3e8d-345">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-345">The session identifier of the message session.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="d3e8d-346">Den Empfangsmodus bei der Verarbeitung mit der Nachrichten empfängt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-346">The receive mode when processing with the receive messages.</span></span></param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-347">Der Zeitraum für die Verarbeitung von Nachrichten vor dem Timeout der Server-Wartevorgänge</span><span class="sxs-lookup"><span data-stu-id="d3e8d-347">The time span the server waits for processing messages before it times out</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-348">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-348">The time span the server waits for processing messages before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-349">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-349">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-350">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-350">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="d3e8d-351">Führt beim Aufrufen des BeginAcceptMessageSession-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-351">Executes upon calling the BeginAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-352">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Annehmen einer Sitzungs verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-352">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to accept a message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAddRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAddRule (Microsoft.ServiceBus.Messaging.RuleDescription description, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginAddRule (description As RuleDescription, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAddRule : Microsoft.ServiceBus.Messaging.RuleDescription * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAddRule (description, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="d3e8d-353">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-353">The rule description that provides metadata of the rule to add.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-354">Die Zeitspanne, die diesen Vorgang wartet, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-354">The time span this operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-355">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-355">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-356">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-356">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="d3e8d-357">Führt beim Aufrufen des BeginAddRule-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-357">Executes upon calling the BeginAddRule operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-358">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-358">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="d3e8d-359">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-359">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-360">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-360">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-361">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-361">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="d3e8d-362">Dieses Objekt wird übergeben, um die BeginClose delegieren, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-362">This object is passed to the BeginClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-363">Führt die Aktion "Schließen" beginnen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-363">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-364">Ein <see cref="T:System.IAsyncResult" />, das auf den asynchronen BeginClose verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-364">An <see cref="T:System.IAsyncResult" />that references the asynchronous BeginClose.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="d3e8d-365">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-365">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-366">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-366">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-367">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-367">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-368">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-368">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="d3e8d-369">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-369">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-370">Führt die Begin Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-370">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-371">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-371">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueuePath, string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueuePath, string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (subQueuePath, subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueuePath" Type="System.String" />
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueuePath"><span data-ttu-id="d3e8d-372">Der Pfad der Unterwarteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-372">The path of the subqueue.</span></span></param>
        <param name="subQueueName"><span data-ttu-id="d3e8d-373">Der Name der Unterwarteschlange.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-373">The name of the subqueue.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="d3e8d-374">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-374">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-375">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-375">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-376">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-376">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-377">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-377">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="d3e8d-378">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-378">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-379">Führt die Begin Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-379">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-380">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Async-Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-380">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent async method.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="d3e8d-381">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-381">The time the session was last updated.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-382">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-382">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-383">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-383">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="d3e8d-384">Führt beim Aufrufen des BeginGetMessageSessions-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-384">Executes upon calling the BeginGetMessageSessions operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-385">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-385">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetRules">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetRules (int top, int skip, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetRules(int32 top, int32 skip, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetRules(System.Int32,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetRules (top As Integer, skip As Integer, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetRules : int * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetRules (top, skip, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="top">To be added.</param>
        <param name="skip">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRule (string ruleName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRule(string ruleName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRule (ruleName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRule : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRule (ruleName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="d3e8d-386">Der Name des zu entfernenden Regel an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-386">The name of the rule to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-387">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-387">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-388">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-388">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-389">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-389">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="d3e8d-390">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-390">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-391">Beginnt, Entfernen einer <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> aus einer <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> durch die Laufzeit-Clientprotokoll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-391">Begins removing a <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> from a <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> through the run-time client protocol.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-392">Ein <see cref="T:System.IAsyncResult" /> verweist, die auf den asynchronen <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-392">An <see cref="T:System.IAsyncResult" /> that references the asynchronous <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRulesByTag">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRulesByTag (string tag, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRulesByTag(string tag, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRulesByTag(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRulesByTag (tag As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRulesByTag : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRulesByTag (tag, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="d3e8d-393">Das Tag, die verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-393">The tag to be used.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3e8d-394">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-394">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="d3e8d-395">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-395">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d3e8d-396">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-396">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="d3e8d-397">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-397">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-398">Entfernen beginnt eine <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> aus einer <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> über die Laufzeit-Clientprotokoll mit einem Tag.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-398">Begins removing a <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> from a <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> through the run-time client protocol using a tag.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-399">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-399">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="subscriptionClient.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="d3e8d-400">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-400">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-401">Führt die Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="d3e8d-401">Executes the close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-402">Ein <see cref="T:System.IAsyncResult" /> zur Darstellung des Status des asynchronen Accept Nachricht Sitzung Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-402">An <see cref="T:System.IAsyncResult" /> that represents the status of the asynchronous accept message session operation.</span></span></param>
        <summary><span data-ttu-id="d3e8d-403">Führt beim Aufrufen des EndAcceptMessageSession-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-403">Executes upon calling the EndAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-404">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-404">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAddRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAddRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAddRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAddRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAddRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAddRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndAddRule result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-405">Ein <see cref="T:System.IAsyncResult" /> aus einem <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-405">An <see cref="T:System.IAsyncResult" /> from a <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary><span data-ttu-id="d3e8d-406">Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-406">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-407">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen BeginClose verweist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-407">An <see cref="T:System.IAsyncResult" /> that references the asynchronous BeginClose.</span></span></param>
        <summary><span data-ttu-id="d3e8d-408">Führt die End-Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="d3e8d-408">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="subscriptionClient.OnEndCreateReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-409">Ein <see cref="T:System.IAsyncResult" /> -Objekt, das verweist auf die <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-409">An <see cref="T:System.IAsyncResult" /> object that references the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />.</span></span></param>
        <summary><span data-ttu-id="d3e8d-410">Führt das Ende Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-410">Executes the end create receiver action.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-411">Ein neu erstelltes <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-411">A newly-created <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.OnEndGetMessageSessions result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-412">Das Ergebnis der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-412">The result of the message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-413">Führt die End Get-Nachrichtenaktion an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-413">Executes the end get message action.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-414">Ende Nachrichtenaktion abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-414">The end get message action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetRules">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetRules (result As IAsyncResult) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetRules : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="subscriptionClient.OnEndGetRules result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRule result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-415">Ein <see cref="T:System.IAsyncResult" /> aus einem <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-415">An <see cref="T:System.IAsyncResult" /> from a <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary><span data-ttu-id="d3e8d-416">Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-416">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRules">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRules (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRules : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRules result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="d3e8d-417">Das Ergebnis der Asynchronization.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-417">The result of the asynchronization.</span></span></param>
        <summary><span data-ttu-id="d3e8d-418">Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-418">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="subscriptionClient.OnMessage callback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d3e8d-419">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-419">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-420">Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem an.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-420">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessage (callback, onMessageOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d3e8d-421">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-421">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="d3e8d-422">Gibt an, die <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen zur Instanziierung der Meldungsverteilschleife.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-422">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="d3e8d-423">Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem, mit dem angegebenen Satz von <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-423">Processes a message in an event-driven message pump, with the given set of <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.OnMessageAsync callback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d3e8d-424">Die asynchrone Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-424">The asynchronous method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="d3e8d-425">Eine Nachricht verarbeitet asynchron.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-425">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessageAsync (callback, onMessageOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="d3e8d-426">Die asynchrone Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-426">The asynchronous method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="d3e8d-427">Die Optionen, die der Nachricht zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-427">The options associated with the message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-428">Eine Nachricht verarbeitet asynchron.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-428">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-429">Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-429">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-430">Die zurückgegebene Meldung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-430">The returned message.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-431">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-431">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="d3e8d-432">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-432">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-433">Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-433">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-434">Die zurückgegebene Meldung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-434">The returned message.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-435">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-435">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-436">Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-436">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-437">Eine Taskinstanz, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-437">A task instance that represents the asynchronous peek operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="d3e8d-438">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-438">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="d3e8d-439">Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-439">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-440">Eine Taskinstanz, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-440">A task instance that represents the asynchronous peek operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-441">Die Anzahl der Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-441">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="d3e8d-442">Gibt zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-442">Returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-443">Die Auflistung der ersten Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-443">The collection of first messages in a batch.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-444">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-444">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="d3e8d-445">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-445">The starting point from which to browse a message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="d3e8d-446">Die Anzahl der Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-446">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="d3e8d-447">Gibt zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-447">Returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-448">Die Auflistung der ersten Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-448">The collection of first messages in a batch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-449">Die Anzahl der Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-449">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="d3e8d-450">Gibt asynchron zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-450">Asynchronously returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-451">Eine Taskinstanz, die den asynchronen Lesevorgang für den Batch darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-451">A task instance that represents the asynchronous peek batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="d3e8d-452">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-452">The starting point from which to browse a message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="d3e8d-453">Die Anzahl der Nachrichten in einem Batch.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-453">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="d3e8d-454">Gibt asynchron zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-454">Asynchronously returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-455">Eine Taskinstanz, die den asynchronen Lesevorgang für den Batch darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-455">A task instance that represents the asynchronous peek batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d3e8d-456">Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-456">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="d3e8d-457">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-457">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="d3e8d-458">Wird für die nächste empfangsaufruf an den Server wirksam.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-458">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-459">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-459">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-460">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-460">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-461">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-461">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="d3e8d-462">Wird ausgelöst, wenn das Abonnement nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-462">Thrown when the subscription does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-463">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-463">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-464">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-464">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="d3e8d-465">Wird ausgelöst, wenn ein Authentifizierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-465">Thrown if there is an authentication error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="d3e8d-466">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-466">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="d3e8d-467">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-467">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-468">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-468">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-469">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-469">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-470">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-470">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-471">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-471">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-472">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-472">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-473">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-473">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-474">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-474">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d3e8d-475">Wird ausgelöst, wenn die <paramref name="serverWaitTime" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-475">Thrown if the <paramref name="serverWaitTime" /> is negative.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="d3e8d-476">Wird ausgelöst, wenn das Abonnement nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-476">Thrown when the subscription does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-477">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-477">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-478">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-478">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="d3e8d-479">Wird ausgelöst, wenn ein Authentifizierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-479">Thrown if there is an authentication error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d3e8d-480">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-480">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-481">Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-481">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="d3e8d-482">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-482">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="d3e8d-483">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-483">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-484">Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-484">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-485">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-485">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="d3e8d-486">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-486">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-487">Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-487">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="d3e8d-488">Die Sequenznummer.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-488">The sequence number.</span></span></param>
        <summary><span data-ttu-id="d3e8d-489">Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-489">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-490">Ein Batch nach Abschluss des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-490">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-491">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-491">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-492">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-492">The number of messages to return in the batch.</span></span> <span data-ttu-id="d3e8d-493">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-493">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="d3e8d-494">Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-494">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-495">Ein Batch nach Abschluss des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-495">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-496">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-496">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-497">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-497">The number of messages to return in the batch.</span></span> <span data-ttu-id="d3e8d-498">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-498">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-499">Die Zeitspanne der Server wartet für die Verarbeitung von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-499">The time span the server waits for processing messages.</span></span></param>
        <summary><span data-ttu-id="d3e8d-500">Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-500">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-501">Ein Batch nach Abschluss des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-501">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3e8d-502">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-502">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="d3e8d-503">Die Sequenznummer.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-503">The sequence number.</span></span></param>
        <summary><span data-ttu-id="d3e8d-504">Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="d3e8d-504">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="d3e8d-505">Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-505">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-506">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-506">The number of messages to return in the batch.</span></span> <span data-ttu-id="d3e8d-507">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-507">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="d3e8d-508">Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="d3e8d-508">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="d3e8d-509">Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-509">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="d3e8d-510">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-510">The number of messages to return in the batch.</span></span> <span data-ttu-id="d3e8d-511">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-511">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="d3e8d-512">Die Zeitspanne der Server wartet für die Verarbeitung von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-512">The time span the server waits for processing messages.</span></span></param>
        <summary><span data-ttu-id="d3e8d-513">Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="d3e8d-513">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="d3e8d-514">Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-514">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="d3e8d-515">Der Typ des Handlers.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-515">The type of the handler.</span></span></param>
        <summary><span data-ttu-id="d3e8d-516">Registriert den Ereignishandler für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-516">Registers the handler for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="d3e8d-517">Der Typ des Handlers.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-517">The type of the handler.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-518">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-518">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-519">Registriert den Ereignishandler für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-519">Registers the handler for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="d3e8d-520">Der Typ des Handlers.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-520">The type of the handler.</span></span></param>
        <summary><span data-ttu-id="d3e8d-521">Asynchron registriert den Ereignishandler für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-521">Asynchronously registers the handler for the client session.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-522">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-522">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="d3e8d-523">Der Typ des Handlers.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-523">The type of the handler.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-524">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-524">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-525">Asynchron registriert den Ereignishandler für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-525">Asynchronously registers the handler for the client session.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-526">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-526">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="d3e8d-527">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-527">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-528">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-528">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-529">Registriert die Handlerfactory für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-529">Registers the handler factory for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="d3e8d-530">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-530">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-531">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-531">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-532">Registriert die Handlerfactory für die Clientsitzung.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-532">Registers the handler factory for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="d3e8d-533">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-533">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-534">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-534">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-535">Für die Clientsitzung registriert die Handlerfactory asynchron.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-535">Asynchronously registers the handler factory for the client session.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-536">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-536">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="d3e8d-537">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-537">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="d3e8d-538">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-538">The session handler options.</span></span></param>
        <summary><span data-ttu-id="d3e8d-539">Für die Clientsitzung registriert die Handlerfactory asynchron.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-539">Asynchronously registers the handler factory for the client session.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-540">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-540">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRule">
      <MemberSignature Language="C#" Value="public void RemoveRule (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveRule(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveRule (ruleName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveRule : string -&gt; unit" Usage="subscriptionClient.RemoveRule ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="d3e8d-541">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-541">The name of the rule.</span></span></param>
        <summary><span data-ttu-id="d3e8d-542">Entfernt die Regel beschriebenen <paramref name="ruleName" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-542">Removes the rule described by <paramref name="ruleName" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="d3e8d-543">Wird ausgelöst, wenn <paramref name="ruleName" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-543">Thrown if <paramref name="ruleName" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="d3e8d-544">Wird ausgelöst, wenn der Vorgang den Timeoutwert, die mittels der OperationTimeout-Eigenschaft festgelegt wurde überschritten.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-544">Thrown if the operation exceeded the timeout value set via the OperationTimeout Property.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="d3e8d-545">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-545">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="d3e8d-546">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-546">The name of the rule.</span></span></param>
        <summary><span data-ttu-id="d3e8d-547">Entfernt asynchron die Regel beschriebenen <paramref name="ruleName" />.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-547">Asynchronously removes the rule described by <paramref name="ruleName" />.</span></span></summary>
        <returns><span data-ttu-id="d3e8d-548">Eine Taskinstanz, die den asynchronen Entfernungsvorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-548">A task instance that represents the asynchronous remove rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="subscriptionClient.RenewMessageLock lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewMessageLockAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewMessageLockAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="subscriptionClient.RenewMessageLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d3e8d-549">Ruft ab, der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-549">Gets the full pathname of the topic.</span></span></summary>
        <value><span data-ttu-id="d3e8d-550">Der vollständige Pfadname des Themas.</span><span class="sxs-lookup"><span data-stu-id="d3e8d-550">The full pathname of the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>