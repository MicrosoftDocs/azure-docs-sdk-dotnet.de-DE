<Type Name="IReliableConcurrentQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableConcurrentQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableConcurrentQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableConcurrentQueue(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableConcurrentQueue&lt;'T&gt; = interface&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">
            Der Typ der Werte in der slim zuverlässige Warteschlange enthalten sind.
            </typeparam>
    <summary>
      <para>
            Stellt eine zuverlässige Auflistung erhalten bleibt, replizierten Werte mit Best-Effort-FIFO-Reihenfolge zu sortieren.
            </para>
    </summary>
    <remarks>
      <para>
            Als Alternative zur vorgesehen <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> für arbeitsauslastungen, in denen strenge Sortierung nicht erforderlich ist, als durch lockern die Reihenfolge Einschränkung Parallelität kann erheblich verbessert werden.  <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />gleichzeitige Consumer und Producer beschränkt, auf ein Maximum von einem einzelnen, während <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> erzwingt diese Einschränkung nicht.
            </para>
      <para>
        <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />bietet die gleiche Transaktion Isolationssemantik als die zuverlässige Datenstrukturen nicht.  Finden Sie die einzelnen Vorgänge und die Eigenschaften (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> und <see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) für Details dazu, welche Isolation, sofern vorhanden, sie bieten.
            </para>
      <para>
            Es wird erwartet, dass Werte in der Warteschlange relativ kurzlebig sind; Anders gesagt, ausgehenden (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) zu rechnen ist gleich oder größer als die eingehend (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) Rate.  Diese Vorgabe verletzen kann die Systemleistung verschlechtern.  Eine Einschränkung der geplanten Warteschlange-Kapazität, die eingehende reiht Drosselung wird, sobald die Kapazität erreicht ist, hilft dabei, die diese Eigenschaft.
            -Eigenschaft veranschaulicht.
            </para>
      <para>
            Wie die Reihenfolge der Elemente nicht unbedingt gewährleistet ist, Annahmen über die Reihenfolge der zwei beliebige Werte in der Warteschlange darf nicht hergestellt werden.  Die Reihenfolge der Best-Effort-FIFO-Reihenfolge ist für Ausgewogenheit bereitgestellt wird. die Zeit, die ein Wert in der Warteschlange verbringt sollte verknüpft sein, um die Fehlerrate (Fehler können der Warteschlange Sortierung alter) und den Dequeue-Rate, aber nicht die Rate der in die Warteschlange einzureihen.
            </para>
      <para>
        <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />bieten einen Lesevorgang, nicht jedoch durch Kombinieren von <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> und <see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" /> identisch semantische erreicht werden kann.  Finden Sie unter <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Weitere Informationen und ein Beispiel.
            </para>
      <para>
            In dieser Warteschlange darf keinen gespeicherte Werten werden geändert, außerhalb des Kontexts eines Vorgangs in der Warteschlange. Es wird dringend empfohlen, stellen <typeparamref name="T" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.
            </para>
      <para>
            Transaktion ist die Einheit der Parallelität: Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden jeweils einzeln.
            Daher sind alle zuverlässige Auflistung-APIs, die in einer Transaktion annehmen und eine Aufgabe zurückgeben muss erwartete einzeln nacheinander.
            <seealso cref="T:Microsoft.ServiceFabric.Data.ITransaction" /></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
             Ruft die Anzahl der Werte in der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.
             </para>
        </summary>
        <value>Die Anzahl der Werte in der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</value>
        <remarks>
          <para>
             Diese Zahl stellt die Anzahl der Werte, die derzeit für sichtbar <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />.  UNCOMMITTED reiht wird nicht die Anzahl erhöhen, jedoch ohne Commit Dequeues die Anzahl verringert.
             </para>
          <para>
             Beachten Sie, dass diese API nicht mit einem Transaktionsparameter übernimmt.  Seit der Auswirkungen der <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> werden nicht von anderen Transaktionen isoliert, die die Anzahl auch darf nicht von anderen Transaktionen isoliert.  
             </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">Das Replikat ist derzeit nicht lesbar.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</exception>
        <example>
             Dieses Beispiel zeigt die Anzahl der Warteschlangen überwachen unbegrenzt, bis das Abbruchtoken abgebrochen wird.
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                 // Assumption: values are being enqueued/dequeued in another place (e.g. the communication listener).
                 var observer = Task.Run(
                     async () =>
                         {
                             while (true)
                             {
                                 cancellationToken.ThrowIfCancellationRequested();
            
                                 try
                                 {
                                     Console.WriteLine("Count: " + concurrentQueue.Count);
                                 }
                                 catch (FabricNotReadableException e)
                                 {
                                     // Retry until the queue is readable or a different exception is thrown.
                                     Console.WriteLine("Queue is not readable, retrying the observation: " + e);
                                 }
                                 catch (FabricObjectClosedException e)
                                 {
                                     // Gracefully exit as this is happening due to replica close.
                                     Console.WriteLine("Replica is closing, stopping observer: " + e);
                                     return;
                                 }
                                 
                                 await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                             }
                         },
                     cancellationToken);
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T value, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T value, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task" Usage="iReliableConcurrentQueue.EnqueueAsync (tx, value, cancellationToken, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="value">Der Wert am Ende der Warteschlange hinzu. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert lautet <see cref="P:System.Threading.CancellationToken.None" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. Der Standardwert ist NULL.  Wenn Null übergeben wird, wird ein Standardtimeout verwendet werden.</param>
        <summary>
          <para>
             Phase der eines Werts in die Warteschlange einreihen.
             </para>
        </summary>
        <returns>Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</returns>
        <remarks>
             Ein <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgang kann keiner Wert zurück, für die die <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> noch kein Commit ausgeführt wurde.
             Dies schließt die Transaktion, in der der Wert in die Warteschlange eingereiht wurde; Daher <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> Your-Lese-nicht unterstützt.
             </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Das Replikat ist nicht mehr in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">Das Replikat ist derzeit nicht lesbar.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</exception>
        <exception cref="T:System.Fabric.FabricTransientException">Das Replikat gesehen haben, um einen vorübergehenden Fehler. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.Fabric.FabricException">Das Replikat wurde einen anderer oben definierten Typen nicht wiederholbar Fehler erläutert. Die Bereinigung und Rethrow-Ausnahme</exception>
        <exception cref="T:System.TimeoutException">
             Der Vorgang konnte nicht innerhalb des angegebenen Zeitlimits abgeschlossen werden.  Die Transaktion abgebrochen werden soll, und eine neue Transaktion erstellt werden soll, um erneut zu versuchen.
             </exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen, über <paramref name="cancellationToken" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
             Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
             Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
             Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
             </exception>
        <example>
             Dieses Beispiel zeigt, wie <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> in die Warteschlange einzureihende Wert mit Wiederholung.
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                 while (true)
                 {
                     cancellationToken.ThrowIfCancellationRequested();
             
                     try
                     {
                         using (var tx = this.StateManager.CreateTransaction())
                         {
                             await concurrentQueue.EnqueueAsync(tx, 12L, cancellationToken);
                             await tx.CommitAsync();
            
                             return;
                         }
                     }
                     catch (TransactionFaultedException e)
                     {
                         // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
                         // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
                         Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
                     }
                     catch (FabricNotPrimaryException e)
                     {
                         // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
                         // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                         return;
                     }
                     catch (FabricNotReadableException e)
                     {
                         // Retry until the queue is readable or a different exception is thrown.
                         Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                     }
                     catch (FabricObjectClosedException e)
                     {
                         // Gracefully exit RunAsync as this is happening due to replica close.
                         // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                         return;
                     }
                     catch (TimeoutException e)
                     {
                         Console.WriteLine("Encountered TimeoutException during EnqueueAsync, retrying the transaction: " + e);
                     }
                     catch (FabricTransientException e)
                     {
                         // Retry until the queue is writable or a different exception is thrown.
                         Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                     }
            
                     // Delay and retry.
                     await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                 }
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableConcurrentQueue.TryDequeueAsync (tx, cancellationToken, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert lautet <see cref="P:System.Threading.CancellationToken.None" />.</param>
        <param name="timeout">Die Zeitspanne zum Abschließen des Vorgangs warten. Der Standardwert ist NULL.  Wenn Null übergeben wird, wird ein Standardtimeout verwendet werden.</param>
        <summary>
          <para>
            Mit Vorbehalt dequeue einen Wert aus der Warteschlange. Wenn die Warteschlange leer ist, wartet der Dequeue-Vorgang für ein Element zur Verfügung.
            </para>
        </summary>
        <returns>
            Eine Aufgabe, die den asynchronen stellt dequeue-Vorgang. Das Ergebnis ist eine ConditionalValue vom Typ t Wenn Sie ein Wert innerhalb der angegebenen Zeit aus der Warteschlange entfernt wurde, Zurückgeben einer ConditionalValue mit HasValue als "false", ansonsten Längenwert ein ConditionalValue bei HasValue als "true" und Wert wie das Element aus der Warteschlange entfernt, der Typ T
            </returns>
        <remarks>
          <para>
            Während <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> nur Werte zurückgeben, für die entsprechenden <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> wurde ein Commit ausgeführt wurde, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgänge sind nicht voneinander isoliert.  Sobald eine Transaktion einen Wert aus der Warteschlange entfernt wurde, werden andere Transaktionen können nicht aus der Warteschlange entfernt, jedoch nicht aus anderen Werten daraus entfernt wird.
            </para>
          <para>
            Wenn eine Transaktion oder Transaktionen, die eine oder mehrere einschließlich <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgänge wird abgebrochen, die Werte aus der Warteschlange entfernt werden wieder am Anfang der Warteschlange in einer beliebigen Reihenfolge hinzugefügt werden.  Dadurch wird sichergestellt, dass diese Werte bald wieder vorbei, aus der Warteschlange werden die Fairness der Datenstruktur, jedoch entfernt werden ohne strenge Sortierung Durchsetzung verbessern (was erfordern würde, reduzieren die zulässige Parallelität als in <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />).
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Das Replikat ist nicht mehr in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">Das Replikat ist derzeit nicht lesbar.</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</exception>
        <exception cref="T:System.Fabric.FabricTransientException">Das Replikat gesehen haben, um einen vorübergehenden Fehler. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.Fabric.FabricException">Das Replikat wurde einen anderer oben definierten Typen nicht wiederholbar Fehler erläutert. Die Bereinigung und Rethrow-Ausnahme</exception>
        <exception cref="T:System.TimeoutException">
            Der Vorgang konnte nicht innerhalb des angegebenen Zeitlimits abgeschlossen werden.  Die Transaktion abgebrochen werden soll, und eine neue Transaktion erstellt werden soll, um erneut zu versuchen.
            </exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL. Diese Ausnahme nicht behandelt.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen, über <paramref name="cancellationToken" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <example>
            Dieses Beispiel zeigt, wie Sie aus der Warteschlange entfernen und melden Sie sich unbegrenzt wiederholen, bis das Abbruchtoken abgebrochen wird.  
            <code><![CDATA[
            protected override async Task RunAsync(CancellationToken cancellationToken)
            {
                var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                // Assumption: values are being enqueued by another source (e.g. the communication listener).
                while (true)
                {
                    cancellationToken.ThrowIfCancellationRequested();
            
                    try
                    {
                        using (var tx = this.StateManager.CreateTransaction())
                        {
                            var dequeueOutput = await concurrentQueue.TryDequeueAsync(tx, cancellationToken, TimeSpan.FromMilliseconds(100));
                            await tx.CommitAsync();
            
                            if (dequeueOutput.HasValue)
                            {
                                Console.WriteLine("Dequeue # " + dequeueOutput);
                            }
                            else
                            {
                                Console.WriteLine("Could not dequeue in the given time");
                            }
                        }
                    }
                    catch (TransactionFaultedException e)
                    {
                        // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
                        // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
                        Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
                    }
                    catch (FabricNotPrimaryException e)
                    {
                        // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
                        Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                        return;
                    }
                    catch (FabricNotReadableException e)
                    {
                        // Retry until the queue is readable or a different exception is thrown.
                        Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                    }
                    catch (FabricObjectClosedException e)
                    {
                        // Gracefully exit RunAsync as this is happening due to replica close.
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
                        Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                        return;
                    }
                    catch (TimeoutException e)
                    {
                        Console.WriteLine("Encountered TimeoutException during DequeueAsync, retrying the transaction: " + e);
                    }
                    catch (FabricTransientException e)
                    {
                        // Retry until the queue is writable or a different exception is thrown.
                        Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                    }
            
                    // Delay and retry.
                    await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                }
            }
            ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>