<Type Name="QueueClient" FullName="Microsoft.ServiceBus.Messaging.QueueClient">
  <TypeSignature Language="C#" Value="public abstract class QueueClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit QueueClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class QueueClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type QueueClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="4c143-101">Stellt das Clientobjekt Warteschlange dar.</span><span class="sxs-lookup"><span data-stu-id="4c143-101">Represents the queue client object.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="queueClient.Abandon lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-102">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-102">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4c143-103">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="4c143-103">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="4c143-104">Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-104">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="4c143-105">Service Bus erhöht die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-105">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="4c143-106">Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-106">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-107">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-107">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-108">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-108">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Abandon (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-109">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-109">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-110">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-110">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-111">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="4c143-111">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="4c143-112">Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-112">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="4c143-113">Service Bus erhöht die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-113">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="4c143-114">Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-114">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-115">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-115">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4c143-116">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="4c143-116">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4c143-117">Die Meldung wird verworfen.</span><span class="sxs-lookup"><span data-stu-id="4c143-117">The discarded message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-118">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-118">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-119">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-119">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-120">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="4c143-120">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4c143-121">Die Meldung wird verworfen.</span><span class="sxs-lookup"><span data-stu-id="4c143-121">The discarded message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession " />
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
        <summary><span data-ttu-id="4c143-122">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-122">Accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="4c143-123">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-123">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-124">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-124">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-125">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-125">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession isExclusiveMode" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4c143-126">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-126">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-127">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion zuverlässigeren, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-127">Accepts a message session that allows grouping of related messages for processing in a single transaction ith whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession sessionId" />
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
        <param name="sessionId"><span data-ttu-id="4c143-128">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-128">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="4c143-129">Akzeptiert eine nachrichtensitzung, die für die Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-129">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="4c143-130">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-130">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-131">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-131">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-132">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-132">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-133">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-133">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4c143-134">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-134">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-135">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-135">Accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-136">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-136">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4c143-137">Wird ausgelöst, wenn <paramref name="serverWaitTime" /> ist kein positiver TimeSpan-Wert.</span><span class="sxs-lookup"><span data-stu-id="4c143-137">Thrown if <paramref name="serverWaitTime" /> is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-138">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-138">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-139">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-139">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4c143-140">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-140">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-141">Das Servertimeout für die Wartezeit</span><span class="sxs-lookup"><span data-stu-id="4c143-141">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4c143-142">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion zuverlässigeren, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-142">Accepts a message session that allows grouping of related messages for processing in a single transaction ith whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-143">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-143">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4c143-144">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-144">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-145">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-145">Accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-146">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-146">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-147">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-147">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4c143-148">Das Sitzungstoken für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="4c143-148">The session lock token.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-149">Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-149">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-150">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-150">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-151">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-151">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-152">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-152">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-153">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit dem angegebenen Bezeichner, und warten Sie Sitzungstimeout ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-153">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-154">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-154">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-155">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-155">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4c143-156">Wird ausgelöst, wenn <paramref name="serverWaitTime" /> ist kein positiver TimeSpan-Wert.</span><span class="sxs-lookup"><span data-stu-id="4c143-156">Thrown if <paramref name="serverWaitTime" /> is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-157">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-157">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-158">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-158">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-159">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-159">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4c143-160">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-160">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-161">Das Servertimeout für die Wartezeit</span><span class="sxs-lookup"><span data-stu-id="4c143-161">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4c143-162">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-162">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-163">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-163">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-164">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-164">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4c143-165">Die Sitzung locktoken</span><span class="sxs-lookup"><span data-stu-id="4c143-165">The session locktoken</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-166">Das Servertimeout für die Wartezeit</span><span class="sxs-lookup"><span data-stu-id="4c143-166">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4c143-167">Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-167">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync " />
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
        <summary><span data-ttu-id="4c143-168">Asynchron akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-168">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="4c143-169">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-169">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync isExclusiveMode" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4c143-170">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-170">Ture if exclusive mode, or false is not.</span></span></param>
        <summary><span data-ttu-id="4c143-171">Asynchron akzeptiert eine Sitzung, die Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus, und warten Sie Zeit Gruppierung verwandter Nachrichten zulässt.</span><span class="sxs-lookup"><span data-stu-id="4c143-171">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode and wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-172">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-172">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync sessionId" />
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
        <param name="sessionId"><span data-ttu-id="4c143-173">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-173">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="4c143-174">Asynchron akzeptiert eine Sitzung, die für die Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-174">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="4c143-175">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-175">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4c143-176">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-176">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-177">Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-177">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-178">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-178">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4c143-179">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-179">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-180">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-180">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-181">Asynchron akzeptiert eine Sitzung, die Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus, und warten Sie Zeit Gruppierung verwandter Nachrichten zulässt.</span><span class="sxs-lookup"><span data-stu-id="4c143-181">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode and wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-182">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-182">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-183">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-183">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4c143-184">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-184">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-185">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-185">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-186">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-186">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-187">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-187">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4c143-188">Das Sitzungstoken für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="4c143-188">The session lock token.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-189">Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-189">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-190">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-190">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-191">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-191">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-192">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-192">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-193">Asynchron akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit dem angegebenen Bezeichner, und warten Sie Sitzungstimeout ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-193">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="4c143-194">Das Ergebnis eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-194">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-195">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-195">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4c143-196">Erfassen, wenn der exklusive Modus, oder "false" nicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-196">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-197">Das Servertimeout für die Wartezeit</span><span class="sxs-lookup"><span data-stu-id="4c143-197">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4c143-198">Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-198">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4c143-199">Die Sitzungs-ID der Sitzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="4c143-199">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4c143-200">Die Sitzung locktoken</span><span class="sxs-lookup"><span data-stu-id="4c143-200">The session locktoken</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-201">Das Servertimeout für die Wartezeit</span><span class="sxs-lookup"><span data-stu-id="4c143-201">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4c143-202">Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-202">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="queueClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="4c143-203">Bei der Planung einer Nachricht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-203">Returned on scheduling a message.</span></span></param>
        <summary>
            <span data-ttu-id="4c143-204">Bricht eine geplante Nachricht</span><span class="sxs-lookup"><span data-stu-id="4c143-204">Cancels a scheduled message</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="queueClient.Complete lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-205">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-205">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-206">Schließt die Verarbeitung einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-206">Completes processing of a message.</span></span></summary>
        <remarks> <span data-ttu-id="4c143-207">Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c143-207">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="4c143-208">Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="4c143-208">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-209">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4c143-209">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-210">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-210">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4c143-211">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="4c143-211">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-212">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-212">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-213">Schließt asynchron verarbeiten einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="4c143-213">Asynchronously completes processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4c143-214">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-214">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="queueClient.CompleteBatch lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="4c143-215">Die Lock-Token mit gesperrten Nachrichten im Batch verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-215">The lock tokens associated with locked messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4c143-216">Schließt die Verarbeitung eines Nachrichtenbatches an.</span><span class="sxs-lookup"><span data-stu-id="4c143-216">Completes processing of a message batch.</span></span></summary>
        <remarks> <span data-ttu-id="4c143-217">Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="4c143-217">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="4c143-218">Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="4c143-218">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteBatchAsync lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="4c143-219">Die Lock-Token mit gesperrten Nachrichten im Batch verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-219">The lock tokens associated with locked messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4c143-220">Schließt die Verarbeitung eines Nachrichtenbatches asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="4c143-220">Asynchronously completes processing of a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-221">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-221">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="4c143-222">Der Pfad.</span><span class="sxs-lookup"><span data-stu-id="4c143-222">The path.</span></span></param>
        <summary><span data-ttu-id="4c143-223">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mit dem angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="4c143-223">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> with specified path.</span></span></summary>
        <returns><span data-ttu-id="4c143-224">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-224">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4c143-225">Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen.</span><span class="sxs-lookup"><span data-stu-id="4c143-225">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="4c143-226">Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-226">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="4c143-227">Das Format des Abschnitts lautet wie folgt:</span><span class="sxs-lookup"><span data-stu-id="4c143-227">The format of the section is as follows:</span></span>
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="4c143-228">Der Pfad.</span><span class="sxs-lookup"><span data-stu-id="4c143-228">The path.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-229">Der Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-229">The mode.</span></span></param>
        <summary><span data-ttu-id="4c143-230">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mit dem angegebenen Pfad und Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-230">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> with specified path and mode.</span></span></summary>
        <returns><span data-ttu-id="4c143-231">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-231">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4c143-232">Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen.</span><span class="sxs-lookup"><span data-stu-id="4c143-232">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="4c143-233">Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-233">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="4c143-234">Das Format des Abschnitts lautet wie folgt:</span><span class="sxs-lookup"><span data-stu-id="4c143-234">The format of the section is as follows:</span></span>
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4c143-235">Vollständig qualifizierten Domänennamen für Sercvice Bus.</span><span class="sxs-lookup"><span data-stu-id="4c143-235">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="4c143-236">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4c143-236">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4c143-237">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-237">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4c143-238">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-238">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="4c143-239">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="4c143-239">The client assertion certificate credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-240">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-240">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4c143-241"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="4c143-241"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4c143-242">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-242">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4c143-243">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-243">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4c143-244">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-244">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4c143-245">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="4c143-245">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4c143-246">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4c143-246">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4c143-247">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-247">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4c143-248">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-248">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="4c143-249">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="4c143-249">The app credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-250">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-250">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4c143-251"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="4c143-251"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4c143-252">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-252">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4c143-253">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-253">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4c143-254">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-254">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4c143-255">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="4c143-255">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4c143-256">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4c143-256">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4c143-257">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-257">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4c143-258">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-258">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="4c143-259">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-259">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="4c143-260">Die Kennwort-Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="4c143-260">The user password credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-261">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-261">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4c143-262"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="4c143-262"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4c143-263">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-263">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4c143-264">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-264">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4c143-265">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-265">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
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
        <param name="endpointAddress"><span data-ttu-id="4c143-266">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="4c143-266">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4c143-267">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4c143-267">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4c143-268">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-268">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4c143-269">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-269">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="4c143-270">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="4c143-270">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="4c143-271">Die RedrectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="4c143-271">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="4c143-272">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="4c143-272">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="4c143-273">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="4c143-273">User Identifier</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-274">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-274">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4c143-275"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="4c143-275"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4c143-276">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-276">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4c143-277">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-277">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4c143-278">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-278">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4c143-279">Die zu verwendende Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4c143-279">The connection string to use.</span></span></param>
        <summary><span data-ttu-id="4c143-280">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4c143-280">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="4c143-281">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="4c143-281">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> instance.</span></span></returns>
        <remarks><span data-ttu-id="4c143-282">Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-282">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-283">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="4c143-283">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4c143-284">Die zu verwendende Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4c143-284">The connection string to use.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-285">Die <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-285">The <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <summary><span data-ttu-id="4c143-286">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge und Empfangen von Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-286">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> using the specified connection string and receiving mode.</span></span></summary>
        <returns><span data-ttu-id="4c143-287">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="4c143-287">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> instance.</span></span></returns>
        <remarks><span data-ttu-id="4c143-288">Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-288">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-289">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="4c143-289">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4c143-290">Die verwendete Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4c143-290">The connection string used.</span></span></param>
        <param name="path"><span data-ttu-id="4c143-291">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-291">The path to the queue.</span></span></param>
        <summary><span data-ttu-id="4c143-292">Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Pfad.</span><span class="sxs-lookup"><span data-stu-id="4c143-292">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> from a connection string with the specified queue path.</span></span> <span data-ttu-id="4c143-293">Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="4c143-293">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="4c143-294">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-294">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4c143-295">Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</span><span class="sxs-lookup"><span data-stu-id="4c143-295">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-296">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="4c143-296">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4c143-297">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4c143-297">The connection string.</span></span></param>
        <param name="path"><span data-ttu-id="4c143-298">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-298">The path to the queue.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-299">Die <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-299">The <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <summary><span data-ttu-id="4c143-300">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Pfad und Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-300">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> from a connection string with the specified path and mode.</span></span> <span data-ttu-id="4c143-301">Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="4c143-301">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="4c143-302">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-302">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4c143-303">Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</span><span class="sxs-lookup"><span data-stu-id="4c143-303">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-304">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</span><span class="sxs-lookup"><span data-stu-id="4c143-304">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity(System.Uri,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity (endpointAddress, path, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4c143-305">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="4c143-305">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4c143-306">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4c143-306">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4c143-307">Der Pfad der Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-307">The path to the queue.</span></span></param>
        <param name="mode"><span data-ttu-id="4c143-308">Der Receive-Modus.</span><span class="sxs-lookup"><span data-stu-id="4c143-308">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4c143-309"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="4c143-309"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4c143-310">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-310">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4c143-311">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-311">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="4c143-312">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-312">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="queueClient.DeadLetter lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-313">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-313">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-314">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-314">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-315">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4c143-315">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-316">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-316">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4c143-317">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="4c143-317">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.DeadLetter (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-318">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-318">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-319">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-319">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-320">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-320">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="queueClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-321">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-321">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4c143-322">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-322">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4c143-323">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-323">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4c143-324">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-324">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-325">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4c143-325">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-326">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-326">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4c143-327">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="4c143-327">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-328">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-328">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-329">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-329">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-330">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-330">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-331">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-331">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-332">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-332">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-333">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-333">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-334">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-334">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-335">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-335">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4c143-336">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-336">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4c143-337">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-337">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4c143-338">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-338">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-339">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-339">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="queueClient.Defer lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-340">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-340">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-341">Wird die Verarbeitung einer Nachricht angehalten.</span><span class="sxs-lookup"><span data-stu-id="4c143-341">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="4c143-342">Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="4c143-342">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-343">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4c143-343">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-344">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-344">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4c143-345">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</span><span class="sxs-lookup"><span data-stu-id="4c143-345">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Defer (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-346">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-346">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-347">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-347">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-348">Wird die Verarbeitung einer Nachricht angehalten.</span><span class="sxs-lookup"><span data-stu-id="4c143-348">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="4c143-349">Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="4c143-349">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4c143-350">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-350">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4c143-351">Asynchron hält die Verarbeitung einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="4c143-351">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4c143-352">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-352">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4c143-353">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-353">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4c143-354">Die Eigenschaften der Nachricht ändern.</span><span class="sxs-lookup"><span data-stu-id="4c143-354">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4c143-355">Asynchron hält die Verarbeitung einer Nachricht ein.</span><span class="sxs-lookup"><span data-stu-id="4c143-355">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4c143-356">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-356">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath"><span data-ttu-id="4c143-357">Der Pfad an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-357">The path to the dead letter queue.</span></span></param>
        <summary><span data-ttu-id="4c143-358">Erstellt einen Formatnamen aus dem Pfad der angegebenen Dead-Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="4c143-358">Builds a format name from the specified dead letter queue path.</span></span></summary>
        <returns><span data-ttu-id="4c143-359">Die <see cref="T:System.String" /> geführt haben, erstellen Sie für den Pfad der angegebenen Dead Letter-Warteschlange den Formatnamen.</span><span class="sxs-lookup"><span data-stu-id="4c143-359">The <see cref="T:System.String" /> resulted from building the format name for the specified dead letter queue path.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions " />
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
        <summary><span data-ttu-id="4c143-360">Ruft die nachrichtensitzungen aktivieren, Sitzungen auf Warteschlangen zu suchen.</span><span class="sxs-lookup"><span data-stu-id="4c143-360">Gets the message sessions, enabling you to browse sessions on queues.</span></span></summary>
        <returns><span data-ttu-id="4c143-361">Die Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="4c143-361">The message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions lastUpdatedTime" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4c143-362">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="4c143-362">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="4c143-363">Ruft alle Nachrichten, deren Status der Sitzung, seit aktualisiert wurde, Sitzungen <paramref name="lastUpdatedTime" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-363">Retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-364">Die Message-Sitzungen.</span><span class="sxs-lookup"><span data-stu-id="4c143-364">The message sessions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync " />
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
        <summary><span data-ttu-id="4c143-365">Ruft asynchron den nachrichtensitzungen aktivieren, Suchen von Sitzungen auf Warteschlangen ab.</span><span class="sxs-lookup"><span data-stu-id="4c143-365">Asynchronously gets the message sessions, enabling you to browse sessions on queues.</span></span></summary>
        <returns><span data-ttu-id="4c143-366">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-366">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync lastUpdatedTime" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4c143-367">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="4c143-367">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="4c143-368">Ruft asynchron alle nachrichtensitzungen, deren Status der Sitzung, seit aktualisiert wurde <paramref name="lastUpdatedTime" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-368">Asynchronously retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-369">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-369">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4c143-370">Ruft ab oder legt die messagingfactory.</span><span class="sxs-lookup"><span data-stu-id="4c143-370">Gets or sets the messaging factory.</span></span></summary>
        <value><span data-ttu-id="4c143-371">Der messaging-Factory.</span><span class="sxs-lookup"><span data-stu-id="4c143-371">The messaging factory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4c143-372">Ruft die Meldung ab Empfangsmodus beim Verarbeiten der empfangenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-372">Gets the message receive mode when processing the received message.</span></span></summary>
        <value><span data-ttu-id="4c143-373">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> beim Verarbeiten der empfangenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-373">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> when processing the received message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="queueClient.OnAbort " />
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
        <summary><span data-ttu-id="4c143-374">Führt beim Aufrufen der Abort-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="4c143-374">Executes upon calling the Abort event.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int prefetchCount, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int32 prefetchCount, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Int32,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * int * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginAcceptMessageSession (sessionId, receiveMode, prefetchCount, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
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
        <Parameter Name="prefetchCount" Type="System.Int32" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId"></param>
        <param name="receiveMode"></param>
        <param name="prefetchCount"></param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="4c143-375">Die maximale Zeit, bevor der schließen-Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-375">The maximum time before the close operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4c143-376">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-376">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4c143-377">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="4c143-377">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4c143-378">Dieses Objekt wird übergeben, um die EndClose delegieren, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-378">This object is passed to the EndClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-379">Wird ausgeführt, wenn der schließende-Vorgang aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-379">Executes when the Close operation is called.</span></span></summary>
        <returns><span data-ttu-id="4c143-380">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-380">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
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
        <param name="receiveMode"><span data-ttu-id="4c143-381">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="4c143-381">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="4c143-382">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-382">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4c143-383">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-383">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4c143-384">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="4c143-384">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4c143-385">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-385">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-386">Führt die Begin Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4c143-386">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4c143-387">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-387">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueueName"><span data-ttu-id="4c143-388">Der Name der untergeordneten Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-388">Name of the sub-queue.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="4c143-389">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="4c143-389">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="4c143-390">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-390">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4c143-391">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-391">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4c143-392">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="4c143-392">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4c143-393">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-393">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-394">Führt die Begin Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4c143-394">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4c143-395">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-395">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateSender (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="4c143-396">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-396">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4c143-397">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-397">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4c143-398">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="4c143-398">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4c143-399">Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateSender(System.IAsyncResult)" />-Delegaten übergeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-399">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateSender(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-400">Führt die Begin Absender Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4c143-400">Executes the begin create sender action.</span></span></summary>
        <returns><span data-ttu-id="4c143-401">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist</span><span class="sxs-lookup"><span data-stu-id="4c143-401">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4c143-402">Das Datum und die Uhrzeit der letzten Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="4c143-402">The date and time of the last update.</span></span></param>
        <param name="callback"><span data-ttu-id="4c143-403">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-403">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4c143-404">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="4c143-404">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4c143-405">Führt die BeginGetMessageSessions-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="4c143-405">Executes the BeginGetMessageSessions action.</span></span></summary>
        <returns><span data-ttu-id="4c143-406">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen der nachrichtensitzungen verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-406">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the message sessions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="queueClient.OnClose timeout" />
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
        <param name="timeout"><span data-ttu-id="4c143-407">Die maximale Zeit, bevor der schließen-Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-407">The maximum time before the close operation times out.</span></span></param>
        <summary><span data-ttu-id="4c143-408">Führt beim Aufrufen der Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="4c143-408">Executes upon calling the Close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.OnEndAcceptMessageSession result" />
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
        <param name="result"><span data-ttu-id="4c143-409">Ein <see cref="T:System.IAsyncResult" /> zur Darstellung des Status des asynchronen Accept Nachricht Sitzung Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-409">An <see cref="T:System.IAsyncResult" /> that represents the status of the asynchronous accept message session operation.</span></span></param>
        <summary><span data-ttu-id="4c143-410">Führt beim Aufrufen des EndAcceptMessageSession-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4c143-410">Executes upon calling the EndAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="4c143-411">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-411">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="queueClient.OnEndClose result" />
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
        <param name="result"><span data-ttu-id="4c143-412">Das Ergebnis des asynchronen übergeordneten Methode.</span><span class="sxs-lookup"><span data-stu-id="4c143-412">The result of the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="4c143-413">Führt die End-Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="4c143-413">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="queueClient.OnEndCreateReceiver result" />
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
        <param name="result"><span data-ttu-id="4c143-414">Das Ergebnis des asynchronen <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-414">The result of the asynchronous <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> operation.</span></span></param>
        <summary><span data-ttu-id="4c143-415">Führt das Ende Empfänger Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4c143-415">Executes the end create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4c143-416">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="4c143-416">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="queueClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4c143-417">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-417">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="4c143-418">Führt das Ende Absender Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="4c143-418">Executes the end create sender action.</span></span></summary>
        <returns><span data-ttu-id="4c143-419">Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="4c143-419">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.OnEndGetMessageSessions result" />
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
        <param name="result"><span data-ttu-id="4c143-420">Das Ergebnis der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="4c143-420">The result of the session.</span></span></param>
        <summary><span data-ttu-id="4c143-421">Führt die End Get-Nachrichtenaktion an.</span><span class="sxs-lookup"><span data-stu-id="4c143-421">Executes the end get message action.</span></span></summary>
        <returns> <span data-ttu-id="4c143-422">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="4c143-422">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.OnMessage callback" />
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
        <param name="callback"><span data-ttu-id="4c143-423">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-423">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-424">Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem an.</span><span class="sxs-lookup"><span data-stu-id="4c143-424">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessage (callback, onMessageOptions)" />
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
        <param name="callback"><span data-ttu-id="4c143-425">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-425">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="4c143-426">Gibt an, die <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen zur Instanziierung der Meldungsverteilschleife.</span><span class="sxs-lookup"><span data-stu-id="4c143-426">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="4c143-427">Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem, mit dem angegebenen Satz von <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-427">Processes a message in an event-driven message pump, with the given set of <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.OnMessageAsync callback" />
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
        <param name="callback"><span data-ttu-id="4c143-428">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-428">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4c143-429">Eine Nachricht verarbeitet asynchron.</span><span class="sxs-lookup"><span data-stu-id="4c143-429">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessageAsync (callback, onMessageOptions)" />
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
        <param name="callback"><span data-ttu-id="4c143-430">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-430">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="4c143-431">Ruft eine Option für die Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="4c143-431">Calls a message option.</span></span></param>
        <summary><span data-ttu-id="4c143-432">Eine Nachricht verarbeitet asynchron.</span><span class="sxs-lookup"><span data-stu-id="4c143-432">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4c143-433">Ruft ab oder legt den vollständigen Pfadnamen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4c143-433">Gets or sets the full path name of the queue.</span></span></summary>
        <value><span data-ttu-id="4c143-434">Der Warteschlangenpfad relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="4c143-434">The queue path relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek " />
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
        <summary><span data-ttu-id="4c143-435">Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="4c143-435">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-436">Einer brokernachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-436">A brokered message.</span></span> <span data-ttu-id="4c143-437">Gibt alle Eigenschaften und den Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="4c143-437">Returns all properties and the message body.</span></span></returns>
        <remarks><span data-ttu-id="4c143-438">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-438">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4c143-439">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-439">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="4c143-440">Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="4c143-440">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-441">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4c143-441">The brokered message.</span></span></returns>
        <remarks><span data-ttu-id="4c143-442">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-442">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync " />
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
        <summary><span data-ttu-id="4c143-443">Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="4c143-443">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-444">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-444">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4c143-445">Die Sequenznummer, aus denen eine Nachricht einsehen.</span><span class="sxs-lookup"><span data-stu-id="4c143-445">The sequence number from where to peek a message.</span></span></param>
        <summary><span data-ttu-id="4c143-446">Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</span><span class="sxs-lookup"><span data-stu-id="4c143-446">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4c143-447">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-447">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4c143-448">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="4c143-448">The number of messages.</span></span></param>
        <summary><span data-ttu-id="4c143-449">Liest einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="4c143-449">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4c143-450">Ein Nachrichtenbatch eingesehen werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-450">A batch of messages peeked.</span></span> <span data-ttu-id="4c143-451">Gibt alle Eigenschaften und den Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="4c143-451">Returns all properties and the message body.</span></span></returns>
        <remarks><span data-ttu-id="4c143-452">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-452">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4c143-453">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-453">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4c143-454">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="4c143-454">The number of messages.</span></span></param>
        <summary><span data-ttu-id="4c143-455">Liest einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="4c143-455">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4c143-456">Ein Nachrichtenbatch eingesehen werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-456">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4c143-457">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="4c143-457">The number of message.</span></span></param>
        <summary><span data-ttu-id="4c143-458">Liest asynchron einen Batch von Nachrichten ein.</span><span class="sxs-lookup"><span data-stu-id="4c143-458">Asynchronously peeks a batch of message.</span></span></summary>
        <returns><span data-ttu-id="4c143-459">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-459">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4c143-460">Die Sequenznummer ab dem einen Batch von Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="4c143-460">The sequence number from where to peek a batch of message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4c143-461">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="4c143-461">The number of message.</span></span></param>
        <summary><span data-ttu-id="4c143-462">Liest asynchron einen Batch von Nachrichten ein.</span><span class="sxs-lookup"><span data-stu-id="4c143-462">Asynchronously peeks a batch of message.</span></span></summary>
        <returns><span data-ttu-id="4c143-463">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-463">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
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
        <summary><span data-ttu-id="4c143-464">Ruft ab oder legt die Anzahl der Nachrichten, die die messagingsitzung gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="4c143-464">Gets or sets the number of messages that the queue receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="4c143-465">Die Anzahl der Nachrichten, die die messagingsitzung gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="4c143-465">The number of messages that the queue receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="4c143-466">Wird für die nächste empfangsaufruf an den Server wirksam.</span><span class="sxs-lookup"><span data-stu-id="4c143-466">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive " />
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
        <summary><span data-ttu-id="4c143-467">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-467">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-468">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-468">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4c143-469">Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</span><span class="sxs-lookup"><span data-stu-id="4c143-469">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4c143-470">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-470">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-471">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-471">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-472">Wird ausgelöst, wenn die Meldung Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-472">Thrown if the message receive operation times out.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4c143-473">Wird ausgelöst, wenn ein e/a "oder" Security-Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-473">Thrown if an I/O or security error occurs.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4c143-474">Wird ausgelöst, wenn die messagingentität, die dem Vorgang zugeordnet nicht vorhanden ist oder wurde gelöscht.</span><span class="sxs-lookup"><span data-stu-id="4c143-474">Thrown if the messaging entity associated with the operation does not exist or it has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4c143-475">Wird ausgelöst, wenn der Benutzercode hat einige unerwarteter Vorgänge ausgeführt, oder das Servicebus-Gateway nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-475">Thrown if the user code has performed some unexpected operations, or the Service Bus gateway is down.</span></span> <span data-ttu-id="4c143-476">Überprüfen Sie die Ausnahmemeldung für den tatsächlichen Fehler.</span><span class="sxs-lookup"><span data-stu-id="4c143-476">Check the exception message for the actual error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="4c143-477">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="4c143-477">The sequence number of the deferred message to receive.</span></span> </param>
        <summary><span data-ttu-id="4c143-478">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-478">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-479">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-479">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4c143-480">Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</span><span class="sxs-lookup"><span data-stu-id="4c143-480">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4c143-481">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-481">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-482">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-482">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4c143-483">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-483">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-484">Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-484">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-485">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-485">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4c143-486">Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</span><span class="sxs-lookup"><span data-stu-id="4c143-486">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4c143-487">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-487">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4c143-488">Wird ausgelöst, wenn die <paramref name="serverWaitTime" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="4c143-488">Thrown if the <paramref name="serverWaitTime" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-489">Wird ausgelöst, wenn die Meldung Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-489">Thrown if the message receive operation times out.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-490">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-490">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4c143-491">Wird ausgelöst, wenn ein e/a "oder" Security-Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-491">Thrown if an I/O or security error occurs.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4c143-492">Wird ausgelöst, wenn die messagingentität, die dem Vorgang zugeordnet nicht vorhanden ist oder wurde gelöscht.</span><span class="sxs-lookup"><span data-stu-id="4c143-492">Thrown if the messaging entity associated with the operation does not exist or it has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4c143-493">Wird ausgelöst, wenn der Benutzercode hat einige unerwarteter Vorgänge ausgeführt, oder das Servicebus-Gateway nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-493">Thrown if the user code has performed some unexpected operations, or the Service Bus gateway is down.</span></span> <span data-ttu-id="4c143-494">Überprüfen Sie die Ausnahmemeldung für den tatsächlichen Fehler.</span><span class="sxs-lookup"><span data-stu-id="4c143-494">Check the exception message for the actual error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync " />
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
        <summary><span data-ttu-id="4c143-495">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-495">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-496">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-496">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="4c143-497">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="4c143-497">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="4c143-498">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-498">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-499">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-499">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4c143-500">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-500">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-501">Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-501">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-502">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-502">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="4c143-503">Die Sequenznummern, die die Nachrichten im Batch zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-503">The sequence numbers associated with the messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4c143-504">Empfängt einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="4c143-504">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-505">Ein Nachrichtenbatch.</span><span class="sxs-lookup"><span data-stu-id="4c143-505">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4c143-506">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-506">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4c143-507">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-507">The number of messages to return in the batch.</span></span> <span data-ttu-id="4c143-508">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-508">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4c143-509">Empfängt einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="4c143-509">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-510">Ein Nachrichtenbatch.</span><span class="sxs-lookup"><span data-stu-id="4c143-510">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4c143-511">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-511">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="4c143-512">Die Anzahl der Nachrichten in einem Batch zu empfangen. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-512">The number of messages to receive in a batch.As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-513">Die Zeitspanne, die der Server, für den Nachrichtenbatch gewartet wird eingehen, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-513">The time span that the server will wait for the message batch to arrive before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-514">Empfängt einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="4c143-514">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-515">Ein Nachrichtenbatch.</span><span class="sxs-lookup"><span data-stu-id="4c143-515">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4c143-516">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="4c143-516">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="4c143-517">Die Sequenznummern, die die Nachrichten im Batch zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="4c143-517">The sequence numbers associated with the messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4c143-518">Asynchron empfängt einen Nachrichtenbatch aus.</span><span class="sxs-lookup"><span data-stu-id="4c143-518">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-519">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-519">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4c143-520">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-520">The number of messages to return in the batch.</span></span> <span data-ttu-id="4c143-521">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-521">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4c143-522">Asynchron empfängt einen Nachrichtenbatch aus.</span><span class="sxs-lookup"><span data-stu-id="4c143-522">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-523">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-523">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="4c143-524">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4c143-524">The number of messages to return in the batch.</span></span> <span data-ttu-id="4c143-525">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-525">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4c143-526">Die Zeitspanne, die der Server, für den Nachrichtenbatch gewartet wird eingehen, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-526">The time span that the server will wait for the message batch to arrive before it times out.</span></span></param>
        <summary><span data-ttu-id="4c143-527">Asynchron empfängt einen Nachrichtenbatch aus.</span><span class="sxs-lookup"><span data-stu-id="4c143-527">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4c143-528">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-528">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="queueClient.RegisterSessionHandler handlerType" />
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
        <param name="handlerType"><span data-ttu-id="4c143-529">Der Handlertyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-529">The handler type.</span></span></param>
        <summary><span data-ttu-id="4c143-530">Registriert den Ereignishandler für die Sitzung mit bestimmten Typ an.</span><span class="sxs-lookup"><span data-stu-id="4c143-530">Registers the session handler with specific type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandler (handlerType, options)" />
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
        <param name="handlerType"><span data-ttu-id="4c143-531">Der Handlertyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-531">The handler type.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-532">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-532">The session handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-533">Registriert den Ereignishandler für die Sitzung mit spezifischen Typ und Ereignishandler.</span><span class="sxs-lookup"><span data-stu-id="4c143-533">Registers the session handler with specific type and handler options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync handlerType" />
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
        <param name="handlerType"><span data-ttu-id="4c143-534">Der Handlertyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-534">The handler type.</span></span></param>
        <summary><span data-ttu-id="4c143-535">Den Handler für die Sitzung registriert asynchron bestimmten Typ.</span><span class="sxs-lookup"><span data-stu-id="4c143-535">Asynchronously registers the session handler with specific type.</span></span></summary>
        <returns><span data-ttu-id="4c143-536">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-536">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync (handlerType, options)" />
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
        <param name="handlerType"><span data-ttu-id="4c143-537">Der Handlertyp.</span><span class="sxs-lookup"><span data-stu-id="4c143-537">The handler type.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-538">Der Handler Sitzungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-538">The session handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-539">Den Handler für die Sitzung registriert asynchron bestimmte die Optionen Type und Handler.</span><span class="sxs-lookup"><span data-stu-id="4c143-539">Asynchronously registers the session handler with specific type and handler options.</span></span></summary>
        <returns><span data-ttu-id="4c143-540">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-540">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4c143-541">Die Handlerfactory registriert werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-541">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-542">Die Ereignishandleroptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-542">The handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-543">Registriert eine Handlerfactory für Message-Sitzung mit der angegebenen Optionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-543">Registers a message session handler factory with specified options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4c143-544">Die Handlerfactory registriert werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-544">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-545">Die Ereignishandleroptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-545">The handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-546">Registriert eine Handlerfactory für Message-Sitzung mit der angegebenen Optionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-546">Registers a message session handler factory with specified options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4c143-547">Die Handlerfactory registriert werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-547">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-548">Die Ereignishandleroptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-548">The handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-549">Asynchron registriert eine Handlerfactory für Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="4c143-549">Asynchronously registers a message session handler factory.</span></span></summary>
        <returns><span data-ttu-id="4c143-550">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-550">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4c143-551">Die Handlerfactory registriert werden.</span><span class="sxs-lookup"><span data-stu-id="4c143-551">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4c143-552">Die Ereignishandleroptionen.</span><span class="sxs-lookup"><span data-stu-id="4c143-552">The handler options.</span></span></param>
        <summary><span data-ttu-id="4c143-553">Asynchron registriert eine Handlerfactory für Message-Sitzung.</span><span class="sxs-lookup"><span data-stu-id="4c143-553">Asynchronously registers a message session handler factory.</span></span></summary>
        <returns><span data-ttu-id="4c143-554">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="4c143-554">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="queueClient.RenewMessageLock lockToken" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="queueClient.RenewMessageLockAsync lockToken" />
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
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="queueClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4c143-555">Nachricht geplant werden</span><span class="sxs-lookup"><span data-stu-id="4c143-555">Message to be scheduled</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="4c143-556">Zeitpunkt der in die Warteschlange einreihen</span><span class="sxs-lookup"><span data-stu-id="4c143-556">Time of enqueue</span></span></param>
        <summary>
            <span data-ttu-id="4c143-557">Sendet eine Nachricht geplante</span><span class="sxs-lookup"><span data-stu-id="4c143-557">Sends a scheduled message</span></span>
            </summary>
        <returns><span data-ttu-id="4c143-558">Die Sequenznummer, die für den Abbruch erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-558">Sequence number that is needed for cancelling.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="queueClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4c143-559">die zu sendende Meldung.</span><span class="sxs-lookup"><span data-stu-id="4c143-559">The message to send.</span></span></param>
        <summary><span data-ttu-id="4c143-560">Sendet eine Nachricht über die <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-560">Sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4c143-561">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> müssen möglicherweise erhöhen den Wert der <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-561">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span> </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4c143-562">Wird ausgelöst, wenn die <paramref name="message" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="4c143-562">Thrown when the <paramref name="message" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4c143-563">Wird ausgelöst, wenn das Thema/Abonnement unterstützt nicht den Sendevorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="4c143-563">Thrown if the topic/subscription pointed to does not support the send operation.</span></span> <span data-ttu-id="4c143-564">D. h. für unzustellbare Nachrichten, die Warteschlange nicht unterstützt-Transportsendevorgängen.</span><span class="sxs-lookup"><span data-stu-id="4c143-564">That is, Deadletter queue does not support send operations.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4c143-565">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4c143-565">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4c143-566">Wird ausgelöst, wenn ein e/a oder Sicherheit Fehler vorliegt.</span><span class="sxs-lookup"><span data-stu-id="4c143-566">Thrown if there is an I/O or security error.</span></span></exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException"><span data-ttu-id="4c143-567">Wird ausgelöst, wenn bei der Serialisierung oder Deserialisierung ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="4c143-567">Thrown when an error occurs during serialization or deserialization.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4c143-568">Wird ausgelöst, wenn die Warteschlange nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="4c143-568">Thrown if the queue does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4c143-569">Wird ausgelöst, wenn ein Messagingfehler.</span><span class="sxs-lookup"><span data-stu-id="4c143-569">Thrown if there is a messaging error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4c143-570">die zu sendende Meldung.</span><span class="sxs-lookup"><span data-stu-id="4c143-570">The message to send.</span></span></param>
        <summary><span data-ttu-id="4c143-571">Sendet asynchron eine Meldung mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span><span class="sxs-lookup"><span data-stu-id="4c143-571">Asynchronously sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span></span></summary>
        <returns><span data-ttu-id="4c143-572">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-572">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="4c143-573">Die Auflistung der brokernachrichten zu senden.</span><span class="sxs-lookup"><span data-stu-id="4c143-573">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="4c143-574">Sendet eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="4c143-574">Sends a set of brokered messages (for batch processing).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="4c143-575">Die Auflistung der brokernachrichten zu senden.</span><span class="sxs-lookup"><span data-stu-id="4c143-575">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="4c143-576">Sendet asynchron eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="4c143-576">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="4c143-577">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4c143-577">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>