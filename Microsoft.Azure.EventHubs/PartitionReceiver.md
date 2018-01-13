<Type Name="PartitionReceiver" FullName="Microsoft.Azure.EventHubs.PartitionReceiver">
  <TypeSignature Language="C#" Value="public abstract class PartitionReceiver : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PartitionReceiver extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PartitionReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type PartitionReceiver = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist eine logische Darstellung des Empfangs aus einen Event Hub-Partition.
            <para>Eine PartitionReceiver ist an eine ConsumerGroup gebunden + Partitions-Kombination. Wenn Sie eine Epoche erstellen PartitionReceiver basierend (d. h. PartitionReceiver.Epoch! = 0) nicht zulässig, dass mehrere aktive Empfänger pro ConsumerGroup + Partition Kombinationsfeld. Sie können mehrere Empfänger pro ConsumerGroup + zusammen mit dem Empfänger nicht Epoche partitionieren.</para></summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,Microsoft.Azure.EventHubs.ReceiverOptions)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal PartitionReceiver (Microsoft.Azure.EventHubs.EventHubClient eventHubClient, string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Nullable&lt;DateTime&gt; startTime, Nullable&lt;long&gt; epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.EventHubs.EventHubClient eventHubClient, string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int64&gt; epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.#ctor(Microsoft.Azure.EventHubs.EventHubClient,System.String,System.String,System.String,System.Boolean,System.Nullable{System.DateTime},System.Nullable{System.Int64},Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.PartitionReceiver : Microsoft.Azure.EventHubs.EventHubClient * string * string * string * bool * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="new Microsoft.Azure.EventHubs.PartitionReceiver (eventHubClient, consumerGroupName, partitionId, startOffset, offsetInclusive, startTime, epoch, receiverOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubClient" Type="Microsoft.Azure.EventHubs.EventHubClient" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="epoch" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="eventHubClient"></param>
        <param name="consumerGroupName"></param>
        <param name="partitionId"></param>
        <param name="startOffset"></param>
        <param name="offsetInclusive"></param>
        <param name="startTime"></param>
        <param name="epoch"></param>
        <param name="receiverOptions"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override sealed System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionReceiver.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt und zugeordnete Ressourcen frei <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.
            </summary>
        <returns>Ein asynchroner Vorgang</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name der Consumergruppe
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultConsumerGroupName">
      <MemberSignature Language="C#" Value="public static readonly string DefaultConsumerGroupName;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string DefaultConsumerGroupName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.DefaultConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultConsumerGroupName As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.DefaultConsumerGroupName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Standardwert der Name der consumergruppe: $Default.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOfStream">
      <MemberSignature Language="C#" Value="public static readonly string EndOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string EndOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.EndOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EndOfStream As String " />
      <MemberSignature Language="F#" Value=" staticval mutable EndOfStream : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.EndOfStream" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Konstante, die das Ende eines Streams kennzeichnet. Dies kann als Argument Offset im Erstellen von remoteereignisempfängern zum Starten empfangen aus dem letzten Ereignis, anstelle von einem bestimmten Zeitpunkt im Zeit-Offset-Wert verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Epoche-Wert, den dieser Empfänger derzeit für den Besitz der Partition verwendet wird.
            <para>Ein Wert von Null bedeutet, dass dies Empfänger ist nicht mit einer Epoche basierende Empfänger.</para></summary>
        <value>der Wert der Epoche, den dieser Empfänger derzeit für den Besitz der Partition verwendet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubClient EventHubClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventHubClient EventHubClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.EventHubClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubClient As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.EventHubClient : Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.EventHubClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die EventHubClient dieser PartitionReceiver aus erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="protected bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnCloseAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnCloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionReceiver.OnCloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnReceiveAsync (maxMessageCount As Integer, waitTime As TimeSpan) As Task(Of IList(Of EventData))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.OnReceiveAsync (maxMessageCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="waitTime"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetReceiveHandler">
      <MemberSignature Language="C#" Value="protected abstract void OnSetReceiveHandler (Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetReceiveHandler(class Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnSetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnSetReceiveHandler (receiveHandler As IPartitionReceiveHandler)" />
      <MemberSignature Language="F#" Value="abstract member OnSetReceiveHandler : Microsoft.Azure.EventHubs.IPartitionReceiveHandler -&gt; unit" Usage="partitionReceiver.OnSetReceiveHandler receiveHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveHandler" Type="Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
      </Parameters>
      <Docs>
        <param name="receiveHandler"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Rufen Sie die EventHub-Partition-ID an.
            </summary>
        <value>Der Bezeichner, die die Partition aus der dieser Empfänger Daten abruft darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen von Vorabrufwert beim Empfänger konfiguriert.
            </summary>
        <value>die Obergrenze von Ereignissen wird dieser Empfänger aktiv empfängt, unabhängig davon, ob ein Receive-Vorgang aussteht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">To be added.</param>
        <summary>
            Empfangen ein Batches von <see cref="T:Microsoft.Azure.EventHubs.EventData" />des aus einem EventHub partitionieren
            </summary>
        <returns>Eine Aufgabe, die einen Batch von gedachten <see cref="T:Microsoft.Azure.EventHubs.EventData" /> aus der Partition, für die dieser Empfänger erstellt wird. Gibt "null", wenn keine EventData vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <example>
            Beispielcode:
            <code>
            EventHubClient client = EventHubClient.Create("__connectionString__");
            PartitionReceiver receiver = client.CreateReceiver("ConsumerGroup1", "1");
            IEnumerable&lt;EventData&gt; receivedEvents = await receiver.ReceiveAsync(BatchSize);
                 
            while (true)
            {
                int batchSize = 0;
                if (receivedEvents != null)
                {
                    foreach (EventData receivedEvent in receivedEvents)
                    {
                        Console.WriteLine("Message Payload: {0}", Encoding.UTF8.GetString(receivedEvent.Body));
                        Console.WriteLine("Offset: {0}, SeqNo: {1}, EnqueueTime: {2}", 
                            receivedEvent.SystemProperties.Offset, 
                            receivedEvent.SystemProperties.SequenceNumber, 
                            receivedEvent.SystemProperties.EnqueuedTime);
                        batchSize++;
                    }
                }
                     
                Console.WriteLine("ReceivedBatch Size: {0}", batchSize);
                receivedEvents = await receiver.ReceiveAsync();
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.ReceiveAsync (maxMessageCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionReceiver/&lt;ReceiveAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">To be added.</param>
        <param name="waitTime">To be added.</param>
        <summary>
            Empfangen ein Batches von <see cref="T:Microsoft.Azure.EventHubs.EventData" />aufrufen, die aus einer Partition EventHub Wartezeit für jedes einzelne können.
            </summary>
        <returns>Eine Aufgabe, die einen Batch von gedachten <see cref="T:Microsoft.Azure.EventHubs.EventData" /> aus der Partition, für die dieser Empfänger erstellt wird. Gibt "null", wenn keine EventData vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> Ruft einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInformation" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.ReceiverRuntimeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ungefähre Empfänger Laufzeitinformationen für eine logische Partition einen Event Hub ab.
            Um die Einstellung zu aktivieren, finden Sie unter <see cref="T:Microsoft.Azure.EventHubs.ReceiverOptions" /> und<see cref="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetReceiveHandler">
      <MemberSignature Language="C#" Value="public void SetReceiveHandler (Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetReceiveHandler(class Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetReceiveHandler (receiveHandler As IPartitionReceiveHandler)" />
      <MemberSignature Language="F#" Value="member this.SetReceiveHandler : Microsoft.Azure.EventHubs.IPartitionReceiveHandler -&gt; unit" Usage="partitionReceiver.SetReceiveHandler receiveHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveHandler" Type="Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
      </Parameters>
      <Docs>
        <param name="receiveHandler">Die <see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" /> verwendet, um Ereignisse zu verarbeiten.</param>
        <summary>
            Legt die <see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" /> zum Verarbeiten von Ereignissen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="protected string StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property StartOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartOffset : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOfStream">
      <MemberSignature Language="C#" Value="public static readonly string StartOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string StartOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly StartOfStream As String " />
      <MemberSignature Language="F#" Value=" staticval mutable StartOfStream : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dies ist eine Konstante, die definiert, um den Beginn eines Datenstroms Partition im Event Hub darstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="protected Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.StartTime" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>