<Type Name="IEventProcessor" FullName="Microsoft.Azure.EventHubs.Processor.IEventProcessor">
  <TypeSignature Language="C#" Value="public interface IEventProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessor" />
  <TypeSignature Language="F#" Value="type IEventProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92a67-101">Schnittstelle, die vom Prozessor Ereignisklassen implementiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="92a67-101">Interface that must be implemented by event processor classes.</span></span>
            
            <span data-ttu-id="92a67-102"><para>Keine Instanz einer Ereignisklasse-Prozessor verarbeitet nur Ereignisse aus einer Partition einen Event Hub. Eine PartitionContext wird mit jedem Aufruf der Ereignisprozessor bereitgestellt, da einige Parameter geändert werden konnte, aber es wird immer die gleiche Partition sein. </para> <para>Zwar EventProcessorHost ist Multithread, Aufrufe an eine bestimmte Instanz einer Prozessor Ereignisklasse werden mit Ausnahme von OnError() serialisiert. OnOpen() zuerst aufgerufen wird, und dann OnEvents() wird nicht oder mehrmals aufgerufen werden. Wenn der muss der Ereignisprozessor heruntergefahren werden, ob Fehler an einer Stelle, oder die Lease für die Partition verloren gegangen oder weil der gesamte Prozessor Host heruntergefahren wird, OnClose() aufgerufen wird, nachdem der letzte OnEvents()-Aufruf zurückgegeben. </para> <para>OnError() konnte beim OnEvents() aufgerufen werden oder OnClose() ausgeführt wird. Keine Synchronisierung wird ausgeführt, um zu vermeiden, möglicherweise Deadlocks.</para></span><span class="sxs-lookup"><span data-stu-id="92a67-102"><para>Any given instance of an event processor class will only process events from one partition of one Event Hub. A PartitionContext is provided with each call to the event processor because some parameters could change, but it will always be the same partition.</para><para>Although EventProcessorHost is multithreaded, calls to a given instance of an event processor class are serialized, except for OnError(). OnOpen() is called first, then OnEvents() will be called zero or more times. When the event processor needs to be shut down, whether because there was a failure somewhere, or the lease for the partition has been lost, or because the entire processor host is being shut down, OnClose() is called after the last OnEvents() call returns.</para><para>OnError() could be called while OnEvents() or OnClose() is executing. No synchronization is attempted in order to avoid possibly deadlocking.</para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, Microsoft.Azure.EventHubs.Processor.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, valuetype Microsoft.Azure.EventHubs.Processor.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.CloseAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,Microsoft.Azure.EventHubs.Processor.CloseReason)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (context As PartitionContext, reason As CloseReason) As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * Microsoft.Azure.EventHubs.Processor.CloseReason -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.CloseAsync (context, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="reason" Type="Microsoft.Azure.EventHubs.Processor.CloseReason" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="92a67-103">Informationen zur Partition.</span><span class="sxs-lookup"><span data-stu-id="92a67-103">Information about the partition.</span></span></param>
        <param name="reason"><span data-ttu-id="92a67-104">Der Grund, warum der Ereignisprozessor beendet wird.</span><span class="sxs-lookup"><span data-stu-id="92a67-104">Reason why the event processor is being stopped.</span></span></param>
        <summary>
            <span data-ttu-id="92a67-105">Wird aufgerufen, Prozessor-Host, um anzugeben, dass der Ereignisprozessor beendet wird.</span><span class="sxs-lookup"><span data-stu-id="92a67-105">Called by processor host to indicate that the event processor is being stopped.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.OpenAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (context As PartitionContext) As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.OpenAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="92a67-106">Informationen über die Partition, der diese Ereignisprozessor Ereignisse verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="92a67-106">Information about the partition that this event processor will process events from.</span></span></param>
        <summary>
            <span data-ttu-id="92a67-107">Wird vom Prozessor Host zum Initialisieren der Ereignisprozessor aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="92a67-107">Called by processor host to initialize the event processor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessErrorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessErrorAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, Exception error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessErrorAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, class System.Exception error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.ProcessErrorAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessErrorAsync (context As PartitionContext, error As Exception) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessErrorAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * Exception -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessErrorAsync (context, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="error" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="92a67-108">Informationen zur Partition.</span><span class="sxs-lookup"><span data-stu-id="92a67-108">Information about the partition.</span></span></param>
        <param name="error"><span data-ttu-id="92a67-109">Der Fehler, der aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="92a67-109">The error that occured.</span></span></param>
        <summary>
            <span data-ttu-id="92a67-110">Wird aufgerufen, wenn der zugrunde liegenden Client ein Fehlers beim empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="92a67-110">Called when the underlying client experiences an error while receiving.</span></span> <span data-ttu-id="92a67-111">EventProcessorHost übernimmt des Fehlers wiederherstellen und Datapump Nachrichten fortgesetzt werden, damit keine Aktion aus dem Code erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="92a67-111">EventProcessorHost will take care of recovering from the error and continuing to pump messages, so no action is required from your code.</span></span> <span data-ttu-id="92a67-112">Diese Methode wird zu Informationszwecken bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="92a67-112">This method is provided for informational purposes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.ProcessEventsAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (context As PartitionContext, messages As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessEventsAsync (context, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="92a67-113">Informationen zur Partition.</span><span class="sxs-lookup"><span data-stu-id="92a67-113">Information about the partition.</span></span></param>
        <param name="messages"><span data-ttu-id="92a67-114">Die Ereignisse verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="92a67-114">The events to be processed.</span></span></param>
        <summary>
            <span data-ttu-id="92a67-115">Wird vom Prozessor Host ein, wenn ein Batch von Ereignissen angekommen ist.</span><span class="sxs-lookup"><span data-stu-id="92a67-115">Called by the processor host when a batch of events has arrived.</span></span>
            <span data-ttu-id="92a67-116"><para>Dies ist, in denen die eigentliche Arbeit der Ereignisprozessor erfolgt.</para></span><span class="sxs-lookup"><span data-stu-id="92a67-116"><para>This is where the real work of the event processor is done.</para></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>