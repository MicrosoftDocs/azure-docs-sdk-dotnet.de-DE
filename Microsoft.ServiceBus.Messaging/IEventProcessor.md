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
    <summary>Stellt Methoden zum Ereignis Prozessoren bereit. Anwendungen müssen diese Schnittstelle die Behandlung von Ereignissen von Event Hubs ermöglicht implementieren. Diese Schnittstelle ist der wesentliche Erweiterbarkeitspunkt für die EventProcessorHost und <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</summary>
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
        <param name="context">Partition-Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert. Sie können Aufrufen <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> um Prüfpunkt Fortschritte bei der Verarbeitung von Nachrichten vom Event Hub-Streams.</param>
        <param name="reason">Der Grund für den Aufruf von <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />.</param>
        <summary>Wird aufgerufen, wenn der Besitz der Partition auf einen anderen Knoten verschoben wird, für den Lastenausgleich Zweck, oder wenn der Host wird heruntergefahren. Wird aufgerufen, als Antwort auf <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</summary>
        <returns> Ein Task, der angibt, dass der schließen-Vorgang abgeschlossen ist.</returns>
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
        <param name="context">Die Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert. Jeder Versuch, rufen Sie <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" /> während der geöffnete Vorgang fehl.</param>
        <summary>Initialisiert die Event Hub-Prozessor-Instanz. Diese Methode wird aufgerufen, bevor alle Ereignisdaten an diese Prozessorinstanz übergeben werden.</summary>
        <returns>Der Task, der angibt, dass der Öffnungsvorgang abgeschlossen ist.</returns>
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
        <param name="context">Die Besitzinformationen für die Partition auf der diese Prozessorinstanz funktioniert.</param>
        <param name="messages">Ein Batch von Event Hubs-Ereignissen.</param>
        <summary>Verarbeitet asynchron den angegebenen Kontext und Nachrichten. Diese Methode wird aufgerufen, wenn neue Nachrichten im Event Hubs Datenstrom vorhanden sind. Stellen Sie sicher, Prüfpunkt nur, wenn Sie alle Ereignisse in jedem Batch verarbeitet haben.</summary>
        <returns>Der Task, der angibt, <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" /> ist abgeschlossen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>