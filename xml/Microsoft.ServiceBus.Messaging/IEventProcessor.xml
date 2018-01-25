<Type Name="IEventProcessor" FullName="Microsoft.ServiceBus.Messaging.IEventProcessor">
  <TypeSignature Language="C#" Value="public interface IEventProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessor" />
  <TypeSignature Language="F#" Value="type IEventProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3f2ea-101">Stellt Methoden zum Ereignis Prozessoren bereit.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-101">Provides methods for event processors.</span></span> <span data-ttu-id="3f2ea-102">Anwendungen müssen diese Schnittstelle die Behandlung von Ereignissen von Event Hubs ermöglicht implementieren.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-102">Applications must implement this interface, which enables the handling of events from Event Hubs.</span></span> <span data-ttu-id="3f2ea-103">Diese Schnittstelle ist der wesentliche Erweiterbarkeitspunkt für die EventProcessorHost und <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-103">This interface is the main extensibility point for the EventProcessorHost and <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (Microsoft.ServiceBus.Messaging.PartitionContext context, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (context As PartitionContext, reason As CloseReason) As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : Microsoft.ServiceBus.Messaging.PartitionContext * Microsoft.ServiceBus.Messaging.CloseReason -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.CloseAsync (context, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="3f2ea-104">Partition-Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-104">Partition ownership information for the partition on which this processor instance works.</span></span> <span data-ttu-id="3f2ea-105">Sie können Aufrufen <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> um Prüfpunkt Fortschritte bei der Verarbeitung von Nachrichten vom Event Hub-Streams.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-105">You can call <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> to checkpoint progress in the processing of messages from Event Hub streams.</span></span></param>
        <param name="reason"><span data-ttu-id="3f2ea-106">Der Grund für den Aufruf von <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-106">The reason for calling <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span></span></param>
        <summary><span data-ttu-id="3f2ea-107">Wird aufgerufen, wenn der Besitz der Partition auf einen anderen Knoten verschoben wird, für den Lastenausgleich Zweck, oder wenn der Host wird heruntergefahren.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-107">Called when the ownership of partition moves to a different node for load-balancing purpose, or when the host is shutting down.</span></span> <span data-ttu-id="3f2ea-108">Wird aufgerufen, als Antwort auf <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-108">Called in response to <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span></span></summary>
        <returns> <span data-ttu-id="3f2ea-109">Ein Task, der angibt, dass der schließen-Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-109">A task indicating that the Close operation is complete.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (Microsoft.ServiceBus.Messaging.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.OpenAsync(Microsoft.ServiceBus.Messaging.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (context As PartitionContext) As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.OpenAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="3f2ea-110">Die Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-110">Ownership information for the partition on which this processor instance works.</span></span> <span data-ttu-id="3f2ea-111">Jeder Versuch, rufen Sie <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> während der geöffnete Vorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-111">Any attempt to call <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> will fail during the Open operation.</span></span></param>
        <summary><span data-ttu-id="3f2ea-112">Initialisiert die Event Hub-Prozessor-Instanz.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-112">Initializes the Event Hub processor instance.</span></span> <span data-ttu-id="3f2ea-113">Diese Methode wird aufgerufen, bevor alle Ereignisdaten an diese Prozessorinstanz übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-113">This method is called before any event data is passed to this processor instance.</span></span></summary>
        <returns><span data-ttu-id="3f2ea-114">Der Task, der angibt, dass der Öffnungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-114">The task that indicates that the Open operation is complete.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (Microsoft.ServiceBus.Messaging.PartitionContext context, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (context As PartitionContext, messages As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : Microsoft.ServiceBus.Messaging.PartitionContext * seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessEventsAsync (context, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="3f2ea-115">Die Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-115">Ownership information for the partition on which this processor instance works.</span></span></param>
        <param name="messages"><span data-ttu-id="3f2ea-116">Ein Batch von Event Hubs-Ereignissen.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-116">A batch of Event Hubs events.</span></span></param>
        <summary><span data-ttu-id="3f2ea-117">Verarbeitet asynchron den angegebenen Kontext und Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-117">Asynchronously processes the specified context and messages.</span></span> <span data-ttu-id="3f2ea-118">Diese Methode wird aufgerufen, wenn neue Nachrichten im Event Hubs Datenstrom vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-118">This method is called when there are new messages in the Event Hubs stream.</span></span> <span data-ttu-id="3f2ea-119">Stellen Sie sicher, Prüfpunkt nur, wenn Sie alle Ereignisse in jedem Batch verarbeitet haben.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-119">Make sure to checkpoint only when you are finished processing all the events in each batch.</span></span></summary>
        <returns><span data-ttu-id="3f2ea-120">Der Task, der angibt, <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" /> ist abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="3f2ea-120">The task that indicates that <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" /> is complete.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>