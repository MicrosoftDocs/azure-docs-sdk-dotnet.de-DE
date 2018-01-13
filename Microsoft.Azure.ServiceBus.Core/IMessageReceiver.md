<Type Name="IMessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.IMessageReceiver">
  <TypeSignature Language="C#" Value="public interface IMessageReceiver : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageReceiver implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageReceiver&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type IMessageReceiver = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IReceiverClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="10c64-101">Die MessageReceiver kann zum Empfangen von Nachrichten aus Warteschlangen und Abonnements, und bestätigen sie verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-101">The MessageReceiver can be used to receive messages from Queues and Subscriptions and acknowledge them.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="10c64-102">Die MessageReceiver bietet erweiterte Funktionalität, die nicht in der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> oder <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-102">The MessageReceiver provides advanced functionality that is not found in the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> or <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span></span> <span data-ttu-id="10c64-103">Z. B. <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, dem können Sie zum Empfangen von Nachrichten bei Bedarf, erfordert jedoch auch manuell mithilfe von Sperren erneuern <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-103">For instance, <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, which allows you to receive messages on demand, but also requires you to manually renew locks using <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span></span>
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
    <example>
             <span data-ttu-id="10c64-104">Erstellen Sie eine neue MessageReceiver zum Empfangen einer Nachricht aus einem Abonnement</span><span class="sxs-lookup"><span data-stu-id="10c64-104">Create a new MessageReceiver to receive a message from a Subscription</span></span>
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="10c64-105">Eine Meldung aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="10c64-105">Receive a message from the Subscription.</span></span>
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="10c64-106">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> mit den Token sperren die entsprechenden Nachrichten abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="10c64-106">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the lock tokens of the corresponding messages to complete.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-107">Schließt eine Reihe von <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einer Liste von Token der Sperre.</span><span class="sxs-lookup"><span data-stu-id="10c64-107">Completes a series of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a list of lock tokens.</span></span> <span data-ttu-id="10c64-108">Hierdurch wird die Nachricht vom Dienst gelöscht.</span><span class="sxs-lookup"><span data-stu-id="10c64-108">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-109">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="10c64-109">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="10c64-110">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-110">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="10c64-111">Das Sperrtoken des der <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-111">The lock token of the <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="10c64-112">Die Eigenschaften der Nachricht zu ändern, während die Nachricht verzögern.</span><span class="sxs-lookup"><span data-stu-id="10c64-112">The properties of the message to modify while deferring the message.</span></span></param>
        <summary><span data-ttu-id="10c64-113">Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="10c64-113">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="10c64-114">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-114">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="10c64-115">Um diese Meldung erneut in der Zukunft Sie benötigen zum Speichern der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> und empfangen mit <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-115">In order to receive this message again in the future, you will need to save the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> and receive it using <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span></span>
            <span data-ttu-id="10c64-116">Verzögern von Nachrichten wirkt sich nicht der Nachricht Ablauf, was bedeutet, dass die verzögerte Nachrichten weiterhin ablaufen können.</span><span class="sxs-lookup"><span data-stu-id="10c64-116">Deferring messages does not impact message's expiration, meaning that deferred messages can still expire.</span></span>
            <span data-ttu-id="10c64-117">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="10c64-117">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="10c64-118">Ruft die Sequenznummer der letzten eingesehenen Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="10c64-118">Gets the sequence number of the last peeked message.</span></span></summary>
        <value><span data-ttu-id="10c64-119">Die Sequenznummer der letzten eingesehenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="10c64-119">The sequence number of the last peeked message.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10c64-120">Ruft die nächste active Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung ab.</span><span class="sxs-lookup"><span data-stu-id="10c64-120">Fetches the next active message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-121">Die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="10c64-121">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="10c64-122">Gibt null zurück, wenn nichts einsehen.</span><span class="sxs-lookup"><span data-stu-id="10c64-122">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="10c64-123">Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="10c64-123">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="10c64-124">Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="10c64-124">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="10c64-125">Im Gegensatz zu einer empfangenen Nachrichten eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.</span><span class="sxs-lookup"><span data-stu-id="10c64-125">Unlike a received messaged, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="10c64-126">Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)</span><span class="sxs-lookup"><span data-stu-id="10c64-126">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="10c64-127">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="10c64-127">The number of messages.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-128">Ruft den nächsten Batch aktiver Nachrichten ohne Ändern des Zustands der Empfänger oder die Quelle der Meldung ab.</span><span class="sxs-lookup"><span data-stu-id="10c64-128">Fetches the next batch of active messages without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-129">Liste der <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="10c64-129">List of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="10c64-130">Gibt null zurück, wenn nichts einsehen.</span><span class="sxs-lookup"><span data-stu-id="10c64-130">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="10c64-131">Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="10c64-131">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="10c64-132">Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="10c64-132">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="10c64-133">Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.</span><span class="sxs-lookup"><span data-stu-id="10c64-133">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="10c64-134">Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)</span><span class="sxs-lookup"><span data-stu-id="10c64-134">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="10c64-135">Die Sequenznummer ab dem die Nachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="10c64-135">The sequence number from where to read the message.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-136">Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="10c64-136">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-137">Den asynchronen Vorgang, die gibt die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="10c64-137">The asynchronous operation that returns the <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="10c64-138">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-138">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="10c64-139">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="10c64-139">The number of messages.</span></span></param>
        <summary><span data-ttu-id="10c64-140">Liest einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="10c64-140">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="10c64-141">Ein Nachrichtenbatch eingesehen werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-141">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10c64-142">Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="10c64-142">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-143">Die empfangene Nachricht.</span><span class="sxs-lookup"><span data-stu-id="10c64-143">The message received.</span></span> <span data-ttu-id="10c64-144">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-144">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="10c64-145">Timeout nach der Dauer des Vorgangs<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="10c64-145">Operation will time out after duration of <see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="10c64-146">Die maximale Anzahl von Nachrichten, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-146">The maximum number of messages that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-147">Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="10c64-147">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-148">Liste der Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="10c64-148">List of messages received.</span></span> <span data-ttu-id="10c64-149">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-149">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="10c64-150">Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</span><span class="sxs-lookup"><span data-stu-id="10c64-150">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="10c64-151">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="10c64-151">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-152">Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="10c64-152">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-153">Die empfangene Nachricht.</span><span class="sxs-lookup"><span data-stu-id="10c64-153">The message received.</span></span> <span data-ttu-id="10c64-154">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-154">Returns null if no message is found.</span></span></returns>
        <remarks>
            <span data-ttu-id="10c64-155">Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss).</span><span class="sxs-lookup"><span data-stu-id="10c64-155">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="10c64-156">Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-156">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="10c64-157">Die maximale Anzahl von Nachrichten, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-157">The maximum number of messages that will be received.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="10c64-158">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="10c64-158">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-159">Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="10c64-159">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-160">Liste der Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="10c64-160">List of messages received.</span></span> <span data-ttu-id="10c64-161">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-161">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="10c64-162">Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</span><span class="sxs-lookup"><span data-stu-id="10c64-162">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span>
            <span data-ttu-id="10c64-163">Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss).</span><span class="sxs-lookup"><span data-stu-id="10c64-163">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="10c64-164">Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-164">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="10c64-165">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , enthält die Sequenznummern empfangen.</span><span class="sxs-lookup"><span data-stu-id="10c64-165">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the sequence numbers to receive.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-166">Empfängt eine <see cref="T:System.Collections.Generic.IList`1" /> verzögerte Nachrichten identifizierten <paramref name="sequenceNumbers" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-166">Receives a <see cref="T:System.Collections.Generic.IList`1" /> of deferred messages identified by <paramref name="sequenceNumbers" />.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-167">Nachrichten, die Sequenznummer identifizierte werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="10c64-167">Messages identified by sequence number are returned.</span></span> <span data-ttu-id="10c64-168">Gibt null zurück, wenn keine Nachrichten gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-168">Returns null if no messages are found.</span></span>
            <span data-ttu-id="10c64-169">Löst aus, wenn die Nachrichten, nicht verzögert wurde.</span><span class="sxs-lookup"><span data-stu-id="10c64-169">Throws if the messages have not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="10c64-170">Die Sequenznummer der Nachricht, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-170">The sequence number of the message that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-171">Empfängt eine bestimmte verzögerte Nachricht erkennbar <paramref name="sequenceNumber" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-171">Receives a specific deferred message identified by <paramref name="sequenceNumber" />.</span></span>
            </summary>
        <returns><span data-ttu-id="10c64-172">Nachricht erkennbar Sequenznummer <paramref name="sequenceNumber" />.</span><span class="sxs-lookup"><span data-stu-id="10c64-172">Message identified by sequence number <paramref name="sequenceNumber" />.</span></span> <span data-ttu-id="10c64-173">Gibt null zurück, wenn keine solche Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="10c64-173">Returns null if no such message is found.</span></span>
            <span data-ttu-id="10c64-174">Löst aus, wenn die Nachricht nicht verzögert wurde.</span><span class="sxs-lookup"><span data-stu-id="10c64-174">Throws if the message has not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="10c64-175">Erneuert die Sperre für die Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="10c64-175">Renews the lock on the message.</span></span> <span data-ttu-id="10c64-176">Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-176">The lock will be renewed based on the setting specified on the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="10c64-177">Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).</span><span class="sxs-lookup"><span data-stu-id="10c64-177">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="10c64-178">Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-178">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="10c64-179">Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="10c64-179">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="iMessageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="10c64-180">Der Nachricht zugeordnete Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="10c64-180">Lock token associated with the message.</span></span></param>
        <summary>
            <span data-ttu-id="10c64-181">Erneuert die Sperre für die Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="10c64-181">Renews the lock on the message.</span></span> <span data-ttu-id="10c64-182">Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-182">The lock will be renewed based on the setting specified on the queue.</span></span>
            <span data-ttu-id="10c64-183"><returns>Neue Sperre token Ablaufdatum und die Uhrzeit in UTC-Format.</returns></span><span class="sxs-lookup"><span data-stu-id="10c64-183"><returns>New lock token expiry date and time in UTC format.</returns></span></span></summary>
        <returns><span data-ttu-id="10c64-184">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="10c64-184">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="10c64-185">Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).</span><span class="sxs-lookup"><span data-stu-id="10c64-185">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="10c64-186">Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="10c64-186">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="10c64-187">Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="10c64-187">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>