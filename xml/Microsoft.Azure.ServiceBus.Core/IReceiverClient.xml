<Type Name="IReceiverClient" FullName="Microsoft.Azure.ServiceBus.Core.IReceiverClient">
  <TypeSignature Language="C#" Value="public interface IReceiverClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReceiverClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReceiverClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type IReceiverClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IClientEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="22e21-101">Eine Schnittstelle, die zum beschreiben allgemeine Funktionen zum Empfangen von Nachrichten aus <see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" /> und <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-101">An interface used to describe common functionality for receiving messages from <see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" /> and <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />.</span></span>
            </summary>
    <remarks><span data-ttu-id="22e21-102">Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> für erweiterten Satz von Funktionen.</span><span class="sxs-lookup"><span data-stu-id="22e21-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="22e21-103">Das Sperrtoken der entsprechenden Nachricht zu verwerfen.</span><span class="sxs-lookup"><span data-stu-id="22e21-103">The lock token of the corresponding message to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="22e21-104">Die Eigenschaften der Nachricht zu ändern, während die Nachricht aufzugeben.</span><span class="sxs-lookup"><span data-stu-id="22e21-104">The properties of the message to modify while abandoning the message.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-105">Verwirft eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einem Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="22e21-105">Abandons a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a lock token.</span></span> <span data-ttu-id="22e21-106">Dadurch wird die Nachricht erneut für die Verarbeitung zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="22e21-106">This will make the message available again for processing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="22e21-107">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-107">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="22e21-108">Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="22e21-108">Abandoning a message will increase the delivery count on the message.</span></span>
            <span data-ttu-id="22e21-109">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="22e21-109">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.CompleteAsync lockToken" />
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="22e21-110">Das Sperrtoken der entsprechenden Nachricht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="22e21-110">The lock token of the corresponding message to complete.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-111">Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="22e21-111">Completes a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using its lock token.</span></span> <span data-ttu-id="22e21-112">Hierdurch wird die Nachricht aus der Warteschlange gelöscht.</span><span class="sxs-lookup"><span data-stu-id="22e21-112">This will delete the message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="22e21-113">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="22e21-113">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="22e21-114">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-114">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="22e21-115">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="22e21-115">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="22e21-116">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="22e21-116">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="22e21-117">Die Eigenschaften der Nachricht zu ändern, wenn zum untergeordneten Warteschlange verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="22e21-117">The properties of the message to modify while moving to sub-queue.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-118">Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.</span><span class="sxs-lookup"><span data-stu-id="22e21-118">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="22e21-119">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-119">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="22e21-120">Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.</span><span class="sxs-lookup"><span data-stu-id="22e21-120">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="22e21-121">Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.</span><span class="sxs-lookup"><span data-stu-id="22e21-121">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="22e21-122">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="22e21-122">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="22e21-123">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="22e21-123">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="22e21-124">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="22e21-124">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="22e21-125">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="22e21-125">The error description for deadlettering the message.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-126">Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.</span><span class="sxs-lookup"><span data-stu-id="22e21-126">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="22e21-127">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-127">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="22e21-128">Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.</span><span class="sxs-lookup"><span data-stu-id="22e21-128">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="22e21-129">Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.</span><span class="sxs-lookup"><span data-stu-id="22e21-129">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="22e21-130">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="22e21-130">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22e21-131">Ruft den Pfad der ab dem <see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />.</span><span class="sxs-lookup"><span data-stu-id="22e21-131">Gets the path of the <see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />.</span></span> <span data-ttu-id="22e21-132">Dies ist entweder der Name der Warteschlange oder den vollständigen Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="22e21-132">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22e21-133">Prefetch beschleunigt den Nachrichtenfluss durch ins Leben gerufen, eine Nachricht, die für den lokalen Abruf unmittelbar verfügbar sein, wenn und vor der Anwendung, für eine aufgefordert Verwendung empfangen.</span><span class="sxs-lookup"><span data-stu-id="22e21-133">Prefetch speeds up the message flow by aiming to have a message readily available for local retrieval when and before the application asks for one using Receive.</span></span>
            <span data-ttu-id="22e21-134">Einen Wert ungleich Null festlegen, vorab PrefetchCount Anzahl der Nachrichten abruft.</span><span class="sxs-lookup"><span data-stu-id="22e21-134">Setting a non-zero value prefetches PrefetchCount number of messages.</span></span>
            <span data-ttu-id="22e21-135">Festlegen des Werts auf 0 (null) wird Prefetch deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="22e21-135">Setting the value to zero turns prefetch off.</span></span>
            <span data-ttu-id="22e21-136">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="22e21-136">Defaults to 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="22e21-137">Wenn Sie Prefetch aktiviert ist, wird der Empfänger – abrufen Nachrichten mehr anzeigt, maximal der Größe PrefetchCount als was die Anwendung sofort anfordert.</span><span class="sxs-lookup"><span data-stu-id="22e21-137">When Prefetch is enabled, the receiver will quietly acquire more messages, up to the PrefetchCount limit, than what the application immediately asks for.</span></span> <span data-ttu-id="22e21-138">Ein einzelner Aufruf der ursprünglichen Receive/ReceiveAsync wird daher eine Nachricht abrufen, für sofortigen Verbrauch, die so bald wie verfügbaren zurückgegeben werden, und der Client zum Abrufen von weiterer Nachrichten zum Ausfüllen des Prefetch-Puffers im Hintergrund fortgesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="22e21-138">A single initial Receive/ReceiveAsync call will therefore acquire a message for immediate consumption that will be returned as soon as available, and the client will proceed to acquire further messages to fill the prefetch buffer in the background.</span></span>
            </para>
          <para>
            <span data-ttu-id="22e21-139">Während der Nachrichten im Puffer Prefetch verfügbar sind, alle nachfolgenden ReceiveAsync-Aufrufe werden sofort aus dem Puffer erfüllt, und wie Speicherplatz verfügbar ist, wird der Puffer im Hintergrund aufgefüllt. Keine Nachrichten für die Übermittlung verfügbar sind, wird der Empfangsvorgang und dann warten, oder blockieren wie erwartet ausgleichen den Puffer.</span><span class="sxs-lookup"><span data-stu-id="22e21-139">While messages are available in the prefetch buffer, any subsequent ReceiveAsync calls will be immediately satisfied from the buffer, and the buffer is replenished in the background as space becomes available.If there are no messages available for delivery, the receive operation will drain the buffer and then wait or block as expected.</span></span>
            </para>
          <para><span data-ttu-id="22e21-140">Updates für diesen Wert wirksam, auf die nächste empfangsaufruf an den Dienst.</span><span class="sxs-lookup"><span data-stu-id="22e21-140">Updates to this value take effect on the next receive call to the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22e21-141">Ruft die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> des aktuellen Empfängers.</span><span class="sxs-lookup"><span data-stu-id="22e21-141">Gets the <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> of the current receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="22e21-142">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="22e21-142">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="messageHandlerOptions"><span data-ttu-id="22e21-143">Die <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> Optionen zum Konfigurieren der Einstellungen der Datapump verwendet.</span><span class="sxs-lookup"><span data-stu-id="22e21-143">The <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> options used to configure the settings of the pump.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-144">Empfangen von Nachrichten dauerhaft aus der Entität.</span><span class="sxs-lookup"><span data-stu-id="22e21-144">Receive messages continuously from the entity.</span></span> <span data-ttu-id="22e21-145">Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="22e21-145">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="22e21-146">Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="22e21-146">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="22e21-147">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="22e21-147">Enable prefetch to speed up the receive rate.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="22e21-148">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="22e21-148">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="22e21-149">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="22e21-149">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="22e21-150"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="22e21-150"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="22e21-151">Empfangen von Nachrichten dauerhaft aus der Entität.</span><span class="sxs-lookup"><span data-stu-id="22e21-151">Receive messages continuously from the entity.</span></span> <span data-ttu-id="22e21-152">Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="22e21-152">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="22e21-153">Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="22e21-153">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="22e21-154">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="22e21-154">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="22e21-155">Verwendung <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</span><span class="sxs-lookup"><span data-stu-id="22e21-155">Use <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>