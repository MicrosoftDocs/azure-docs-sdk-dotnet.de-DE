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
    <typeparam name="TKey"><span data-ttu-id="fd8c1-101">Der Typ der Schlüssel im Wörterbuch zuverlässige.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-101">The type of the keys in the Reliable Dictionary.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="fd8c1-102">Der Typ der Werte in der zuverlässigen Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-102">The type of the values in the Reliable Dictionary.</span></span></typeparam>
    <summary>
      <para><span data-ttu-id="fd8c1-103">Stellt eine zuverlässige Auflistung von Schlüssel/Wert-Paaren, die persistent gespeichert und repliziert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-103">Represents a Reliable Collection of key/value pairs that are persisted and replicated.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="fd8c1-104">Schlüssel oder Werte, die in dieses Wörterbuch aufweist und müssen nicht gespeichert werden außerhalb des Kontexts eines Vorgangs auf das Wörterbuch geändert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-104">Keys or values stored in this dictionary MUST NOT be mutated outside the context of an operation on the dictionary.</span></span> <span data-ttu-id="fd8c1-105">Es wird dringend empfohlen, beide <typeparamref name="TKey" /> und <typeparamref name="TValue" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-105">It is highly recommended to make both <typeparamref name="TKey" /> and <typeparamref name="TValue" /> immutable in order to avoid accidental data corruption.</span></span>
            <span data-ttu-id="fd8c1-106">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">hier</see> für häufige Probleme.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-106">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">here</see> for common pitfalls.</span></span></para>
      <para><span data-ttu-id="fd8c1-107">Die Transaktion ist die Einheit der Parallelität.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-107">The transaction is the unit of concurrency.</span></span> <span data-ttu-id="fd8c1-108">Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-108">Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="fd8c1-109">Wenn eine asynchrone zuverlässige Auflistung-Methode aufrufen, übernimmt ein <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, Sie müssen warten, auf den Abschluss der zurückgegebenen Aufgabe vor dem Aufrufen einer anderen Methode, die mit der gleichen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-109">When calling any asynchronous Reliable Collection method that takes an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, you must wait for completion of the returned Task before calling another method using the same transaction.</span></span> <span data-ttu-id="fd8c1-110">Beispiele für Transaktionen <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">hier</see>.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-110">See examples of transactions <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">here</see>.</span></span></para>
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
        <param name="tx"><span data-ttu-id="fd8c1-111">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-111">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-112">Der hinzuzufügende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-112">The key to be added.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-113">Der hinzuzufügende Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-113">The value to be added.</span></span> <span data-ttu-id="fd8c1-114">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-114">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-115">Die zuverlässige Wörterbuch hinzugefügt das angegebene Schlüssel-Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-115">Adds the specified key/value pair to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-116">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-116">A task that represents the asynchronous add operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-117"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-117"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="fd8c1-118">Das zuverlässige Wörterbuch enthält bereits ein Wert mit dem gleichen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-118">A value with the same key already exists in the Reliable Dictionary.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-119">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-119">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-120">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-120">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-121">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-121">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-122">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-122">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-123">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-123">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-124">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-124">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-125">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-125">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-126">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-126">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-127">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-127">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-128">Der hinzuzufügende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-128">The key to be added.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-129">Der hinzuzufügende Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-129">The value to be added.</span></span> <span data-ttu-id="fd8c1-130">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-130">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-131">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-131">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-132">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-132">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-133">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-133">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-134">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-134">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-135">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-135">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-136">Die zuverlässige Wörterbuch hinzugefügt das angegebene Schlüssel-Wert-Paar.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-136">Adds the specified key/value pair to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-137">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-137">A task that represents the asynchronous add operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-138"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-138"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="fd8c1-139">Ein Wert mit dem gleichen Schlüssel bereits im Wörterbuch zuverlässige vorhanden ist, oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-139">A value with the same key already exists in the Reliable Dictionary, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-140">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-140">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-141">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-141">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-142">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-142">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-143">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-143">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-144">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-144">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-145">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-145">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-146">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-146">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-147">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-147">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-148">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-148">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-149">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-149">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-150">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-150">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValueFactory"><span data-ttu-id="fd8c1-151">Die Funktion zum Generieren eines Werts für einen nicht vorhandenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-151">The function used to generate a value for an absent key.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="fd8c1-152">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-152">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-153">Verwendet die angegebene Funktionen, die zuverlässige Wörterbuch ein Schlüssel/Wert-Paar hinzugefügt werden, wenn der Schlüssel nicht bereits vorhanden ist oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige zu aktualisieren, wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-153">Uses the specified functions to add a key/value pair to the Reliable Dictionary if the key does not already exist, or to update a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-154">Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-154">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="fd8c1-155">Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-155">The task result is the new value for the key.</span></span> <span data-ttu-id="fd8c1-156">Dies ist das Ergebnis von AddValueFactory (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-156">This will be either the result of addValueFactory (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-157"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="addValueFactory" /> null ist, oder <paramref name="updateValueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-157"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="addValueFactory" /> is null, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-158">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-158">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-159">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-159">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-160">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-160">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-161">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-161">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-162">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-162">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-163">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-163">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-164">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-164">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-165">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-165">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-166">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-166">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-167">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-167">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValue"><span data-ttu-id="fd8c1-168">Der Wert für einen nicht vorhandenen Schlüssel hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-168">The value to be added for an absent key.</span></span> <span data-ttu-id="fd8c1-169">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-169">The value can be null for reference types.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="fd8c1-170">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-170">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-171">Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige aktualisiert mithilfe der angegebenen Funktion, wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-171">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary by using the specified function if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-172">Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-172">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="fd8c1-173">Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-173">The task result is the new value for the key.</span></span> <span data-ttu-id="fd8c1-174">Dies ist entweder AddValue (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-174">This will be either addValue (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-175"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="updateValueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-175"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-176">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-176">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-177">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-177">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-178">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-178">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-179">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-179">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-180">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-180">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-181">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-181">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-182">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-182">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-183">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-183">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-184">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-184">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-185">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-185">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValueFactory"><span data-ttu-id="fd8c1-186">Die Funktion zum Generieren eines Werts für einen nicht vorhandenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-186">The function used to generate a value for an absent key.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="fd8c1-187">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-187">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-188">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-188">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-189">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-189">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-190">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-190">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-191">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-191">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-192">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-192">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-193">Verwendet die angegebene Funktionen, die zuverlässige Wörterbuch ein Schlüssel/Wert-Paar hinzugefügt werden, wenn der Schlüssel nicht bereits vorhanden ist oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige zu aktualisieren, wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-193">Uses the specified functions to add a key/value pair to the Reliable Dictionary if the key does not already exist, or to update a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-194">Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-194">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="fd8c1-195">Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-195">The task result is the new value for the key.</span></span> <span data-ttu-id="fd8c1-196">Dies ist das Ergebnis von AddValueFactory (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-196">This will be either the result of addValueFactory (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-197"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="addValueFactory" /> null ist, oder <paramref name="updateValueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-197"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="addValueFactory" /> is null, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-198"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-198"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-199">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-199">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-200">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-200">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-201">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-201">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-202">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-202">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-203">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-203">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-204">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-204">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-205">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-205">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-206">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-206">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-207">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-207">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-208">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-208">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-209">Der Schlüssel, der hinzugefügt oder dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-209">The key to be added or whose value should be updated.</span></span></param>
        <param name="addValue"><span data-ttu-id="fd8c1-210">Der Wert für einen nicht vorhandenen Schlüssel hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-210">The value to be added for an absent key.</span></span> <span data-ttu-id="fd8c1-211">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-211">The value can be null for reference types.</span></span></param>
        <param name="updateValueFactory"><span data-ttu-id="fd8c1-212">Die Funktion zum Generieren eines neuen Werts für einen vorhandenen Schlüssel auf Grundlage des vorhandenen Werts des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-212">The function used to generate a new value for an existing key based on the key's existing value.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-213">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-213">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-214">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-214">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-215">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-215">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-216">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-216">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-217">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-217">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-218">Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige aktualisiert mithilfe der angegebenen Funktion, wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-218">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary by using the specified function if the key already exists.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-219">Eine Aufgabe, die den asynchronen hinzufügen oder Update-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-219">Task that represents the asynchronous add or update operation.</span></span> <span data-ttu-id="fd8c1-220">Das Ergebnis der Aufgabe wird der neue Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-220">The task result is the new value for the key.</span></span> <span data-ttu-id="fd8c1-221">Dies ist entweder AddValue (wenn der Schlüssel nicht vorhanden war) oder das Ergebnis von UpdateValueFactory (wenn der Schlüssel vorhanden war) sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-221">This will be either addValue (if the key was absent) or the result of updateValueFactory (if the key was present).</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-222"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="updateValueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-222"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="updateValueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-223"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-223"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-224">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-225">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-225">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-226">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-226">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-227">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-227">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-228">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-228">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-229">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-229">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-230">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-230">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-231">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-231">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-232">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-232">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="timeout"><span data-ttu-id="fd8c1-233">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-233">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-234">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-234">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-235">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-235">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-236">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-236">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-237">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-237">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-238">Entfernt alle Schlüssel und Werte aus dem zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-238">Removes all keys and values from the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-239">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-239">Task that represents the asynchronous clear operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-240"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-240"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-241">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-241">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-242">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-242">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-243">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-243">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-244">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-244">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-245">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-245">The key to locate in the Reliable Dictionary.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-246">Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-246">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-247">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-247">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="fd8c1-248">Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-248">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-249"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-249"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-250">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-250">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-251">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-251">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-252">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-252">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-253">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-253">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-254">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-254">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-255">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-255">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-256">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-256">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-257">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-257">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-258">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-258">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-259">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-259">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-260">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-260">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-261">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-261">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-262">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-262">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="lockMode"><span data-ttu-id="fd8c1-263">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-263">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-264">Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-264">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-265">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-265">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="fd8c1-266">Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-266">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-267"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-267"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-268">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-268">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-269">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-269">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-270">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-270">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-271">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-271">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-272">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-272">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-273">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-273">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-274">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-274">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-275">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-275">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-276">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-276">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-277">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-277">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-278">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-278">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-279">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-279">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-280">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-280">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-281">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-281">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-282">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-282">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-283">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-283">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-284">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-284">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-285">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-285">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-286">Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-286">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-287">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-287">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="fd8c1-288">Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-288">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-289"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-289"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-290"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-290"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-291">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-291">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-292">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-292">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-293">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-293">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-294">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-294">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-295">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-295">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-296">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-296">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-297">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-297">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-298">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-298">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-299">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-299">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-300">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-300">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-301">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-301">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-302">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-302">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-303">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-303">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-304">Die im zuverlässigen Wörterbuch zu suchende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-304">The key to locate in the Reliable Dictionary.</span></span></param>
        <param name="lockMode"><span data-ttu-id="fd8c1-305">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-305">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-306">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-306">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-307">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-307">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-308">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-308">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-309">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-309">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-310">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-310">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-311">Bestimmt, ob das zuverlässige Wörterbuch den angegebenen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-311">Determines whether the Reliable Dictionary contains the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-312">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-312">A task that represents the asynchronous operation.</span></span> <span data-ttu-id="fd8c1-313">Das Ergebnis der Aufgabe gibt an, ob der Schlüssel vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-313">The task result indicates whether the key exists.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-314"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-314"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-315"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-315"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-316">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-316">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-317">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-317">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-318">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-318">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-319">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-319">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-320">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-320">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-321">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-321">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-322">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-322">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-323">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-323">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-324">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-324">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-325">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-325">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-326">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-326">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-327">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-327">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="txn"><span data-ttu-id="fd8c1-328">Die Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-328">The transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-329">Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-329">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="fd8c1-330">Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-330">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="fd8c1-331">Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-331">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="fd8c1-332">Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-332">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="fd8c1-333">Es stellt eine einheitliche Ansicht der Momentaufnahme dar.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-333">It represents a snapshot consistent view.</span></span> <span data-ttu-id="fd8c1-334">Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-334">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="fd8c1-335">Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-335">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-336">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-336">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-337">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-337">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-338">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-338">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-339">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-339">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-340">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-340">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-341">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-341">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-342">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-342">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-343">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-343">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-344">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-344">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="fd8c1-345">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-345">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
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
        <param name="txn"><span data-ttu-id="fd8c1-346">Die Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-346">The transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="fd8c1-347">Die zu verwendende enumerationsmodus.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-347">The enumeration mode to use.</span></span> <span data-ttu-id="fd8c1-348">Die Standardeinstellung ist nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-348">The default is Unordered.</span></span> <span data-ttu-id="fd8c1-349">Geordnete Enumeration ist nur Aufsteigend.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-349">Ordered enumeration is ascending only.</span></span> </param>
        <summary>
            <span data-ttu-id="fd8c1-350">Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-350">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="fd8c1-351">Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-351">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="fd8c1-352">Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-352">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="fd8c1-353">Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-353">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="fd8c1-354">Es stellt eine einheitliche Ansicht der Momentaufnahme dar.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-354">It represents a snapshot consistent view.</span></span> <span data-ttu-id="fd8c1-355">Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-355">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="fd8c1-356">Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-356">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-357">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-357">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-358">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-358">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-359">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-359">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-360">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-360">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-361">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-361">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-362">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-362">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-363">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-363">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-364">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-364">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-365">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-365">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="fd8c1-366">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-366">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
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
        <param name="txn"><span data-ttu-id="fd8c1-367">Die Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-367">The transaction to associate this operation with.</span></span></param>
        <param name="filter"><span data-ttu-id="fd8c1-368">Prädikat filtert, die die Schlüssel-Wert-Paare in der Enumeration, die anhand des Schlüssels eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-368">Predicate that filters the key-value pairs to include in the enumeration based on the key.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="fd8c1-369">Die zu verwendende enumerationsmodus.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-369">The enumeration mode to use.</span></span> <span data-ttu-id="fd8c1-370">Die Standardeinstellung ist nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-370">The default is Unordered.</span></span> <span data-ttu-id="fd8c1-371">Geordnete Enumeration ist nur Aufsteigend.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-371">Ordered enumeration is ascending only.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-372">Erstellt einen asynchrone Enumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-372">Creates an asynchronous enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="fd8c1-373">Erstellungsvorgang aufzählbare für eine Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-373">A task that represents the asynchronous create enumerable operation.</span></span> <span data-ttu-id="fd8c1-374">Das Ergebnis der Aufgabe ist ein Enumerator für das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-374">The task result is an enumerator for the Reliable Dictionary.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="fd8c1-375">Der zurückgegebene Enumerator sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das zuverlässige Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-375">The returned enumerator is safe to use concurrently with reads and writes to the Reliable Dictionary.</span></span>
            <span data-ttu-id="fd8c1-376">Es stellt eine einheitliche Ansicht der Momentaufnahme dar.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-376">It represents a snapshot consistent view.</span></span> <span data-ttu-id="fd8c1-377">Bitte beachten Sie, dass <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> muss auf die zurückgegebenen IAsyncEnumerable aufgerufen werden, um aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-377">Please note that <see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" /> needs to be called on the returned IAsyncEnumerable in order to enumerate.</span></span> <span data-ttu-id="fd8c1-378">Beispiele für die Nutzung überwachungsarbeitsbereich <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">hier</see>.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-378">Example usage can be seen <see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">here</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-379">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-379">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-380">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-380">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-381">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-381">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-382">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-382">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-383">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-383">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-384">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-384">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-385">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-385">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-386">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-386">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-387">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-387">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="fd8c1-388">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-388">Indicates that the Reliable Dictionary is closed or deleted.</span></span></para>
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
            <span data-ttu-id="fd8c1-389">Tritt auf, wenn die zuverlässige Wörterbuch ändert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-389">Occurs when the Reliable Dictionary changes.</span></span>
            <span data-ttu-id="fd8c1-390">Z. B. hinzufügen, aktualisieren oder Entfernen eines Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-390">For example, addition, update or removal of an item.</span></span>
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
        <param name="tx"><span data-ttu-id="fd8c1-391">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-391">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-392">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-392">The key of the element to add.</span></span></param>
        <param name="valueFactory"><span data-ttu-id="fd8c1-393">Die Funktion, mit der ein Wert für den Schlüssel generiert wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-393">The function used to generate a value for the key.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-394">Fügt ein Schlüssel/Wert-Paar dem zuverlässige Wörterbuch hinzu mithilfe der angegebenen Funktion, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-394">Adds a key/value pair to the Reliable Dictionary by using the specified function, if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-395">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-395">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-396">Das Taskergebnis ist der Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-396">The task result is the value for the key.</span></span> <span data-ttu-id="fd8c1-397">Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert für den Schlüssel, wie von ValueFactory zurückgegeben, wenn der Schlüssel nicht im Wörterbuch zuverlässige war wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-397">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value for the key as returned by valueFactory if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-398"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="valueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-398"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="valueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-399">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-399">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-400">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-400">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-401">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-401">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-402">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-402">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-403">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-403">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-404">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-404">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-405">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-405">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-406">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-406">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-407">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-407">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-408">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-408">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-409">Der hinzuzufügende Wert, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-409">The value to be added, if the key does not already exist.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-410">Fügt ein Schlüssel/Wert-Paar zuverlässige Wörterbuch, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-410">Adds a key/value pair to the Reliable Dictionary if the key does not already exist.</span></span>
            <span data-ttu-id="fd8c1-411">Wenn der Schlüssel vorhanden ist keine Updates auf den Wert erfolgt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-411">If the key exists no updates will be made to the value.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-412">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-412">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-413">Das Taskergebnis ist der Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-413">The task result is the value for the key.</span></span> <span data-ttu-id="fd8c1-414">Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert, wenn der Schlüssel nicht im Wörterbuch zuverlässige war.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-414">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-415"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-415"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-416">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-416">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-417">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-417">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-418">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-418">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-419">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-419">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-420">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-420">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-421">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-421">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-422">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-422">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-423">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-423">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-424">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-424">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-425">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-425">The key of the element to add.</span></span></param>
        <param name="valueFactory"><span data-ttu-id="fd8c1-426">Die Funktion, mit der ein Wert für den Schlüssel generiert wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-426">The function used to generate a value for the key.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-427">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-427">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-428">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-428">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-429">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-429">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-430">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-430">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-431">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-431">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-432">Fügt ein Schlüssel/Wert-Paar dem zuverlässige Wörterbuch hinzu mithilfe der angegebenen Funktion, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-432">Adds a key/value pair to the Reliable Dictionary by using the specified function, if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-433">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-433">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-434">Das Taskergebnis ist der Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-434">The task result is the value for the key.</span></span> <span data-ttu-id="fd8c1-435">Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert für den Schlüssel, wie von ValueFactory zurückgegeben, wenn der Schlüssel nicht im Wörterbuch zuverlässige war wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-435">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value for the key as returned by valueFactory if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-436"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden, oder <paramref name="valueFactory" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-436"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized, or <paramref name="valueFactory" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-437"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-437"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-438">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-438">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-439">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-439">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-440">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-440">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-441">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-441">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-442">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-442">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-443">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-443">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-444">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-444">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-445">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-445">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-446">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-446">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-447">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-447">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-448">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-448">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-449">Der hinzuzufügende Wert, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-449">The value to be added, if the key does not already exist.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-450">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-450">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-451">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-451">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-452">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-452">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-453">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-453">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-454">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-454">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-455">Fügt ein Schlüssel/Wert-Paar zuverlässige Wörterbuch, wenn der Schlüssel nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-455">Adds a key/value pair to the Reliable Dictionary if the key does not already exist.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-456">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-456">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-457">Das Taskergebnis ist der Wert für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-457">The task result is the value for the key.</span></span> <span data-ttu-id="fd8c1-458">Dies ist entweder der vorhandene Wert für den Schlüssel, wenn der Schlüssel bereits im Wörterbuch zuverlässig ist, oder der neue Wert, wenn der Schlüssel nicht im Wörterbuch zuverlässige war.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-458">This will be either the existing value for the key if the key is already in the Reliable Dictionary, or the new value if the key was not in the Reliable Dictionary.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-459"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-459"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-460"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-460"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-461">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-461">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-462">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-462">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-463">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-463">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-464">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-464">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-465">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-465">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-466">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-466">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-467">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-467">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-468">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-468">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-469">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-469">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
            <span data-ttu-id="fd8c1-470">Eine Funktion, die aufgerufen wird, wenn die zuverlässige Wörterbuch während kopieren/wiederherstellen bzw. Wiederherstellung neu erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-470">A function that is called when the Reliable Dictionary is being rebuilt during copy, restore or recovery.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fd8c1-471">Die asynchrone Rebuild-Benachrichtigung-Funktion.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-471">The asynchronous rebuild notification function.</span></span> <span data-ttu-id="fd8c1-472">Funktion nimmt IReliableDictionary und NotifyDictionaryRebuildEventArgs-Token und gibt eine Aufgabe, die asynchrone Verarbeitung der Benachrichtigung Rebuild darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-472">Function takes in IReliableDictionary and NotifyDictionaryRebuildEventArgs token and returns a Task that represents the asynchronous processing of the rebuild notification.</span></span>
            </value>
        <remarks>
          <span data-ttu-id="fd8c1-473"><see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />kann nur innerhalb dieses Rückrufs verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-473"><see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" /> can only be used within this callback.</span></span>
            <span data-ttu-id="fd8c1-474">Sobald der asynchrone Rückruf abgeschlossen ist, die <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" /> ungültig wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-474">Once the asynchronous callback completes, the <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" /> becomes invalid.</span></span> <span data-ttu-id="fd8c1-475">Weitere Informationen finden Sie <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">hier</see>.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-475">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">here</see> for more information.</span></span> 
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
        <param name="tx"><span data-ttu-id="fd8c1-476">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-476">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-477">Der Schlüssel, dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-477">The key whose value should be updated.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-478">Der Wert, der den Wert des Elements ersetzt, die dem angegebenen <paramref name="key" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-478">The value that replaces the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-479">Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige, aktualisiert Wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-479">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-480">Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-480">A task that represents the asynchronous update operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-481"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-481"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-482"><paramref name="key" />ist nicht im Wörterbuch zuverlässige vorhanden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-482"><paramref name="key" /> does not exist in the Reliable Dictionary.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-483">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-483">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-484">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-484">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-485">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-485">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-486">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-486">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-487">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-487">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-488">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-488">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-489">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-489">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-490">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-490">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-491">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-491">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-492">Der Schlüssel, dessen Wert aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-492">The key whose value should be updated.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-493">Der Wert, der den Wert des Elements ersetzt, die dem angegebenen <paramref name="key" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-493">The value that replaces the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-494">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-494">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-495">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-495">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-496">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-496">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-497">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-497">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-498">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-498">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-499">Fügt ein Schlüssel/Wert-Paar zum zuverlässigen Wörterbuch, wenn der Schlüssel nicht bereits vorhanden, oder ein Schlüssel-Wert-Paar im Wörterbuch zuverlässige, aktualisiert Wenn der Schlüssel bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-499">Adds a key/value pair to the Reliable Dictionary if the key does not already exist, or updates a key/value pair in the Reliable Dictionary if the key already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-500">Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-500">A task that represents the asynchronous update operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-501"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-501"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-502"><paramref name="key" />in der zuverlässigen Wörterbuch vorhanden ist, nicht vorhanden oder <paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-502"><paramref name="key" /> does not exist in the Reliable Dictionary, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-503">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-503">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-504">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-504">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-505">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-505">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-506">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-506">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-507">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-507">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-508">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-508">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-509">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-509">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-510">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-510">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-511">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-511">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-512">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-512">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-513">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-513">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-514">Der Wert des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-514">The value of the element to add.</span></span> <span data-ttu-id="fd8c1-515">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-515">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-516">Versucht, die zuverlässige Wörterbuch den angegebenen Schlüssel und Wert hinzu.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-516">Attempts to add the specified key and value to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-517">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-517">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-518">Das Ergebnis der Aufgabe gibt an, ob das Schlüssel/Wert-Paar hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-518">The task result indicates whether the key/value pair was added.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-519"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-519"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-520">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-520">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-521">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-521">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-522">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-522">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-523">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-523">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-524">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-524">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-525">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-525">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-526">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-526">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-527">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-527">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-528">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-528">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-529">Der Schlüssel des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-529">The key of the element to add.</span></span></param>
        <param name="value"><span data-ttu-id="fd8c1-530">Der Wert des hinzuzufügenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-530">The value of the element to add.</span></span> <span data-ttu-id="fd8c1-531">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-531">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-532">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-532">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-533">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-533">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-534">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-534">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-535">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-535">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-536">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-536">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-537">Versucht, die zuverlässige Wörterbuch den angegebenen Schlüssel und Wert hinzu.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-537">Attempts to add the specified key and value to the Reliable Dictionary.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-538">Das Hinzufügen einer Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-538">A task that represents the asynchronous add operation.</span></span> <span data-ttu-id="fd8c1-539">Das Ergebnis der Aufgabe gibt an, ob das Schlüssel/Wert-Paar hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-539">The task result indicates whether the key/value pair was added.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-540"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-540"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-541"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-541"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-542">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-542">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-543">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-543">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-544">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-544">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-545">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-545">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-546">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-546">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-547">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-547">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-548">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-548">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-549">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-549">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-550">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-550">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-551">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-551">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-552">Der Schlüssel des abzurufenden Werts.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-552">The key of the value to get.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-553">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-553">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-554">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-554">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="fd8c1-555">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-555">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-556"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-556"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-557">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-557">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-558">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-558">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-559">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-559">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-560">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-560">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-561">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-561">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-562">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-562">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-563">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-563">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-564">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-564">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-565">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-565">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-566">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-566">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-567">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-567">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-568">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-568">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-569">Der Schlüssel des abzurufenden Werts.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-569">The key of the value to get.</span></span></param>
        <param name="lockMode"><span data-ttu-id="fd8c1-570">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-570">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-571">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-571">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-572">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-572">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="fd8c1-573">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-573">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-574"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-574"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-575">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-575">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-576">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-576">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-577">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-577">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-578">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-578">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-579">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-579">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-580">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-580">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-581">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-581">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-582">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-582">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-583">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-583">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-584">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-584">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-585">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-585">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-586">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-586">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-587">Der Schlüssel des abzurufenden Werts.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-587">The key of the value to get.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-588">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-588">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-589">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-589">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-590">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-590">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-591">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-591">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-592">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-592">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-593">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-593">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-594">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-594">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="fd8c1-595">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-595">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-596"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-596"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-597"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-597"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-598">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-598">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-599">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-599">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-600">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-600">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-601">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-601">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-602">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-602">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-603">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-603">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-604">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-604">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-605">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-605">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-606">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-606">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-607">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-607">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-608">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-608">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-609">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-609">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-610">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-610">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-611">Der Schlüssel des abzurufenden Werts.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-611">The key of the value to get.</span></span></param>
        <param name="lockMode"><span data-ttu-id="fd8c1-612">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-612">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-613">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-613">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-614">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-614">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-615">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-615">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-616">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-616">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-617">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-617">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-618">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässig abzurufen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-618">Attempts to get the value associated with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-619">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-619">A task that represents the asynchronous read operation.</span></span> <span data-ttu-id="fd8c1-620">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel im Wörterbuch zuverlässige gefunden wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-620">The task result is a tuple indicating whether the key was found in the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-621"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-621"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-622"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-622"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-623">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-623">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-624">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-624">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="fd8c1-625">Gibt an, dass die IReliableDictionary Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-625">Indicates that the IReliableDictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="fd8c1-626">Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-626">This exception can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="fd8c1-627">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-627">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> role is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="fd8c1-628">Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-628">One reason it may be thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-629">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-629">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-630">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-630">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-631">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-631">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-632">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-632">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-633">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-633">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-634">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-634">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-635">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-635">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-636">Der Schlüssel des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-636">The key of the element to remove.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-637">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässige zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-637">Attempts to remove the value with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-638">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-638">Task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="fd8c1-639">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel aus dem zuverlässige Wörterbuch entfernt wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-639">The task result is a tuple indicating whether the key was removed from the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-640"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-640"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-641">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-641">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-642">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-642">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-643">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-643">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-644">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-644">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-645">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-645">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-646">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-646">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-647">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-647">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-648">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-648">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-649">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-649">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-650">Der Schlüssel des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-650">The key of the element to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-651">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-651">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-652">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-652">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-653">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-653">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-654">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-654">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-655">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-655">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-656">Versucht, den Wert mit dem angegebenen Schlüssel aus dem Wörterbuch zuverlässige zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-656">Attempts to remove the value with the specified key from the Reliable Dictionary.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fd8c1-657">Eine Aufgabe, die den asynchronen Entfernungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-657">Task that represents the asynchronous remove operation.</span></span> <span data-ttu-id="fd8c1-658">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob der Schlüssel aus dem zuverlässige Wörterbuch entfernt wurde, und wenn dies der Fall ist, wird der Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-658">The task result is a tuple indicating whether the key was removed from the Reliable Dictionary and if so, the value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-659"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-659"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-660"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-660"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-661">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-661">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-662">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-662">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-663">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-663">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-664">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-664">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-665">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-665">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-666">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-666">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-667">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-667">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-668">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-668">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-669">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-669">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-670">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-670">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-671">Der Schlüssel, dessen Wert mit <paramref name="comparisonValue" /> verglichen und möglicherweise ersetzt wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-671">The key whose value is compared with <paramref name="comparisonValue" /> and possibly replaced.</span></span></param>
        <param name="newValue"><span data-ttu-id="fd8c1-672">Der Wert, der den Wert des Elements mit dem angegebenen <paramref name="key" /> ersetzt, wenn der Vergleich Gleichheit ergibt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-672">The value that replaces the value of the element that has the specified <paramref name="key" /> if the comparison results in equality.</span></span></param>
        <param name="comparisonValue"><span data-ttu-id="fd8c1-673">Der Wert, der mit dem Wert des Elements, bei dem <paramref name="key" /> angegeben ist, verglichen wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-673">The value that is compared to the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-674">Vergleicht den vorhandenen Wert für den angegebenen Schlüssel mit einem angegebenen Wert und aktualisiert den Schlüssel mit einem dritten Wert, wenn sie gleich sind.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-674">Compares the existing value for the specified key with a specified value, and if they are equal, updates the key with a third value.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-675">Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-675">A task that represents the asynchronous update operation.</span></span> <span data-ttu-id="fd8c1-676">Das Ergebnis der Aufgabe gibt an, ob das Objekt aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-676">The task result indicates whether the object was updated.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-677"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-677"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-678">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-678">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-679">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-679">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-680">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-680">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-681">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-681">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-682">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-682">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-683">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-683">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-684">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-684">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-685">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-685">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="tx"><span data-ttu-id="fd8c1-686">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-686">Transaction to associate this operation with.</span></span></param>
        <param name="key"><span data-ttu-id="fd8c1-687">Der Schlüssel, dessen Wert mit <paramref name="comparisonValue" /> verglichen und möglicherweise ersetzt wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-687">The key whose value is compared with <paramref name="comparisonValue" /> and possibly replaced.</span></span></param>
        <param name="newValue"><span data-ttu-id="fd8c1-688">Der Wert, der den Wert des Elements mit dem angegebenen <paramref name="key" /> ersetzt, wenn der Vergleich Gleichheit ergibt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-688">The value that replaces the value of the element that has the specified <paramref name="key" /> if the comparison results in equality.</span></span></param>
        <param name="comparisonValue"><span data-ttu-id="fd8c1-689">Der Wert, der mit dem Wert des Elements, bei dem <paramref name="key" /> angegeben ist, verglichen wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-689">The value that is compared to the value of the element that has the specified <paramref name="key" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="fd8c1-690">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-690">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="fd8c1-691">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-691">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="fd8c1-692">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-692">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fd8c1-693">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-693">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="fd8c1-694">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-694">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="fd8c1-695">Vergleicht den vorhandenen Wert für den angegebenen Schlüssel mit einem angegebenen Wert und aktualisiert den Schlüssel mit einem dritten Wert, wenn sie gleich sind.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-695">Compares the existing value for the specified key with a specified value, and if they are equal, updates the key with a third value.</span></span>
            </summary>
        <returns><span data-ttu-id="fd8c1-696">Eine Aufgabe, die den asynchronen Updatevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-696">A task that represents the asynchronous update operation.</span></span> <span data-ttu-id="fd8c1-697">Das Ergebnis der Aufgabe gibt an, ob das Objekt aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-697">The task result indicates whether the object was updated.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="fd8c1-698"><paramref name="tx" />ist null, oder <paramref name="key" /> ist null oder nicht serialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-698"><paramref name="tx" /> is null, or <paramref name="key" /> is null or cannot be serialized.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="fd8c1-699"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-699"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="fd8c1-700">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-700">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="fd8c1-701">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-701">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="fd8c1-702">Die Ausnahme ausgelöst, wenn ist die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> befindet sich nicht in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-702">The exception that is thrown when the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="fd8c1-703">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-703">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="fd8c1-704">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="fd8c1-704">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="fd8c1-705">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-705">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="fd8c1-706">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-706">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="fd8c1-707">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-707">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="fd8c1-708">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="fd8c1-708">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>