<Type Name="IReliableDictionary&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue))" />
  <TypeSignature Language="F#" Value="type IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
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
  </Interfaces>
  <Docs>
    <typeparam name="TKey">Der Typ der Schlüssel im Wörterbuch zuverlässige.</typeparam>
    <typeparam name="TValue">Der Typ der Werte in der zuverlässigen Wörterbuch.</typeparam>
    <summary>
      <para>Stellt eine zuverlässige Auflistung von Schlüssel/Wert-Paaren, die persistent gespeichert und repliziert werden.</para>
    </summary>
    <remarks>
      <para>Schlüssel oder Werte, die in dieses Wörterbuch aufweist und müssen nicht gespeichert werden außerhalb des Kontexts eines Vorgangs auf das Wörterbuch geändert. Es wird dringend empfohlen, beide <typeparamref name="TKey" /> und <typeparamref name="TValue" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.
            Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">hier</see> für häufige Probleme.</para>
      <para>Die Transaktion ist die Einheit der Parallelität. Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an.
            Wenn eine asynchrone zuverlässige Auflistung-Methode aufrufen, übernimmt ein <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, Sie müssen warten, auf den Abschluss der zurückgegebenen Aufgabe vor dem Aufrufen einer anderen Methode, die mit der gleichen Transaktion. Beispiele für Transaktionen <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">hier</see>.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der hinzuzufügende Schlüssel.</param>
        <param name="value">Der hinzuzufügende Wert. Der Wert kann für Verweistypen NULL sein.</param>
        <summary>
            Die zuverlässige Wörterbuch hinzugefügt das angegebene Schlüssel-Wert-Paar.
            </summary>
        <returns>Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">Das zuverlässige Wörterbuch enthält bereits ein Wert mit dem gleichen Schlüssel.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value, timeout, cancellationToken)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der hinzuzufügende Schlüssel.</param>
        <param name="value">Der hinzuzufügende Wert. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Die zuverlässige Wörterbuch hinzugefügt das angegebene Schlüssel-Wert-Paar.
            </summary>
        <returns>Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">Ein Wert mit dem gleichen Schlüssel bereits im Wörterbuch zuverlässige vorhanden ist, oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValueFactory As Func(Of TKey, TValue), updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</param>
        <param name="addValueFactory">Die Funktion zum Generieren eines Werts für einen nicht vorhandenen Schlüssel.</param>
        <param name="updateValueFactory">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</param>
        <summary>
            Verwendet die angegebene Funktionen, die zuverlässige Wörterbuch ein Schlüssel/Wert-Paar hinzugefügt werden, wenn der Schlüssel nicht bereits vorhanden ist oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige zu aktualisieren, wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt. Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel. Dies ist das Ergebnis von AddValueFactory (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="addValueFactory" /> null ist, oder <paramref name="updateValueFactory" /> ist null.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValue As TValue, updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</param>
        <param name="addValue">Der Wert für einen nicht vorhandenen Schlüssel hinzugefügt werden. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="updateValueFactory">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige aktualisiert mithilfe der angegebenen Funktion, wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt. Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel. Dies ist entweder AddValue (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="updateValueFactory" /> ist null.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</param>
        <param name="addValueFactory">Die Funktion zum Generieren eines Werts für einen nicht vorhandenen Schlüssel.</param>
        <param name="updateValueFactory">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Verwendet die angegebene Funktionen, die zuverlässige Wörterbuch ein Schlüssel/Wert-Paar hinzugefügt werden, wenn der Schlüssel nicht bereits vorhanden ist oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige zu aktualisieren, wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt. Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel. Dies ist das Ergebnis von AddValueFactory (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="addValueFactory" /> null ist, oder <paramref name="updateValueFactory" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</param>
        <param name="addValue">Der Wert für einen nicht vorhandenen Schlüssel hinzugefügt werden. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="updateValueFactory">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige aktualisiert mithilfe der angegebenen Funktion, wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt. Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel. Dies ist entweder AddValue (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="updateValueFactory" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ClearAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.ClearAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Entfernt alle Schlüssel und Werte aus dem zuverlässige Wörterbuch.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKeyAsync (tx As ITransaction, key As TKey) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</param>
        <summary>
            Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <summary>
            Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of KeyValuePair(Of TKey, TValue)))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn">Die Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <summary>
            Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.
            </summary>
        <returns>
          <para>Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt. Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</para>
        </returns>
        <remarks>
          <para>Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.
            Es stellt eine einheitliche Ansicht der Momentaufnahme dar. Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden. Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">Die Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="enumerationMode">Die zu verwendende enumerationsmodus. Die Standardeinstellung ist nicht sortiert. Geordnete Enumeration ist nur Aufsteigend. </param>
        <summary>
            Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.
            </summary>
        <returns>
          <para>Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt. Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</para>
        </returns>
        <remarks>
          <para>Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.
            Es stellt eine einheitliche Ansicht der Momentaufnahme dar. Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden. Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Func&lt;TKey,bool&gt; filter, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, class System.Func`2&lt;!TKey, bool&gt; filter, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Func{`0,System.Boolean},Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Func&lt;'Key, bool (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, filter, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="filter" Type="System.Func&lt;TKey,System.Boolean&gt;" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">Die Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="filter">Prädikat filtert, die die Schlüssel-Wert-Paare in der Enumeration, die anhand des Schlüssels eingeschlossen werden sollen.</param>
        <param name="enumerationMode">Die zu verwendende enumerationsmodus. Die Standardeinstellung ist nicht sortiert. Geordnete Enumeration ist nur Aufsteigend.</param>
        <summary>
            Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.
            </summary>
        <returns>
          <para>Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt. Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</para>
        </returns>
        <remarks>
          <para>Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.
            Es stellt eine einheitliche Ansicht der Momentaufnahme dar. Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden. Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DictionaryChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt; DictionaryChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;&gt; DictionaryChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.DictionaryChanged" />
      <MemberSignature Language="VB.NET" Value="Event DictionaryChanged As EventHandler(Of NotifyDictionaryChangedEventArgs(Of TKey, TValue)) " />
      <MemberSignature Language="F#" Value="member this.DictionaryChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " Usage="member this.DictionaryChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn die zuverlässige Wörterbuch ändert.
            Z. B. hinzufügen, aktualisieren oder Entfernen eines Elements.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, valueFactory As Func(Of TKey, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="valueFactory">Die Funktion, mit der ein Wert für den Schlüssel generiert wird.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar dem zuverlässige Wörterbuch hinzu mithilfe der angegebenen Funktion, wenn der Schlüssel nicht bereits vorhanden ist.
            </summary>
        <returns>
            Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Taskergebnis ist der Wert für den Schlüssel. Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert für den Schlüssel, wie von ValueFactory zurückgegeben, wenn der Schlüssel nicht im Wörterbuch zuverlässige war wird.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="valueFactory" /> ist null.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="value">Der hinzuzufügende Wert, wenn der Schlüssel nicht bereits vorhanden ist.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zuverlässige Wörterbuch, wenn der Schlüssel nicht bereits vorhanden ist.
            Wenn der Schlüssel vorhanden ist keine Updates auf den Wert erfolgt.
            </summary>
        <returns>
            Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Taskergebnis ist der Wert für den Schlüssel. Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert, wenn der Schlüssel nicht im Wörterbuch zuverlässige war.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="valueFactory">Die Funktion, mit der ein Wert für den Schlüssel generiert wird.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar dem zuverlässige Wörterbuch hinzu mithilfe der angegebenen Funktion, wenn der Schlüssel nicht bereits vorhanden ist.
            </summary>
        <returns>
            Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Taskergebnis ist der Wert für den Schlüssel. Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert für den Schlüssel, wie von ValueFactory zurückgegeben, wenn der Schlüssel nicht im Wörterbuch zuverlässige war wird.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="valueFactory" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="value">Der hinzuzufügende Wert, wenn der Schlüssel nicht bereits vorhanden ist.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zuverlässige Wörterbuch, wenn der Schlüssel nicht bereits vorhanden ist.
            </summary>
        <returns>
            Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Taskergebnis ist der Wert für den Schlüssel. Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert, wenn der Schlüssel nicht im Wörterbuch zuverlässige war.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="RebuildNotificationAsyncCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2&lt;!TKey, !TValue&gt;, class System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.RebuildNotificationAsyncCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property RebuildNotificationAsyncCallback As Func(Of IReliableDictionary(Of TKey, TValue), NotifyDictionaryRebuildEventArgs(Of TKey, TValue), Task)" />
      <MemberSignature Language="F#" Value="member this.RebuildNotificationAsyncCallback : Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value&gt;, Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt;, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.RebuildNotificationAsyncCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine Funktion, die aufgerufen wird, wenn die zuverlässige Wörterbuch während kopieren/wiederherstellen bzw. Wiederherstellung neu erstellt wird.
            </summary>
        <value>
            Die asynchrone Rebuild-Benachrichtigung-Funktion. Funktion nimmt IReliableDictionary und NotifyDictionaryRebuildEventArgs-Token und gibt eine Aufgabe, die asynchrone Verarbeitung der Benachrichtigung Rebuild darstellt.
            </value>
        <remarks>
          <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />kann nur innerhalb dieses Rückrufs verwendet werden.
            Sobald der asynchrone Rückruf abgeschlossen ist, die <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" /> ungültig wird. Weitere Informationen finden Sie <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">hier</see>. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, dessen Wert aktualisiert werden soll.</param>
        <param name="value">Der Wert, der den Wert des Elements ersetzt, die dem angegebenen <paramref name="key" />.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige, aktualisiert Wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="key" />ist nicht im Wörterbuch zuverlässige vorhanden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value, timeout, cancellationToken)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, dessen Wert aktualisiert werden soll.</param>
        <param name="value">Der Wert, der den Wert des Elements ersetzt, die dem angegebenen <paramref name="key" />.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige, aktualisiert Wenn der Schlüssel bereits vorhanden ist.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="key" />in der zuverlässigen Wörterbuch vorhanden ist, nicht vorhanden oder <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="value">Der Wert des hinzuzufügenden Elements. Der Wert kann für Verweistypen NULL sein.</param>
        <summary>
            Versucht, die zuverlässige Wörterbuch den angegebenen Schlüssel und Wert hinzu.
            </summary>
        <returns>Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Ergebnis der Aufgabe gibt an, ob das Schlüssel/Wert-Paar hinzugefügt wurde.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des hinzuzufügenden Elements.</param>
        <param name="value">Der Wert des hinzuzufügenden Elements. Der Wert kann für Verweistypen NULL sein.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, die zuverlässige Wörterbuch den angegebenen Schlüssel und Wert hinzu.
            </summary>
        <returns>Das Hinzufügen einer Aufgabe, die den asynchronen darstellt. Das Ergebnis der Aufgabe gibt an, ob das Schlüssel/Wert-Paar hinzugefügt wurde.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValueAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des abzurufenden Werts.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des abzurufenden Werts.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des abzurufenden Werts.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des abzurufenden Werts.</param>
        <param name="lockMode">Typ der Sperre für die Verwendung für diese Lesevorgang.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.
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
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryRemoveAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des zu entfernenden Elements.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässige zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel aus dem zuverlässige Wörterbuch entfernt wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel des zu entfernenden Elements.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässige zu entfernen.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt. Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel aus dem zuverlässige Wörterbuch entfernt wurde, und wenn dies der Fall ist, wird der Wert.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryUpdateAsync (tx As ITransaction, key As TKey, newValue As TValue, comparisonValue As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, dessen Wert mit <paramref name="comparisonValue" /> verglichen und möglicherweise ersetzt wird.</param>
        <param name="newValue">Der Wert, der den Wert des Elements mit dem angegebenen <paramref name="key" /> ersetzt, wenn der Vergleich Gleichheit ergibt.</param>
        <param name="comparisonValue">Der Wert, der mit dem Wert des Elements, bei dem <paramref name="key" /> angegeben ist, verglichen wird.</param>
        <summary>
            Vergleicht den vorhandenen Wert für den angegebenen Schlüssel mit einem angegebenen Wert und aktualisiert den Schlüssel mit einem dritten Wert, wenn sie gleich sind.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Updatevorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob das Objekt aktualisiert wurde.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">Transaktion, die diesen Vorgang zu verknüpfen.</param>
        <param name="key">Der Schlüssel, dessen Wert mit <paramref name="comparisonValue" /> verglichen und möglicherweise ersetzt wird.</param>
        <param name="newValue">Der Wert, der den Wert des Elements mit dem angegebenen <paramref name="key" /> ersetzt, wenn der Vergleich Gleichheit ergibt.</param>
        <param name="comparisonValue">Der Wert, der mit dem Wert des Elements, bei dem <paramref name="key" /> angegeben ist, verglichen wird.</param>
        <param name="timeout">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst. In erster Linie verwendet, um Deadlocks zu verhindern. Der Standardwert ist 4 Sekunden.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen. Der Standardwert ist „None“.</param>
        <summary>
            Vergleicht den vorhandenen Wert für den angegebenen Schlüssel mit einem angegebenen Wert und aktualisiert den Schlüssel mit einem dritten Wert, wenn sie gleich sind.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Updatevorgang darstellt. Das Ergebnis der Aufgabe gibt an, ob das Objekt aktualisiert wurde.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</exception>
        <exception cref="T:System.OperationCanceledException">Der Vorgang wurde abgebrochen.</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</exception>
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