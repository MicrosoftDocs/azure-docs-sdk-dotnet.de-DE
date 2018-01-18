<Type Name="MessageSender" FullName="Microsoft.ServiceBus.Messaging.MessageSender">
  <TypeSignature Language="C#" Value="public abstract class MessageSender : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSender extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSender" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessageSender = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="75fdc-101">Die MessageSender-Klasse wird zum Senden von Nachrichten vom Service Bus verwendet.</span><span class="sxs-lookup"><span data-stu-id="75fdc-101">The MessageSender class is used to send messages from the Service Bus.</span></span> </summary>
    <remarks><span data-ttu-id="75fdc-102">Bitte beachten Sie, dass Übermittlungsmechanismus Nachricht keine standardmäßig alle Zeit zuverlässige Nachricht empfangen.</span><span class="sxs-lookup"><span data-stu-id="75fdc-102">Please note that message delivery mechanism does not provide by default all time reliable message receiving.</span></span> <span data-ttu-id="75fdc-103">Service Bus wird die Nachricht gelöscht, sobald sie das System verlässt.</span><span class="sxs-lookup"><span data-stu-id="75fdc-103">Service Bus deletes the message once it goes out of the system.</span></span> <span data-ttu-id="75fdc-104">Für eine garantierte Übermittlung können Sie den PeekLock Übermittlung-Modus verwenden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-104">For a guaranteed delivery, you can use the PeekLock delivery mode.</span></span>
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             <span data-ttu-id="75fdc-105">Erstellen Sie einen Sender MessageSender MyMessageSender = myQueueClient.CreateSender(SendMode.Default);</span><span class="sxs-lookup"><span data-stu-id="75fdc-105">// Create a sender MessageSender myMessageSender = myQueueClient.CreateSender(SendMode.Default);</span></span>
             
             <span data-ttu-id="75fdc-106">Senden von Nachrichten Liste&lt;Objekt&gt; Probleme = neue Liste&lt;Objekt&gt;(); Foreach (Var Problem Punkte) {myMessageSender.Send (neue BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="75fdc-106">// Send messages List&lt;object&gt; Issues = new List&lt;object&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             <span data-ttu-id="75fdc-107">Erstellen Sie einen Empfänger MessageReceiver MyMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span><span class="sxs-lookup"><span data-stu-id="75fdc-107">// Create a receiver MessageReceiver myMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span></span>
             
             <span data-ttu-id="75fdc-108">Empfangen von Nachrichten für (Int Count = 0; Anzahl &lt; Issues.Count; Anzahl ++) {Var Message = myMessageReceiver.Receive(); message.Complete(); }</span><span class="sxs-lookup"><span data-stu-id="75fdc-108">// Receive messages for (int count = 0; count &lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example></remarks>
  </Docs>
  <Members>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BatchFlushInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.MessageSender.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="75fdc-109">Ruft die batchleerungsintervall ab.</span><span class="sxs-lookup"><span data-stu-id="75fdc-109">Gets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="75fdc-110">Eine batchleerungsintervall.</span><span class="sxs-lookup"><span data-stu-id="75fdc-110">A batch flush interval.</span></span> <span data-ttu-id="75fdc-111">Der Standardwert ist 20 ms.</span><span class="sxs-lookup"><span data-stu-id="75fdc-111">The default value is 20 ms.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="75fdc-112">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> befindet sich im closing, closed oder fehlerhaften Status.</span><span class="sxs-lookup"><span data-stu-id="75fdc-112">Thrown when the <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> is in closing, closed, or faulted state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="BatchingEnabled">
      <MemberSignature Language="C#" Value="protected bool BatchingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BatchingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.BatchingEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property BatchingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BatchingEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSender.BatchingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="75fdc-113">Ruft einen Wert, der angibt, ob die Batchverarbeitung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="75fdc-113">Gets a value indicating whether the batching is enabled.</span></span></summary>
        <value><span data-ttu-id="75fdc-114">"true", wenn die Batchverarbeitung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="75fdc-114">true if batching is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCancelScheduledMessage">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCancelScheduledMessage (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCancelScheduledMessage(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginCancelScheduledMessage(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCancelScheduledMessage : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginCancelScheduledMessage (trackingContext, sequenceNumbers, timeout, callback, state)" />
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
        <param name="trackingContext"><span data-ttu-id="75fdc-115">Der Nachverfolgungskontext verwenden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-115">Tracking context to use.</span></span></param>
        <param name="sequenceNumbers"><span data-ttu-id="75fdc-116">Sequenznummer der Nachricht abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="75fdc-116">Sequence Number of the message to cancelled.</span></span></param>
        <param name="timeout"><span data-ttu-id="75fdc-117">Ein Client Side-Timeoutwert für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="75fdc-117">A client side timeout value for the operation.</span></span> <span data-ttu-id="75fdc-118">Der Vorgang abgebrochen werden soll, oder "Abbrechen", wenn die Dauer dieses Zeitlimit überschritten.</span><span class="sxs-lookup"><span data-stu-id="75fdc-118">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="75fdc-119">Der Benutzerrückruf, aufgerufen werden soll, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="75fdc-119">A user callback to be invoked when the operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="75fdc-120">Der Status bei Abschluss des Vorgangs an den Rückruf übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-120">The state to be passed to the callback when the operation completes.</span></span></param>
        <summary>
            <span data-ttu-id="75fdc-121">Konkrete Implementierungen überschreiben (falls erforderlich) dadurch was erfolgen soll, um geplante sendet "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="75fdc-121">This allows concrete implementations to override (if needed) what should be done to cancel scheduled sends</span></span>
            </summary>
        <returns><span data-ttu-id="75fdc-122">eine <see cref="T:System.IAsyncResult" /> für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="75fdc-122">a <see cref="T:System.IAsyncResult" /> for the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginScheduleMessage">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginScheduleMessage (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginScheduleMessage(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginScheduleMessage(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginScheduleMessage : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginScheduleMessage (trackingContext, messages, timeout, callback, state)" />
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
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="75fdc-123">Der Nachverfolgungskontext verwenden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-123">Tracking context to use.</span></span></param>
        <param name="messages"><span data-ttu-id="75fdc-124">Nachrichten geplant werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-124">Messages to be scheduled.</span></span></param>
        <param name="timeout"><span data-ttu-id="75fdc-125">Ein Client Side-Timeoutwert für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="75fdc-125">A client side timeout value for the operation.</span></span> <span data-ttu-id="75fdc-126">Der Vorgang abgebrochen werden soll, oder "Abbrechen", wenn die Dauer dieses Zeitlimit überschritten.</span><span class="sxs-lookup"><span data-stu-id="75fdc-126">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="75fdc-127">Der Benutzerrückruf, aufgerufen werden soll, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="75fdc-127">A user callback to be invoked when the operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="75fdc-128">Der Status bei Abschluss des Vorgangs an den Rückruf übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-128">The state to be passed to the callback when the operation completes.</span></span></param>
        <summary>
            <span data-ttu-id="75fdc-129">Dies ermöglicht es sich um konkrete Implementierungen überschreiben (falls erforderlich) sendet was erfolgen soll, wenn Sie planen</span><span class="sxs-lookup"><span data-stu-id="75fdc-129">This allows concrete implementations to override (if needed) what should be done to schedule sends</span></span>
            </summary>
        <returns><span data-ttu-id="75fdc-130">eine <see cref="T:System.IAsyncResult" /> für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="75fdc-130">a <see cref="T:System.IAsyncResult" /> for the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSend">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSend (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSend(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginSend(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginSend (trackingContext, messages, fromSync, timeout, callback, state)" />
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
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="messages"></param>
        <param name="fromSync"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary><span data-ttu-id="75fdc-131">Führt die Begin-Sendeaktion an.</span><span class="sxs-lookup"><span data-stu-id="75fdc-131">Executes the begin send action.</span></span> <span data-ttu-id="75fdc-132">Diese Methode ist für die interne Verwendung vorgesehen und kann nicht vom Benutzer in eine konkrete Klasse implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-132">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSendEventData">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSendEventData (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDatas, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSendEventData(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDatas, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginSendEventData(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSendEventData : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginSendEventData (trackingContext, eventDatas, timeout, callback, state)" />
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
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="eventDatas"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary><span data-ttu-id="75fdc-133">Führt die Begin Sendeaktion-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="75fdc-133">Executes the begin send event data action.</span></span> <span data-ttu-id="75fdc-134">Diese Methode ist für die interne Verwendung vorgesehen und kann nicht vom Benutzer in eine konkrete Klasse implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-134">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCancelScheduledMessage">
      <MemberSignature Language="C#" Value="protected abstract void OnEndCancelScheduledMessage (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndCancelScheduledMessage(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndCancelScheduledMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndCancelScheduledMessage (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndCancelScheduledMessage : IAsyncResult -&gt; unit" Usage="messageSender.OnEndCancelScheduledMessage result" />
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
        <param name="result"><span data-ttu-id="75fdc-135">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-135">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="75fdc-136">Löst ein Ereignis aus, wenn den Abbruch der geplanten Nachricht beendet.</span><span class="sxs-lookup"><span data-stu-id="75fdc-136">Raises an event when ending the cancellation of the scheduled message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndScheduleMessage">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;long&gt; OnEndScheduleMessage (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;int64&gt; OnEndScheduleMessage(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndScheduleMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndScheduleMessage (result As IAsyncResult) As IEnumerable(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member OnEndScheduleMessage : IAsyncResult -&gt; seq&lt;int64&gt;" Usage="messageSender.OnEndScheduleMessage result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="75fdc-137">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-137">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="75fdc-138">Löst ein Ereignis aus, wenn den Zeitplan für die Nachricht beendet.</span><span class="sxs-lookup"><span data-stu-id="75fdc-138">Raises an event when ending the message schedule.</span></span></summary>
        <returns><span data-ttu-id="75fdc-139">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-139">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSend">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSend (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSend(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndSend(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSend (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSend : IAsyncResult -&gt; unit" Usage="messageSender.OnEndSend result" />
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
        <param name="result"></param>
        <summary><span data-ttu-id="75fdc-140">Führt die Sendeaktion Ende an.</span><span class="sxs-lookup"><span data-stu-id="75fdc-140">Executes the end send action.</span></span> <span data-ttu-id="75fdc-141">Diese Methode ist für die interne Verwendung vorgesehen und kann nicht vom Benutzer in eine konkrete Klasse implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-141">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSendEventData">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSendEventData (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSendEventData(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndSendEventData(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSendEventData (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSendEventData : IAsyncResult -&gt; unit" Usage="messageSender.OnEndSendEventData result" />
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
        <param name="result"><span data-ttu-id="75fdc-142">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-142">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="75fdc-143">Führt End Sendeaktion-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="75fdc-143">Executes the end send event data action.</span></span> <span data-ttu-id="75fdc-144">Diese Methode ist für die interne Verwendung vorgesehen und kann nicht vom Benutzer in eine konkrete Klasse implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-144">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSend">
      <MemberSignature Language="C#" Value="protected virtual void OnSend (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSend(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnSend(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan -&gt; unit&#xA;override this.OnSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan -&gt; unit" Usage="messageSender.OnSend (trackingContext, messages, timeout)" />
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
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="75fdc-145">TrackingContext verwenden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-145">TrackingContext to use.</span></span></param>
        <param name="messages"><span data-ttu-id="75fdc-146">Eine Liste der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-146">A list of <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> to be sent.</span></span></param>
        <param name="timeout"><span data-ttu-id="75fdc-147">Ein Client Side-Timeoutwert für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="75fdc-147">A client side timeout value for the operation.</span></span> <span data-ttu-id="75fdc-148">Der Vorgang abgebrochen werden soll, oder "Abbrechen", wenn die Dauer dieses Zeitlimit überschritten.</span><span class="sxs-lookup"><span data-stu-id="75fdc-148">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75fdc-149">Konkrete Implementierungen überschreiben (falls erforderlich) dadurch was geschehen soll, Versand <paramref name="messages" /> auf synchrone Weise.</span><span class="sxs-lookup"><span data-stu-id="75fdc-149">This allows concrete implementations to override (if needed) what should be done when sending <paramref name="messages" /> in a synchronous manner.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="75fdc-150">In der Regel das Timeout stammen aus <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="75fdc-150">Typically the timeout comes from <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></para>
          <para><span data-ttu-id="75fdc-151">OnSend gleich <c>dies. OnEndSend (diese. OnBeginSend ("Nachrichten", "Timeout", "Null", "Null")); </c>.</span><span class="sxs-lookup"><span data-stu-id="75fdc-151">OnSend is equal to <c>this.OnEndSend(this.OnBeginSend(messages, timeout, null, null));</c>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public abstract string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.Path" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSender.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="75fdc-152">Ruft den Pfad der Warteschlange bzw. Thema relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="75fdc-152">Gets the path of the queue or topic relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="75fdc-153">Der Pfad der Warteschlange bzw. Thema relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</span><span class="sxs-lookup"><span data-stu-id="75fdc-153">The path of the queue or topic relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="messageSender.Send message" />
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
        <param name="message"><span data-ttu-id="75fdc-154">Die vermittelte Nachricht zu senden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-154">The brokered message to send.</span></span></param>
        <summary><span data-ttu-id="75fdc-155">Sendet den angegebene vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="75fdc-155">Sends the specified brokered message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="75fdc-156">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span><span class="sxs-lookup"><span data-stu-id="75fdc-156">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="75fdc-157">Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="75fdc-157">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="75fdc-158">Wird ausgelöst, wenn <paramref name="message" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="75fdc-158">Thrown when <paramref name="message" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendAsync message" />
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
        <param name="message"><span data-ttu-id="75fdc-159">Die vermittelte Nachricht zu senden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-159">The brokered message to send.</span></span></param>
        <summary><span data-ttu-id="75fdc-160">Asynchron sendet die angegebene vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="75fdc-160">Asynchronously sends the specified brokered message.</span></span></summary>
        <returns><span data-ttu-id="75fdc-161">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-161">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="messageSender.SendBatch messages" />
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
        <param name="messages"><span data-ttu-id="75fdc-162">Die Auflistung der brokernachrichten zu senden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-162">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="75fdc-163">Sendet eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="75fdc-163">Sends a set of brokered messages (for batch processing).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendBatchAsync messages" />
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
        <param name="messages"><span data-ttu-id="75fdc-164">Die Auflistung der brokernachrichten zu senden.</span><span class="sxs-lookup"><span data-stu-id="75fdc-164">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="75fdc-165">Sendet asynchron eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="75fdc-165">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="75fdc-166">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="75fdc-166">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal abstract bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSender.SupportsGetRuntimeEntityDescription" />
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