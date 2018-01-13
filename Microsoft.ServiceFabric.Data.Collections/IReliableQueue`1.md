<Type Name="IReliableQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;!T&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableQueue(Of T)&#xA;Implements IReliableCollection(Of T)" />
  <TypeSignature Language="F#" Value="type IReliableQueue&lt;'T&gt; = interface&#xA;    interface IReliableCollection&lt;'T&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">Der Typ der Elemente in der zuverlässige Warteschlange.</typeparam>
    <summary>
            Stellt eine zuverlässige First-in-First-Out Auflistung von Objekten, die persistent gespeichert und repliziert werden.
            </summary>
    <remarks>
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
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!T&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (tx As ITransaction) As Task(Of IAsyncEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'T&gt;&gt;" Usage="iReliableQueue.CreateEnumerableAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <summary>
            Erstellt eine asynchrone aufzählbare über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />.
            </summary>
        <returns>IEnumerable, das alle Werte darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.
            <cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnqueueAsync (tx As ITransaction, item As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item)" />
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
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="item">Das Objekt, das das Ende der Warteschlange hinzugefügt werden soll. Der Wert kann für Verweistypen NULL sein.</param>
        <summary>
            Fügt ein Objekt am Ende der zuverlässige Warteschlange an.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</returns>
        <remarks>Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item, timeout, cancellationToken)" />
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
        <Parameter Name="item" Type="T" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="item">Das Objekt, das das Ende der Warteschlange hinzugefügt werden soll. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Fügt ein Objekt am Ende der zuverlässige Warteschlange an.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</returns>
        <remarks>Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryDequeueAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync tx" />
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
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <summary>
            Versucht, entfernen und das Objekt am Anfang der Warteschlange für zuverlässige zurückgeben.
            </summary>
        <returns>
            Aufgabe, die den asynchronen darstellt dequeue-Vorgang. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt entfernt wurde, und wenn dies der Fall ist, das Objekt.
            </returns>
        <remarks>Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync (tx, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, entfernen und das Objekt am Anfang der Warteschlange für zuverlässige zurückgeben.
            </summary>
        <returns>
            Aufgabe, die den asynchronen darstellt dequeue-Vorgang. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt entfernt wurde, und wenn dies der Fall ist, das Objekt.
            </returns>
        <remarks>Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryPeekAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync tx" />
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
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <summary>
            Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.
            <cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode)" />
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
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <summary>
            Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.
            <cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.
            <cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode, timeout, cancellationToken)" />
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
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.
            <cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>