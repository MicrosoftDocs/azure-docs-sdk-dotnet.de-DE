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
             Die MessageReceiver kann zum Empfangen von Nachrichten aus Warteschlangen und Abonnements, und bestätigen sie verwendet werden.
             </summary>
    <remarks>
             Die MessageReceiver bietet erweiterte Funktionalität, die nicht in der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> oder <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />. Z. B. <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, dem können Sie zum Empfangen von Nachrichten bei Bedarf, erfordert jedoch auch manuell mithilfe von Sperren erneuern <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
    <example>
             Erstellen Sie eine neue MessageReceiver zum Empfangen einer Nachricht aus einem Abonnement
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             Eine Meldung aus dem Abonnement.
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
        <param name="lockTokens">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> mit den Token sperren die entsprechenden Nachrichten abgeschlossen.</param>
        <summary>
            Schließt eine Reihe von <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einer Liste von Token der Sperre. Hierdurch wird die Nachricht vom Dienst gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
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
        <param name="lockToken">Das Sperrtoken des der <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, während die Nachricht verzögern.</param>
        <summary>Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um diese Meldung erneut in der Zukunft Sie benötigen zum Speichern der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> und empfangen mit <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.
            Verzögern von Nachrichten wirkt sich nicht der Nachricht Ablauf, was bedeutet, dass die verzögerte Nachrichten weiterhin ablaufen können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
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
        <summary>Ruft die Sequenznummer der letzten eingesehenen Nachricht ab.</summary>
        <value>Die Sequenznummer der letzten eingesehenen Nachricht.</value>
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
            Ruft die nächste active Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung ab.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt. Gibt null zurück, wenn nichts einsehen.</returns>
        <remarks>
            Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger. Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.
            Im Gegensatz zu einer empfangenen Nachrichten eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.
            Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)
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
        <param name="maxMessageCount">Die Anzahl der Meldungen.</param>
        <summary>
            Ruft den nächsten Batch aktiver Nachrichten ohne Ändern des Zustands der Empfänger oder die Quelle der Meldung ab.
            </summary>
        <returns>Liste der <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt. Gibt null zurück, wenn nichts einsehen.</returns>
        <remarks>
            Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger. Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.
            Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.
            Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)
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
        <param name="fromSequenceNumber">Die Sequenznummer ab dem die Nachricht zu lesen.</param>
        <summary>
            Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.
            </summary>
        <returns>Den asynchronen Vorgang, die gibt die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</returns>
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
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</param>
        <param name="messageCount">Die Anzahl der Meldungen.</param>
        <summary>Liest einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch eingesehen werden.</returns>
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
            Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.
            </summary>
        <returns>Die empfangene Nachricht. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Timeout nach der Dauer des Vorgangs<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></remarks>
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
        <param name="maxMessageCount">Die maximale Anzahl von Nachrichten, die empfangen werden.</param>
        <summary>
            Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.
            </summary>
        <returns>Liste der Nachrichten empfangen. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</remarks>
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
        <param name="operationTimeout">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>
            Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.
            </summary>
        <returns>Die empfangene Nachricht. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>
            Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss). Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.
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
        <param name="maxMessageCount">Die maximale Anzahl von Nachrichten, die empfangen werden.</param>
        <param name="operationTimeout">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>
            Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> mit <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> Modus.
            </summary>
        <returns>Liste der Nachrichten empfangen. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.
            Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss). Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.
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
        <param name="sequenceNumbers">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , enthält die Sequenznummern empfangen.</param>
        <summary>
            Empfängt eine <see cref="T:System.Collections.Generic.IList`1" /> verzögerte Nachrichten identifizierten <paramref name="sequenceNumbers" />.
            </summary>
        <returns>Nachrichten, die Sequenznummer identifizierte werden zurückgegeben. Gibt null zurück, wenn keine Nachrichten gefunden werden.
            Löst aus, wenn die Nachrichten, nicht verzögert wurde.</returns>
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
        <param name="sequenceNumber">Die Sequenznummer der Nachricht, die empfangen werden.</param>
        <summary>
            Empfängt eine bestimmte verzögerte Nachricht erkennbar <paramref name="sequenceNumber" />.
            </summary>
        <returns>Nachricht erkennbar Sequenznummer <paramref name="sequenceNumber" />. Gibt null zurück, wenn keine solche Nachricht gefunden wird.
            Löst aus, wenn die Nachricht nicht verzögert wurde.</returns>
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
            Erneuert die Sperre für die Nachricht an. Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).
            Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.
            Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.
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
        <param name="lockToken">Der Nachricht zugeordnete Sperrtoken.</param>
        <summary>
            Erneuert die Sperre für die Nachricht an. Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.
            <returns>Neue Sperre token Ablaufdatum und die Uhrzeit in UTC-Format.</returns></summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).
            Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.
            Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>