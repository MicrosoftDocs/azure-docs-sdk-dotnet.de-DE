<Type Name="IReliableDictionary2&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary2&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;, Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary2`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary2(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue)), IReliableDictionary(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt;&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey">
      <Constraints>
        <InterfaceName>System.IComparable&lt;TKey&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;TKey&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey">Der Typ der Schlüssel im Wörterbuch zuverlässige.</typeparam>
    <typeparam name="TValue">
            Der Typ der Werte in der zuverlässigen Wörterbuch.</typeparam>
    <summary>
            Stellt eine zuverlässige Auflistung von Schlüssel/Wert-Paaren, die persistent gespeichert und repliziert werden.
            </summary>
    <remarks>Schlüssel oder Werte, die in dieses Wörterbuch aufweist und müssen nicht gespeichert werden außerhalb des Kontexts eines Vorgangs auf das Wörterbuch geändert.  Es wird dringend empfohlen, beide <typeparamref name="TKey" /> und <typeparamref name="TValue" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.
            
            <para>Die Transaktion ist die Einheit der Parallelität. Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an. Wenn eine asynchrone zuverlässige Auflistung-Methode aufrufen, übernimmt ein <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, Sie müssen warten, auf den Abschluss der zurückgegebenen Aufgabe vor dem Aufrufen einer anderen Methode, die mit der gleichen Transaktion.</para></remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.Count" />
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
            Ruft die Anzahl der Schlüssel-Wert-Paare der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft hat keine Transaktionssemantik. Es stellt die beste Aufwand Anzahl der Elemente im Wörterbuch dar, zum Zeitpunkt, wenn die Eigenschaft zugegriffen wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateKeyEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of TKey))" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <summary>
            Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.
            </summary>
        <returns>Ein aufzählbares Element für die zuverlässige Wörterbuchschlüssel.</returns>
        <remarks>
            Die Enumerarable zurückgegeben, aus dem Wörterbuch zuverlässige sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das Wörterbuch. Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.
            <see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="enumerationMode">Die zu verwendende enumerationsmodus. Die Standardeinstellung ist nicht sortiert.</param>
        <summary>
            Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.
            </summary>
        <returns>Ein aufzählbares Element für die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> Schlüssel.</returns>
        <remarks>
            Die Enumerarable zurückgegeben, die von der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> sicher gleichzeitig mit der Lesevorgänge verwendet wird, und schreibt in das Wörterbuch. Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.
            <see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="txn">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="enumerationMode">Die zu verwendende enumerationsmodus. Die Standardeinstellung ist nicht sortiert.</param>
        <param name="timeout">
            Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.
            </summary>
        <returns>Ein aufzählbares Element für die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> Schlüssel.</returns>
        <remarks>
            Die Enumerarable zurückgegeben, die von der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> sicher gleichzeitig mit der Lesevorgänge verwendet wird, und schreibt in das Wörterbuch. Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.
            <see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
  </Members>
</Type>