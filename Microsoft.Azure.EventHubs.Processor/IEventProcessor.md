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
            Schnittstelle, die vom Prozessor Ereignisklassen implementiert werden muss.
            
            <para>Keine Instanz einer Ereignisklasse-Prozessor verarbeitet nur Ereignisse aus einer Partition einen Event Hub. Eine PartitionContext wird mit jedem Aufruf der Ereignisprozessor bereitgestellt, da einige Parameter geändert werden konnte, aber es wird immer die gleiche Partition sein. </para> <para>Zwar EventProcessorHost ist Multithread, Aufrufe an eine bestimmte Instanz einer Prozessor Ereignisklasse werden mit Ausnahme von OnError() serialisiert. OnOpen() zuerst aufgerufen wird, und dann OnEvents() wird nicht oder mehrmals aufgerufen werden. Wenn der muss der Ereignisprozessor heruntergefahren werden, ob Fehler an einer Stelle, oder die Lease für die Partition verloren gegangen oder weil der gesamte Prozessor Host heruntergefahren wird, OnClose() aufgerufen wird, nachdem der letzte OnEvents()-Aufruf zurückgegeben. </para> <para>OnError() konnte beim OnEvents() aufgerufen werden oder OnClose() ausgeführt wird. Keine Synchronisierung wird ausgeführt, um zu vermeiden, möglicherweise Deadlocks.</para></summary>
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
        <param name="context">Informationen zur Partition.</param>
        <param name="reason">Der Grund, warum der Ereignisprozessor beendet wird.</param>
        <summary>
            Wird aufgerufen, Prozessor-Host, um anzugeben, dass der Ereignisprozessor beendet wird.
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
        <param name="context">Informationen über die Partition, der diese Ereignisprozessor Ereignisse verarbeitet.</param>
        <summary>
            Wird vom Prozessor Host zum Initialisieren der Ereignisprozessor aufgerufen.
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
        <param name="context">Informationen zur Partition.</param>
        <param name="error">Der Fehler, der aufgetreten sind.</param>
        <summary>
            Wird aufgerufen, wenn der zugrunde liegenden Client ein Fehlers beim empfangen hat. EventProcessorHost übernimmt des Fehlers wiederherstellen und Datapump Nachrichten fortgesetzt werden, damit keine Aktion aus dem Code erforderlich ist. Diese Methode wird zu Informationszwecken bereitgestellt.
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
        <param name="context">Informationen zur Partition.</param>
        <param name="messages">Die Ereignisse verarbeitet werden.</param>
        <summary>
            Wird vom Prozessor Host ein, wenn ein Batch von Ereignissen angekommen ist.
            <para>Dies ist, in denen die eigentliche Arbeit der Ereignisprozessor erfolgt.</para></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>