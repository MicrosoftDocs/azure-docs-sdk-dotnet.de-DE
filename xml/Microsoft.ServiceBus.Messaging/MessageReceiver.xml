<Type Name="MessageReceiver" FullName="Microsoft.ServiceBus.Messaging.MessageReceiver">
  <TypeSignature Language="C#" Value="public abstract class MessageReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="ecbee-101">Die MessageReceiver-Klasse dient zum Empfangen von Nachrichten aus der Nachrichtencontainer und bestätigen sie.</span><span class="sxs-lookup"><span data-stu-id="ecbee-101">The MessageReceiver class is used to receive messages from the message container and acknowledge them.</span></span> </summary>
    <remarks><span data-ttu-id="ecbee-102">Bitte beachten Sie, dass Übermittlungsmechanismus Nachricht keine standardmäßig alle Zeit zuverlässige Nachricht empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-102">Please note that message delivery mechanism does not provide by default all time reliable message receiving.</span></span> <span data-ttu-id="ecbee-103">Service Bus wird die Nachricht gelöscht, sobald sie das System verlässt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-103">Service Bus deletes the message once it goes out of the system.</span></span> <span data-ttu-id="ecbee-104">Für eine garantierte Übermittlung können Sie den PeekLock Übermittlung-Modus verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-104">For a guaranteed delivery, you can use the PeekLock delivery mode.</span></span>
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             <span data-ttu-id="ecbee-105">Erstellen Sie einen Sender MessageSender MyMessageSender = myQueueClient.CreateSender(SendMode.Default);</span><span class="sxs-lookup"><span data-stu-id="ecbee-105">// Create a sender MessageSender myMessageSender = myQueueClient.CreateSender(SendMode.Default);</span></span>
             
             <span data-ttu-id="ecbee-106">Senden von Nachrichten Liste&lt;Zeichenfolge&gt; Probleme = neue Liste&lt;Zeichenfolge&gt;(); Foreach (Var Problem Punkte) {myMessageSender.Send (neue BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="ecbee-106">// Send messages List&lt;string&gt; Issues = new List&lt;string&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             <span data-ttu-id="ecbee-107">Erstellen Sie einen Empfänger MessageReceiver MyMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span><span class="sxs-lookup"><span data-stu-id="ecbee-107">// Create a receiver MessageReceiver myMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span></span>
             
             <span data-ttu-id="ecbee-108">Empfangen von Nachrichten für (Int Count = 0; Anzahl &lt; Issues.Count; Anzahl ++) {Var Message = myMessageReceiver.Receive(); message.Complete(); }</span><span class="sxs-lookup"><span data-stu-id="ecbee-108">// Receive messages for (int count = 0; count &lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                    Receiving messages from a particular session
             //********************************************************************************
             
             <span data-ttu-id="ecbee-109">Erstellen von Abonnements Client SubscriptionClient MySubscriptionClient = Factory. CreateSubscriptionClient(mySubscription);</span><span class="sxs-lookup"><span data-stu-id="ecbee-109">// Create subscription client SubscriptionClient mySubscriptionClient = factory.CreateSubscriptionClient(mySubscription);</span></span>
             
             <span data-ttu-id="ecbee-110">Erstellen Sie einen Empfänger MessageReceiver MyMessageReceiver = mySubscriptionClient.AcceptMessageSession(ReceiveMode.PeekLock);</span><span class="sxs-lookup"><span data-stu-id="ecbee-110">// Create a receiver MessageReceiver myMessageReceiver = mySubscriptionClient.AcceptMessageSession(ReceiveMode.PeekLock);</span></span>
            
             <span data-ttu-id="ecbee-111">Empfangen von Nachrichten für (Int Count = 0; Anzahl \* Lt; Issues.Count; Anzahl ++) {Var Message = myMessageReceiver.Receive(); message.Complete(); }</span><span class="sxs-lookup"><span data-stu-id="ecbee-111">// Receive messages for (int count = 0; count \*lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="messageReceiver.Abandon lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-112">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-112">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="ecbee-113">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-113">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="ecbee-114">Wenn der Empfänger einer Nachricht ein Fehler auftritt, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-114">When the message receiver fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="ecbee-115">Service Bus erhöht die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-115">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="ecbee-116">Der Empfänger einer Nachricht kann nun entweder versuchen, erhalten die Nachricht erneut, oder verschieben Sie sie an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="ecbee-116">The message receiver now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Abandon (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-117">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-117">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-118">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-118">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-119">Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-119">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-120">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-120">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="ecbee-121">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-121">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="ecbee-122">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-122">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-123">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-123">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-124">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-124">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-125">Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-125">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="ecbee-126">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-126">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BatchFlushInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-127">Ruft die batchleerungsintervall ab.</span><span class="sxs-lookup"><span data-stu-id="ecbee-127">Gets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="ecbee-128">Batchleerungsintervall.</span><span class="sxs-lookup"><span data-stu-id="ecbee-128">The batch flush interval.</span></span> <span data-ttu-id="ecbee-129">Der Standardwert ist 20 ms.</span><span class="sxs-lookup"><span data-stu-id="ecbee-129">The default value is 20 ms.</span></span></value>
        <remarks><span data-ttu-id="ecbee-130">Sie können den Wert des Zertifikats über SbmpTransportSetting.BatchFlushInterval festlegen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-130">You can set the value of it via SbmpTransportSetting.BatchFlushInterval</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchingEnabled">
      <MemberSignature Language="C#" Value="protected bool BatchingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BatchingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property BatchingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BatchingEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-131">Ruft einen Wert, der angibt, ob die Batchverarbeitung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-131">Gets a value indicating whether the batching is enabled.</span></span></summary>
        <value><span data-ttu-id="ecbee-132">"true", wenn die Batchverarbeitung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="ecbee-132">true if batching is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="messageReceiver.Complete lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-133">Das Sperrtoken des der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="ecbee-133">The lock token of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span> <span data-ttu-id="ecbee-134">Dies ist nur verfügbar, wenn eine Nachricht im Peek / Lock-Modus empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="ecbee-134">This is only available when a message is received in peek-lock mode.</span></span> <span data-ttu-id="ecbee-135">Das Sperrtoken wird intern verwendet, um abzuschließen oder zu verwerfen einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-135">The lock token is used internally to complete or abandon a message.</span></span></param>
        <summary><span data-ttu-id="ecbee-136">Schließt den Empfangsvorgang für eine Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-136">Completes the receive operation on a message.</span></span>
            <span data-ttu-id="ecbee-137">Wenn AMQP verwendet wird, kann dieser Vorgang nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-137">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <remarks> <span data-ttu-id="ecbee-138">Diese Methode wird als ein Handshake zwischen dem Empfänger und die Service Bus für eine Zustellung der Nachricht verwendet.</span><span class="sxs-lookup"><span data-stu-id="ecbee-138">This method is used as a handshake between the receiver and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="ecbee-139">Wenn der Empfänger, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-139">If the receiver failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-140">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-140">The lock token.</span></span></param>
        <summary><span data-ttu-id="ecbee-141">Schließt den Empfangsvorgang für eine Nachricht asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="ecbee-141">Asynchronously completes the receive operation on a message.</span></span>
            <span data-ttu-id="ecbee-142">Wenn AMQP verwendet wird, kann dieser Vorgang nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-142">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <returns><span data-ttu-id="ecbee-143">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-143">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="messageReceiver.CompleteBatch lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="ecbee-144">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-144">The lock tokens.</span></span></param>
        <summary><span data-ttu-id="ecbee-145">Schließt den Receive-Vorgang für einen Batch von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-145">Completes the receive operation on a batch of message.</span></span>
            <span data-ttu-id="ecbee-146">Wenn AMQP verwendet wird, kann dieser Vorgang nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-146">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteBatchAsync lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="ecbee-147">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-147">The lock tokens.</span></span></param>
        <summary><span data-ttu-id="ecbee-148">Asynchron abgeschlossen wird den Empfangsvorgang für einen Batch von Nachrichten ein.</span><span class="sxs-lookup"><span data-stu-id="ecbee-148">Asynchronously completes the receive operation on a batch of message.</span></span>
            <span data-ttu-id="ecbee-149">Wenn AMQP verwendet wird, kann dieser Vorgang nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-149">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <returns><span data-ttu-id="ecbee-150">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-150">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="messageReceiver.DeadLetter lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-151">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-151">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="ecbee-152">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-152">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-153">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-153">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-154">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-154">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-155">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-155">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-156">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-156">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="ecbee-157">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-157">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="ecbee-158">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-158">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="ecbee-159">Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-159">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-160">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-160">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="ecbee-161">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="ecbee-161">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="ecbee-162">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-162">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-163">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-163">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-164">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-164">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-165">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="ecbee-165">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="ecbee-166">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-166">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-167">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-167">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="ecbee-168">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-168">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="ecbee-169">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-169">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="ecbee-170">Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="ecbee-170">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="ecbee-171">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-171">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="messageReceiver.Defer lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-172">Das Sperrtoken des der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="ecbee-172">The lock token of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span> <span data-ttu-id="ecbee-173">Dies ist nur verfügbar, wenn eine Nachricht im Peek / Lock-Modus empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="ecbee-173">This is only available when a message is received in peek-lock mode.</span></span> <span data-ttu-id="ecbee-174">Das Sperrtoken wird intern verwendet, um abzuschließen oder zu verwerfen einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-174">The lock token is used internally to complete or abandon a message.</span></span></param>
        <summary><span data-ttu-id="ecbee-175">Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="ecbee-175">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <remarks><span data-ttu-id="ecbee-176">Vor dem Verschieben der Benutzer sollte der Empfang der Nachricht für den späteren Abruf reserviert.</span><span class="sxs-lookup"><span data-stu-id="ecbee-176">Before deferring user should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="P:Microsoft.ServiceBus.Common.Fx.Exception"><span data-ttu-id="ecbee-177">Empfangen von Kontext ist null.</span><span class="sxs-lookup"><span data-stu-id="ecbee-177">Receive context is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Defer (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-178">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-178">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-179">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-179">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-180">Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="ecbee-180">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-181">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-181">The lock token.</span></span></param>
        <summary><span data-ttu-id="ecbee-182">Asynchron Aufschieben der Verarbeitung der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-182">Asynchronously defer the processing of the message.</span></span></summary>
        <returns><span data-ttu-id="ecbee-183">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-183">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="ecbee-184">Das Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="ecbee-184">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="ecbee-185">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-185">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="ecbee-186">Asynchron Aufschieben der Verarbeitung der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-186">Asynchronously defer the processing of the message.</span></span></summary>
        <returns><span data-ttu-id="ecbee-187">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-187">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockToken">
      <MemberSignature Language="C#" Value="protected static Guid GetLockToken (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig valuetype System.Guid GetLockToken(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockToken (message As BrokeredMessage) As Guid" />
      <MemberSignature Language="F#" Value="static member GetLockToken : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Guid" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="ecbee-188">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> aus dem das Sperrtoken abgerufen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-188">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from which to get the lock token.</span></span></param>
        <summary><span data-ttu-id="ecbee-189">Ruft das Sperrtoken gebunden an die Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="ecbee-189">Gets the lock token bound to the message.</span></span></summary>
        <returns><span data-ttu-id="ecbee-190">Das Sperrtoken der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-190">The lock token of the message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockTokens">
      <MemberSignature Language="C#" Value="protected static System.Collections.Generic.IEnumerable&lt;Guid&gt; GetLockTokens (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; GetLockTokens(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockTokens (messages As IEnumerable(Of BrokeredMessage)) As IEnumerable(Of Guid)" />
      <MemberSignature Language="F#" Value="static member GetLockTokens : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; seq&lt;Guid&gt;" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens messages" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="ecbee-191">Die Auflistung von Nachrichten aus der die Sperre Token abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-191">The collection of messages from which to get the lock tokens.</span></span></param>
        <summary><span data-ttu-id="ecbee-192">Ruft die Auflistung der Lock-Token aus der angegebenen Auflistung von Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="ecbee-192">Gets the collection of lock tokens from the specified collection of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-193">Die Auflistung der Lock-Token aus den angegebenen Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-193">The collection of lock tokens from the specified messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected internal virtual T GetProperty&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance !!T GetProperty&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetProperty``1" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Function GetProperty(Of T) () As T" />
      <MemberSignature Language="F#" Value="abstract member GetProperty : unit -&gt; 'T&#xA;override this.GetProperty : unit -&gt; 'T" Usage="messageReceiver.GetProperty " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"></typeparam>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-194">Ruft ab oder legt fest, der die Sequenznummer der Nachricht zuletzt eingesehen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-194">Gets or sets the sequence number of the message last peeked.</span></span></summary>
        <value><span data-ttu-id="ecbee-195">Die Sequenznummer der Nachricht zuletzt eingesehen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-195">The sequence number of the message last peeked.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-196">Ruft die Meldung ab Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="ecbee-196">Gets the message receive mode.</span></span></summary>
        <value><span data-ttu-id="ecbee-197">Die Nachricht Empfangsmodus.</span><span class="sxs-lookup"><span data-stu-id="ecbee-197">The message receive mode.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="protected internal virtual bool OffsetInclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected virtual void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-198">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-198">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-199">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-199">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    <span data-ttu-id="ecbee-200">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-200">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-201">Führt die Aktion der Abbruchvorgang durchgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="ecbee-201">Executes the abandon action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-202">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-202">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-203">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-203">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="ecbee-204">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-204">The properties to modify.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-205">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-205">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-206">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-206">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-207">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-207">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-208">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-208">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-209">Führt beim Aufrufen des Vorgangs OnAbandon oder BeginAbandon.</span><span class="sxs-lookup"><span data-stu-id="ecbee-209">Executes upon calling the OnAbandon or BeginAbandon operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-210">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abbrechen von Nachrichten und seine Sperre abgeben verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-210">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to abandon the messages and relinquish its lock.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-211">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-211">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="deliveryTags"> <span data-ttu-id="ecbee-212">Eine Auflistung von Übermittlung Tags.</span><span class="sxs-lookup"><span data-stu-id="ecbee-212">A collection of delivery tags.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-213">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-213">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-214">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-214">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-215">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-215">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-216">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-216">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-217">Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</span><span class="sxs-lookup"><span data-stu-id="ecbee-217">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-218">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Empfangen von Nachrichten abschließen verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-218">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-219">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-219">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-220">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-220">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-221">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-221">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-222">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-222">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-223">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-223">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-224">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-224">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-225">Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</span><span class="sxs-lookup"><span data-stu-id="ecbee-225">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-226">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Empfangen von Nachrichten abschließen verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-226">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-227">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-227">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-228">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-228">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="ecbee-229">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-229">The properties to modify.</span></span></param>
        <param name="deadLetterReason"> <span data-ttu-id="ecbee-230">Der Grund für unzustellbare Nachrichten Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-230">The reason for deadlettering the messages.</span></span></param>
        <param name="deadLetterErrorDescription"> <span data-ttu-id="ecbee-231">Die fehlerbeschreibung für unzustellbare Nachrichten Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-231">The error description for deadlettering the messages.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-232">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-232">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-233">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-233">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-234">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-234">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-235">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-235">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-236">Führt beim Aufrufen des Vorgangs OnDeadLetter oder BeginDeadLetter.</span><span class="sxs-lookup"><span data-stu-id="ecbee-236">Executes upon calling the OnDeadLetter or BeginDeadLetter operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-237">Ein<see cref="T:System.IAsyncResult" /> , dass Verweise noch nicht der asynchrone Vorgang zum Verschieben von Nachrichten an die Warteschlange für unzustellbare Nachrichten abgeschlossene.</span><span class="sxs-lookup"><span data-stu-id="ecbee-237">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to move undelivered of messages to the deadletter queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-238">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-238">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-239">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-239">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="ecbee-240">Die Eigenschaften zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-240">The properties to modify.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-241">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-241">The start of synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-242">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-242">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-243">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-243">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-244">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-244">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-245">Führt beim Aufrufen des Vorgangs OnDefer oder BeginDefer.</span><span class="sxs-lookup"><span data-stu-id="ecbee-245">Executes upon calling the OnDefer or BeginDefer operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-246">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Anhalten der Verarbeitung von Nachrichten verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-246">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to suspend processing of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-247">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-247">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="ecbee-248">Die Sequenznummer aus, wo Sie den Vorgang zu starten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-248">The sequence number from where to begin the operation.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ecbee-249">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-249">The number of message.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-250">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-250">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-251">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-251">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-252">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-252">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-253">Beim Aufrufen des Vorgangs BeginPeek führt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-253">Executes upon calling the BeginPeek operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-254">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ecbee-254">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-255">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-255">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-256">Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-256">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="ecbee-257">Der Beginn der Synchronisierung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-257">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-258">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-258">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="ecbee-259">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-259">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-260">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-260">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-261">Führt beim Aufrufen des Vorgangs OnBegin für Sperren von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-261">Executes upon calling the OnBegin operation for lock messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-262">Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Erneuern Sie die Verarbeitung von Nachrichten Sperre verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-262">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to renew processing of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, sequenceNumbers, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-263">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-263">TrackingContext to use.</span></span></param>
        <param name="sequenceNumbers"> <span data-ttu-id="ecbee-264">Die SequenceNumbers.</span><span class="sxs-lookup"><span data-stu-id="ecbee-264">The sequenceNumbers.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ecbee-265">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-265">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="ecbee-266">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ecbee-266">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="ecbee-267">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ecbee-267">The state.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-268">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-268">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ecbee-269">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-269">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-270">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-270">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ecbee-271">Anzahl der Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-271">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="ecbee-272">Der Server-Wartezeit aus, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-272">The server wait time before it times out.</span></span> </param>
        <param name="callback">     <span data-ttu-id="ecbee-273">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ecbee-273">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="ecbee-274">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ecbee-274">The state.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-275">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-275">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ecbee-276">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-276">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-277">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-277">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ecbee-278">Anzahl der Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-278">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="ecbee-279">Der Server-Wartezeit aus, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-279">The server wait time before it times out.</span></span> </param>
        <param name="callback">     <span data-ttu-id="ecbee-280">Der Rückruf.</span><span class="sxs-lookup"><span data-stu-id="ecbee-280">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="ecbee-281">Der Zustand.</span><span class="sxs-lookup"><span data-stu-id="ecbee-281">The state.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-282">Führt die Begin Try Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-282">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ecbee-283">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-283">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginTryReceiveEventData (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceiveEventData(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceiveEventData(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceiveEventData (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-284">Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-284">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="messageCount"><span data-ttu-id="ecbee-285">Die Anzahl der Nachrichten empfangen zu versuchen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-285">The number of messages to try receiving.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="ecbee-286">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-286">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="ecbee-287">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-287">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="ecbee-288">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="ecbee-288">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-289">Führt beim Aufrufen des Vorgangs OnTryReceive oder BeginTryReceive für die Ereignisdaten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-289">Executes upon calling the OnTryReceive or BeginTryReceive operation for the event data.</span></span></summary>
        <returns><span data-ttu-id="ecbee-290">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um zu versuchen, die zum Empfangen von Ereignisdaten verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-290">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive event data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit&#xA;override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-291">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-291">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-292">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-292">The lock tokens.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="ecbee-293">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-293">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-294">Führt die Aktion abgeschlossene.</span><span class="sxs-lookup"><span data-stu-id="ecbee-294">Executes the complete action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected virtual void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit&#xA;override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageReceiver.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-295">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-295">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-296">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-296">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="deadLetterReason">  <span data-ttu-id="ecbee-297">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-297">The reason for deadlettering the message.</span></span> </param>
        <param name="deadLetterErrorDescription">  <span data-ttu-id="ecbee-298">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="ecbee-298">The description information for deadlettering the message.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="ecbee-299">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-299">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-300">Führt den Wechsel zu unzustellbare speicherwarteschlangen-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-300">Executes the move to dead letter queue action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected virtual void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-301">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-301">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-302">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-302">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    <span data-ttu-id="ecbee-303">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-303">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-304">Führt die Defer-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-304">Executes the defer action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndAbandon result" />
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
        <param name="result"><span data-ttu-id="ecbee-305">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-305">The result.</span></span></param>
        <summary><span data-ttu-id="ecbee-306">Führt die Endaktion der Abbruchvorgang durchgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="ecbee-306">Executes the end abandon action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected abstract void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndComplete : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndComplete result" />
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
        <param name="result"><span data-ttu-id="ecbee-307">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-307">The result.</span></span></param>
        <summary><span data-ttu-id="ecbee-308">Führt eine vollständige End-Aktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-308">Executes the end complete action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDeadLetter result" />
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
        <param name="result"><span data-ttu-id="ecbee-309">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen abgeschlossenen Vorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-309">An <see cref="T:System.IAsyncResult" /> object that references the asynchronously completed operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-310">Führt den End-Wechsel zu unzustellbare speicherwarteschlangen-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-310">Executes the end move to dead letter queue action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDefer : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDefer result" />
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
        <param name="result"><span data-ttu-id="ecbee-311">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-311">The result.</span></span></param>
        <summary><span data-ttu-id="ecbee-312">Führt das Ende Aktion verzögern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-312">Executes the end defer action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ecbee-313">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ecbee-313">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-314">Führt den EndPeek-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-314">Executes the EndPeek operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-315">Eine Liste von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-315">A list of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ecbee-316">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ecbee-316">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="ecbee-317">Führt eine Aktion EndRenew für nachrichtensperren.</span><span class="sxs-lookup"><span data-stu-id="ecbee-317">Executes the EndRenew action for message locks.</span></span></summary>
        <returns><span data-ttu-id="ecbee-318">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> Sperre Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-318">A <see cref="T:System.Collections.Generic.IEnumerable`1" /> of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ecbee-319">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-319">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="ecbee-320">Die empfangene Nachricht-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-320">The received message collection.</span></span></param>
        <summary><span data-ttu-id="ecbee-321">Führt das Ende versuchen Aktion empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-321">Executes the end try receive action.</span></span></summary>
        <returns><span data-ttu-id="ecbee-322">"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-322">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ecbee-323">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-323">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="ecbee-324">Die empfangene Nachricht-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-324">The received message collection.</span></span></param>
        <summary><span data-ttu-id="ecbee-325">Führt das Ende versuchen Aktion empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-325">Executes the end try receive action.</span></span></summary>
        <returns><span data-ttu-id="ecbee-326">"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-326">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual bool OnEndTryReceiveEventData (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceiveEventData(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceiveEventData(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnEndTryReceiveEventData (result As IAsyncResult, ByRef messages As IEnumerable(Of EventData)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool&#xA;override this.OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceiveEventData (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="ecbee-327">Das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="ecbee-327">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="ecbee-328">Die empfangene Nachricht-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-328">The received message collection.</span></span></param>
        <summary><span data-ttu-id="ecbee-329">Führt die EndTryReceive-Aktion für die Ereignisdaten an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-329">Executes the EndTryReceive action for the event data.</span></span></summary>
        <returns><span data-ttu-id="ecbee-330">"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-330">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessage (callback, options)" />
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
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="ecbee-331">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-331">The method to invoke when the operation is complete.</span></span></param>
        <param name="options"><span data-ttu-id="ecbee-332">Gibt an, die <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />Optionen zur Instanziierung der Meldungsverteilschleife.</span><span class="sxs-lookup"><span data-stu-id="ecbee-332">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="ecbee-333">Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem an.</span><span class="sxs-lookup"><span data-stu-id="ecbee-333">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessageAsync (callback, options)" />
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
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="ecbee-334">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="ecbee-334">The method to invoke when the operation is complete.</span></span></param>
        <param name="options"><span data-ttu-id="ecbee-335">Gibt an, die <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />Optionen zur Instanziierung der Meldungsverteilschleife.</span><span class="sxs-lookup"><span data-stu-id="ecbee-335">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="ecbee-336">Eine Nachricht in ein ereignisgesteuertes Nachrichtensystem verarbeitet asynchron.</span><span class="sxs-lookup"><span data-stu-id="ecbee-336">Asynchronously processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeek">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnPeek (trackingContext, fromSequenceNumber, messageCount, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-337">Der Nachverfolgungskontext.</span><span class="sxs-lookup"><span data-stu-id="ecbee-337">The tracking context.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="ecbee-338">Die Sequenznummer ab dem einsehen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-338">The sequence number from where to peek.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ecbee-339">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-339">The number of message.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-340">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-340">The time span the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="ecbee-341">Beim Aufrufen der Lesevorgang ausführt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-341">Executes upon calling the Peek operation.</span></span></summary>
        <returns><span data-ttu-id="ecbee-342">Die Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-342">The messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;&#xA;override this.OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnRenewMessageLocks (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="ecbee-343">Der Nachverfolgungskontext.</span><span class="sxs-lookup"><span data-stu-id="ecbee-343">The tracking context.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="ecbee-344">Die Lock-Token.</span><span class="sxs-lookup"><span data-stu-id="ecbee-344">The lock tokens.</span></span></param>
        <param name="timeout"> <span data-ttu-id="ecbee-345">Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-345">The time span the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="ecbee-346">Führt eine Aktion für die Sperre Nachrichten erneuern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-346">Executes the Renew action for lock messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-347">Die Nachrichten erneuerte Sperre.</span><span class="sxs-lookup"><span data-stu-id="ecbee-347">The renewed lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, sequenceNumbers, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-348">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-348">TrackingContext to use.</span></span></param>
        <param name="sequenceNumbers"> <span data-ttu-id="ecbee-349">Die eingehenden Bestätigungen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-349">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="ecbee-350">Das Timeout.</span><span class="sxs-lookup"><span data-stu-id="ecbee-350">The timeout.</span></span> </param>
        <param name="messages"> <span data-ttu-id="ecbee-351">[out] Die Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-351">[out] The messages.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-352">Wiederholen Sie dann führt Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-352">Executes the try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ecbee-353">"true", wenn es "false" erfolgreich ist, wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-353">true if it succeeds, false if it fails.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="ecbee-354">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-354">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="ecbee-355">Anzahl der Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-355">Number of messages.</span></span> </param>
        <param name="serverWaitTime">  <span data-ttu-id="ecbee-356">Der Server-Wartezeit aus, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-356">The server wait time before it times out.</span></span> </param>
        <param name="messages">     <span data-ttu-id="ecbee-357">[out] Die Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-357">[out] The messages.</span></span> </param>
        <summary> <span data-ttu-id="ecbee-358">Wiederholen Sie dann führt Empfangsaktion.</span><span class="sxs-lookup"><span data-stu-id="ecbee-358">Executes the try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="ecbee-359">"true", wenn es "false" erfolgreich ist, wenn ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-359">true if it succeeds, false if it fails.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public abstract string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-360">Ruft den Pfad der Warteschlange bzw. Thema relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="ecbee-360">Gets the path of the queue or topic, relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="ecbee-361">Eine Zeichenfolge, die den Pfad der Warteschlange bzw. Thema darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-361">A string representing the path of the queue or topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek " />
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
        <summary><span data-ttu-id="ecbee-362">Liest die nächste Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-362">Reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-363">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-363">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="ecbee-364">Die Sequenznummer ab dem die Nachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-364">The sequence number from where to read the message.</span></span></param>
        <summary><span data-ttu-id="ecbee-365">Liest die nächste Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-365">Reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-366">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-366">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync " />
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
        <summary><span data-ttu-id="ecbee-367">Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-367">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-368">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-368">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="ecbee-369">Die Sequenznummer ab dem die Nachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-369">The sequence number from where to read the message.</span></span></param>
        <summary><span data-ttu-id="ecbee-370">Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-370">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-371">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-371">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-372">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-372">The number of message.</span></span></param>
        <summary><span data-ttu-id="ecbee-373">Liest das nächste Batch von Nachrichten ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-373">Reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-374">Der Batch der Nachricht gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-374">The batch of message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="ecbee-375">Die Sequenznummer, aus denen eine batchnachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-375">The sequence number from where to read a batch message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="ecbee-376">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-376">The number of message.</span></span></param>
        <summary><span data-ttu-id="ecbee-377">Liest das nächste Batch von Nachrichten ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-377">Reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-378">Der Batch der Nachricht gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-378">The batch of message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-379">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-379">The number of message.</span></span></param>
        <summary><span data-ttu-id="ecbee-380">Liest asynchron das nächste Batch von Nachrichten ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-380">Asynchronously reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-381">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-381">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="ecbee-382">Die Sequenznummer, aus denen eine batchnachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-382">The sequence number from where to read a batch message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="ecbee-383">Die Nummer der Meldung.</span><span class="sxs-lookup"><span data-stu-id="ecbee-383">The number of message.</span></span></param>
        <summary><span data-ttu-id="ecbee-384">Liest asynchron das nächste Batch von Nachrichten ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-384">Asynchronously reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="ecbee-385">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-385">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-386">Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="ecbee-386">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="ecbee-387">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="ecbee-387">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="ecbee-388">Wird für die nächste empfangsaufruf an den Server wirksam.</span><span class="sxs-lookup"><span data-stu-id="ecbee-388">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive " />
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
        <summary><span data-ttu-id="ecbee-389">Empfängt eine <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> aus der aktuellen Warteschlange oder Thema.</span><span class="sxs-lookup"><span data-stu-id="ecbee-389">Receives a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-390">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-390">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-391">Ein NULL-Wert kann über diese API zurückgegeben, wenn Vorgang überschritten Ablauf des angegebenen Timeouts oder die Vorgänge war erfolgreich, aber es gibt keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-391">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="ecbee-392">Die Sequenznummer der Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-392">The sequence number of the message to receive.</span></span></param>
        <summary><span data-ttu-id="ecbee-393">Empfängt eine Nachricht aus der aktuellen Warteschlange oder Thema.</span><span class="sxs-lookup"><span data-stu-id="ecbee-393">Receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-394">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-394">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-395">Ein NULL-Wert kann über diese API zurückgegeben, wenn Vorgang überschritten Ablauf des angegebenen Timeouts oder die Vorgänge war erfolgreich, aber die Nachricht mit der angeforderten SequenceNumber kann nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-395">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="ecbee-396">Die Zeitspanne der Server wartet, bevor ein Timeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-396">The time span the server waits before the operation times out.</span></span></param>
        <summary><span data-ttu-id="ecbee-397">Empfängt eine <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> aus der aktuellen Warteschlange oder Thema.</span><span class="sxs-lookup"><span data-stu-id="ecbee-397">Receives a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-398">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="ecbee-398">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-399">Ein NULL-Wert kann über diese API zurückgegeben, wenn Vorgang überschritten Ablauf des angegebenen Timeouts oder die Vorgänge war erfolgreich, aber es gibt keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-399">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync " />
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
        <summary><span data-ttu-id="ecbee-400">Asynchron empfängt eine Nachricht aus der aktuellen Warteschlange oder Thema ein.</span><span class="sxs-lookup"><span data-stu-id="ecbee-400">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-401">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-401">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="ecbee-402">Die Sequenznummer der Nachricht zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-402">The sequence number of the message to receive.</span></span></param>
        <summary><span data-ttu-id="ecbee-403">Asynchron empfängt eine Nachricht aus der aktuellen Warteschlange oder Thema ein.</span><span class="sxs-lookup"><span data-stu-id="ecbee-403">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-404">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-404">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="ecbee-405">Die Zeitspanne der Server wartet, bevor ein Timeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-405">The time span the server waits before the operation times out.</span></span></param>
        <summary><span data-ttu-id="ecbee-406">Asynchron empfängt eine Nachricht aus der aktuellen Warteschlange oder Thema ein.</span><span class="sxs-lookup"><span data-stu-id="ecbee-406">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="ecbee-407">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-407">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="ecbee-408">Die Sequenznummern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-408">The sequence numbers.</span></span></param>
        <summary><span data-ttu-id="ecbee-409">Ein Batch von Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-409">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-410">Ein Batch von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-410">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-411">Ein NULL-Wert kann über diese API zurückgegeben, wenn Vorgang überschritten Ablauf des angegebenen Timeouts oder die Vorgänge war erfolgreich, aber die Nachricht mit der angeforderten SequenceNumber kann nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-411">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-412">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="ecbee-412">The number of messages to return in the batch.</span></span> <span data-ttu-id="ecbee-413">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-413">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="ecbee-414">Ein Batch von Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-414">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-415">Ein Batch von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-415">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-416">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-416">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-417">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="ecbee-417">The number of messages to return in the batch.</span></span> <span data-ttu-id="ecbee-418">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-418">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="ecbee-419">Die Wartezeit des Servers.</span><span class="sxs-lookup"><span data-stu-id="ecbee-419">The server wait time.</span></span></param>
        <summary><span data-ttu-id="ecbee-420">Ein Batch von Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="ecbee-420">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-421">Ein Batch von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="ecbee-421">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="ecbee-422">Ein NULL-Wert kann über diese API zurückgegeben, wenn Vorgang überschritten Ablauf des angegebenen Timeouts oder die Vorgänge war erfolgreich, aber es gibt keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ecbee-422">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="ecbee-423">Die Sequenznummern.</span><span class="sxs-lookup"><span data-stu-id="ecbee-423">The sequence numbers.</span></span></param>
        <summary><span data-ttu-id="ecbee-424">Ein Batch von Nachrichten empfangen asynchron.</span><span class="sxs-lookup"><span data-stu-id="ecbee-424">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-425">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-425">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-426">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="ecbee-426">The number of messages to return in the batch.</span></span> <span data-ttu-id="ecbee-427">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-427">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="ecbee-428">Ein Batch von Nachrichten empfangen asynchron.</span><span class="sxs-lookup"><span data-stu-id="ecbee-428">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-429">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-429">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="ecbee-430">Die Anzahl der Nachrichten im Batch zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="ecbee-430">The number of messages to return in the batch.</span></span> <span data-ttu-id="ecbee-431">Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ecbee-431">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="ecbee-432">Die Wartezeit des Servers.</span><span class="sxs-lookup"><span data-stu-id="ecbee-432">The server wait time.</span></span></param>
        <summary><span data-ttu-id="ecbee-433">Ein Batch von Nachrichten empfangen asynchron.</span><span class="sxs-lookup"><span data-stu-id="ecbee-433">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="ecbee-434">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ecbee-434">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverStartTime">
      <MemberSignature Language="C#" Value="protected internal virtual Nullable&lt;DateTime&gt; ReceiverStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ReceiverStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property ReceiverStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ReceiverStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-435">Ruft ab oder legt die Startzeit des Empfängers fest.</span><span class="sxs-lookup"><span data-stu-id="ecbee-435">Gets or sets the start time of the receiver.</span></span></summary>
        <value><span data-ttu-id="ecbee-436">Die Startzeit des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="ecbee-436">The start time of the receiver.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="protected internal virtual string StartOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property StartOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartOffset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="ecbee-437">Ruft ab oder legt den Ausgangspunkt des Offsets.</span><span class="sxs-lookup"><span data-stu-id="ecbee-437">Gets or sets the starting point of the offset.</span></span></summary>
        <value><span data-ttu-id="ecbee-438">Der Anfangspunkt des Offsets.</span><span class="sxs-lookup"><span data-stu-id="ecbee-438">The starting point of the offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal abstract bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>