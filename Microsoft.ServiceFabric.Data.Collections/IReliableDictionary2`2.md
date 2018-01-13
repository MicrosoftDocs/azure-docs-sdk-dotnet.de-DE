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
    <typeparam name="TKey"><span data-ttu-id="9b7d3-101">Der Typ der Schlüssel im Wörterbuch zuverlässige.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-101">The type of the keys in the reliable dictionary.</span></span></typeparam>
    <typeparam name="TValue">
            <span data-ttu-id="9b7d3-102">Der Typ der Werte in der zuverlässigen Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-102">The type of the values in the reliable dictionary.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9b7d3-103">Stellt eine zuverlässige Auflistung von Schlüssel/Wert-Paaren, die persistent gespeichert und repliziert werden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-103">Represents a reliable collection of key/value pairs that are persisted and replicated.</span></span>
            </summary>
    <remarks><span data-ttu-id="9b7d3-104">Schlüssel oder Werte, die in dieses Wörterbuch aufweist und müssen nicht gespeichert werden außerhalb des Kontexts eines Vorgangs auf das Wörterbuch geändert.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-104">Keys or values stored in this dictionary MUST NOT be mutated outside the context of an operation on the dictionary.</span></span>  <span data-ttu-id="9b7d3-105">Es wird dringend empfohlen, beide <typeparamref name="TKey" /> und <typeparamref name="TValue" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-105">It is highly recommended to make both <typeparamref name="TKey" /> and <typeparamref name="TValue" /> immutable in order to avoid accidental data corruption.</span></span>
            
            <span data-ttu-id="9b7d3-106"><para>Die Transaktion ist die Einheit der Parallelität. Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an. Wenn eine asynchrone zuverlässige Auflistung-Methode aufrufen, übernimmt ein <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, Sie müssen warten, auf den Abschluss der zurückgegebenen Aufgabe vor dem Aufrufen einer anderen Methode, die mit der gleichen Transaktion.</para></span><span class="sxs-lookup"><span data-stu-id="9b7d3-106"><para> The transaction is the unit of concurrency. Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time. When calling any asynchronous Reliable Collection method that takes an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />, you must wait for completion of the returned Task before calling another method using the same transaction. </para></span></span></remarks>
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
            <span data-ttu-id="9b7d3-107">Ruft die Anzahl der Schlüssel-Wert-Paare der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-107">Gets the number of key-value pairs contained in the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9b7d3-108">Diese Eigenschaft hat keine Transaktionssemantik.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-108">This property does not have transactional semantics.</span></span> <span data-ttu-id="9b7d3-109">Es stellt die beste Aufwand Anzahl der Elemente im Wörterbuch dar, zum Zeitpunkt, wenn die Eigenschaft zugegriffen wurde.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-109">It represents the best effort number of items in the dictionary at the moment when the property was accessed.</span></span>
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
        <param name="txn"><span data-ttu-id="9b7d3-110">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-110">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="9b7d3-111">Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-111">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="9b7d3-112">Ein aufzählbares Element für die zuverlässige Wörterbuchschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-112">An enumerable for the reliable dictionary keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="9b7d3-113">Die Enumerarable zurückgegeben, aus dem Wörterbuch zuverlässige sicher gleichzeitig mit der Lesevorgänge verwendet wird und schreibt in das Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-113">The enumerarable returned from the reliable dictionary is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="9b7d3-114">Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-114">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="9b7d3-115">Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-115">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="9b7d3-116"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-116"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="9b7d3-117">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-117">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="9b7d3-118">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-118">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="9b7d3-119">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-119">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="9b7d3-120">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="9b7d3-120">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="9b7d3-121">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-121">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="9b7d3-122">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-122">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="9b7d3-123">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-123">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="9b7d3-124">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-124">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="txn"><span data-ttu-id="9b7d3-125">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-125">Transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="9b7d3-126">Die zu verwendende enumerationsmodus.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-126">The enumeration mode to use.</span></span> <span data-ttu-id="9b7d3-127">Die Standardeinstellung ist nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-127">The default is Unordered.</span></span></param>
        <summary>
            <span data-ttu-id="9b7d3-128">Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-128">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="9b7d3-129">Ein aufzählbares Element für die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-129">An enumerable for the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="9b7d3-130">Die Enumerarable zurückgegeben, die von der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> sicher gleichzeitig mit der Lesevorgänge verwendet wird, und schreibt in das Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-130">The enumerarable returned from the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="9b7d3-131">Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-131">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="9b7d3-132">Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-132">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="9b7d3-133"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-133"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="9b7d3-134">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-134">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="9b7d3-135">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-135">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="9b7d3-136">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-136">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="9b7d3-137">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="9b7d3-137">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="9b7d3-138">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-138">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="9b7d3-139">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-139">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="9b7d3-140">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-140">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="9b7d3-141">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-141">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
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
        <param name="txn"><span data-ttu-id="9b7d3-142">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-142">Transaction to associate this operation with.</span></span></param>
        <param name="enumerationMode"><span data-ttu-id="9b7d3-143">Die zu verwendende enumerationsmodus.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-143">The enumeration mode to use.</span></span> <span data-ttu-id="9b7d3-144">Die Standardeinstellung ist nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-144">The default is Unordered.</span></span></param>
        <param name="timeout">
            <span data-ttu-id="9b7d3-145">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-145">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="9b7d3-146">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-146">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="9b7d3-147">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-147">The default is 4 seconds.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="9b7d3-148">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-148">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="9b7d3-149">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-149">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="9b7d3-150">Erstellt einen AsyncEnumerator über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> die Schlüssel aufgelistet werden.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-150">Creates an async enumerator over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> to enumerate the keys.</span></span>
            </summary>
        <returns><span data-ttu-id="9b7d3-151">Ein aufzählbares Element für die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-151">An enumerable for the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> keys.</span></span></returns>
        <remarks>
            <span data-ttu-id="9b7d3-152">Die Enumerarable zurückgegeben, die von der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> sicher gleichzeitig mit der Lesevorgänge verwendet wird, und schreibt in das Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-152">The enumerarable returned from the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" /> is safe to use concurrently with reads and writes to the dictionary.</span></span> <span data-ttu-id="9b7d3-153">Es stellt eine konsistente Sicht der Momentaufnahme des Wörterbuchs dar.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-153">It represents a snapshot consistent view of the dictionary.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="9b7d3-154">Ausnahme gibt an, dass das zuverlässige Wörterbuch Lesevorgänge im Moment nicht bedienen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-154">Exception indicates that the Reliable Dictionary cannot serve reads at the moment.</span></span>
            <span data-ttu-id="9b7d3-155"><see cref="T:System.Fabric.FabricNotReadableException" />ausgelöst werden kann, in allen <see cref="T:System.Fabric.ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-155"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="9b7d3-156">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.Primary" /> ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-156">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.Primary" /> is loss of <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="9b7d3-157">Ein Beispiel dafür ausgelöst wird, der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-157">One example for it being thrown in the <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> is that Reliable Collection's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="9b7d3-158">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-158">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="9b7d3-159">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="9b7d3-159">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="9b7d3-160">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-160">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="9b7d3-161">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-161">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="9b7d3-162">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-162">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="9b7d3-163">Gibt an, dass das zuverlässige Wörterbuch geschlossen oder gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9b7d3-163">Indicates that the Reliable Dictionary is closed or deleted.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>