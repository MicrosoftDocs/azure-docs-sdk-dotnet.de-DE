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
    <typeparam name="T"><span data-ttu-id="37d0c-101">Der Typ der Elemente in der zuverlässige Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="37d0c-101">The type of the elements contained in the reliable queue.</span></span></typeparam>
    <summary>
            <span data-ttu-id="37d0c-102">Stellt eine zuverlässige First-in-First-Out Auflistung von Objekten, die persistent gespeichert und repliziert werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-102">Represents a reliable first-in, first-out collection of objects that are persisted and replicated.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="37d0c-103">In dieser Warteschlange darf keinen gespeicherte Werten werden geändert, außerhalb des Kontexts eines Vorgangs in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="37d0c-103">Values stored in this queue MUST NOT be mutated outside the context of an operation on the queue.</span></span> <span data-ttu-id="37d0c-104">Es wird dringend empfohlen, stellen <typeparamref name="T" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-104">It is highly recommended to make <typeparamref name="T" /> immutable in order to avoid accidental data corruption.</span></span>
            </para>
      <para>
            <span data-ttu-id="37d0c-105">Transaktion ist die Einheit der Parallelität: Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden jeweils einzeln.</span><span class="sxs-lookup"><span data-stu-id="37d0c-105">Transaction is the unit of concurrency: Users can have multiple transactions in-flight at any given point of time but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="37d0c-106">Daher sind alle zuverlässige Auflistung-APIs, die in einer Transaktion annehmen und eine Aufgabe zurückgeben muss erwartete einzeln nacheinander.</span><span class="sxs-lookup"><span data-stu-id="37d0c-106">So all Reliable Collection APIs that take in a transaction and return a Task, must be awaited one at a time.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-107">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-107">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-108">Erstellt eine asynchrone aufzählbare über die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-108">Creates an async enumerable over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="37d0c-109">IEnumerable, das alle Werte darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-109">IEnumerable that represents all the values.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="37d0c-110">Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-110">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="37d0c-111"><cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="37d0c-111"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="37d0c-112">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-112">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="37d0c-113">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-113">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-114">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-114">Transaction to associate this operation with.</span></span></param>
        <param name="item"><span data-ttu-id="37d0c-115">Das Objekt, das das Ende der Warteschlange hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="37d0c-115">The object to add to the end of the queue.</span></span> <span data-ttu-id="37d0c-116">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="37d0c-116">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-117">Fügt ein Objekt am Ende der zuverlässige Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="37d0c-117">Adds an object to the end of the reliable queue.</span></span>
            </summary>
        <returns><span data-ttu-id="37d0c-118">Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-118">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks><span data-ttu-id="37d0c-119">Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="37d0c-119">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-120"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-120"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-121">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-121">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="37d0c-122">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-122">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-123">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-123">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-124">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-124">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-125">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-125">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-126">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-126">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-127">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-127">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-128">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-128">Transaction to associate this operation with.</span></span></param>
        <param name="item"><span data-ttu-id="37d0c-129">Das Objekt, das das Ende der Warteschlange hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="37d0c-129">The object to add to the end of the queue.</span></span> <span data-ttu-id="37d0c-130">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="37d0c-130">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="37d0c-131">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="37d0c-131">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="37d0c-132">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="37d0c-132">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="37d0c-133">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-133">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37d0c-134">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-134">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="37d0c-135">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="37d0c-135">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-136">Fügt ein Objekt am Ende der zuverlässige Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="37d0c-136">Adds an object to the end of the reliable queue.</span></span>
            </summary>
        <returns><span data-ttu-id="37d0c-137">Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-137">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks><span data-ttu-id="37d0c-138">Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="37d0c-138">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-139"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-139"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="37d0c-140"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="37d0c-140"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-141">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-141">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="37d0c-142">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-142">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="37d0c-143">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-143">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-144">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-144">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-145">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-145">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-146">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-146">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-147">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-147">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-148">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-148">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-149">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-149">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-150">Versucht, entfernen und das Objekt am Anfang der Warteschlange für zuverlässige zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="37d0c-150">Tries to remove and return the object at the beginning of the reliable queue.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-151">Aufgabe, die den asynchronen darstellt dequeue-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="37d0c-151">Task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="37d0c-152">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt entfernt wurde, und wenn dies der Fall ist, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-152">The task result is a tuple indicating whether an object was removed and if so, the object.</span></span>
            </returns>
        <remarks><span data-ttu-id="37d0c-153">Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="37d0c-153">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-154"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-154"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-155">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-155">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="37d0c-156">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-156">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-157">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-157">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-158">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-158">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-159">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-159">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-160">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-160">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-161">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-161">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-162">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-162">Transaction to associate this operation with.</span></span></param>
        <param name="timeout"><span data-ttu-id="37d0c-163">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="37d0c-163">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="37d0c-164">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="37d0c-164">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="37d0c-165">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-165">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37d0c-166">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-166">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="37d0c-167">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="37d0c-167">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-168">Versucht, entfernen und das Objekt am Anfang der Warteschlange für zuverlässige zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="37d0c-168">Tries to remove and return the object at the beginning of the reliable queue.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-169">Aufgabe, die den asynchronen darstellt dequeue-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="37d0c-169">Task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="37d0c-170">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt entfernt wurde, und wenn dies der Fall ist, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-170">The task result is a tuple indicating whether an object was removed and if so, the object.</span></span>
            </returns>
        <remarks><span data-ttu-id="37d0c-171">Wenn eine wiederholbar Ausnahme von dieser Methode ausgelöst wird, wird empfohlen, die Transaktion zu verwerfen <paramref name="tx" /> , und wiederholen Sie den Vorgang mit einer neuen Transaktion.</span><span class="sxs-lookup"><span data-stu-id="37d0c-171">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-172"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-172"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="37d0c-173"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="37d0c-173"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-174">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-174">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="37d0c-175">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-175">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="37d0c-176">Die Ausnahme ausgelöst, wenn ist die <cref name="IReliableQueue{T}" /> befindet sich nicht in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-176">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-177">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-177">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-178">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-178">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-179">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-179">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-180">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-180">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-181">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-181">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-182">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-182">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-183">Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-183">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-184">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-184">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="37d0c-185">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-185">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-186"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-186"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-187">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-187">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="37d0c-188">Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-188">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="37d0c-189"><cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="37d0c-189"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="37d0c-190">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-190">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="37d0c-191">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-191">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-192">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-192">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-193">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-193">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-194">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-194">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-195">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-195">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-196">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-196">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-197">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-197">Transaction to associate this operation with.</span></span></param>
        <param name="lockMode"><span data-ttu-id="37d0c-198">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="37d0c-198">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-199">Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-199">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-200">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-200">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="37d0c-201">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-201">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-202"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-202"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-203">Der Vorgang konnte nicht innerhalb des Standard-Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-203">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="37d0c-204">Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-204">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="37d0c-205"><cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="37d0c-205"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="37d0c-206">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-206">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="37d0c-207">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-207">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-208">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-208">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-209">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-209">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-210">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-210">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-211">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-211">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-212">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-212">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-213">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-213">Transaction to associate this operation with.</span></span></param>
        <param name="timeout"><span data-ttu-id="37d0c-214">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="37d0c-214">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="37d0c-215">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="37d0c-215">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="37d0c-216">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-216">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37d0c-217">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-217">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="37d0c-218">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="37d0c-218">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-219">Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-219">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-220">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-220">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="37d0c-221">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-221">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-222"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-222"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="37d0c-223"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="37d0c-223"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-224">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="37d0c-225">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-225">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="37d0c-226">Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-226">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="37d0c-227"><cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="37d0c-227"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="37d0c-228">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-228">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="37d0c-229">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-229">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-230">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-230">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-231">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-231">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-232">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-232">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-233">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-233">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-234">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-234">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
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
        <param name="tx"><span data-ttu-id="37d0c-235">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-235">Transaction to associate this operation with.</span></span></param>
        <param name="lockMode"><span data-ttu-id="37d0c-236">Typ der Sperre für die Verwendung für diese Lesevorgang.</span><span class="sxs-lookup"><span data-stu-id="37d0c-236">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="37d0c-237">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="37d0c-237">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="37d0c-238">In erster Linie verwendet, um Deadlocks zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="37d0c-238">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="37d0c-239">Der Standardwert ist 4 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-239">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="37d0c-240">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-240">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="37d0c-241">Der Standardwert ist „None“.</span><span class="sxs-lookup"><span data-stu-id="37d0c-241">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="37d0c-242">Versucht, ein Objekt vom Anfang der Warteschlange für zuverlässige zurückzugeben, ohne es zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-242">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="37d0c-243">Eine Aufgabe, die den asynchronen Lesevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-243">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="37d0c-244">Das Ergebnis der Aufgabe ist ein Tupel, der angibt, ob ein Objekt am Anfang der Warteschlangenobjekts gefunden wurde, und wenn Ja, das Objekt.</span><span class="sxs-lookup"><span data-stu-id="37d0c-244">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="37d0c-245"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="37d0c-245"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="37d0c-246"><paramref name="timeout" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="37d0c-246"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="37d0c-247">Der Vorgang konnte nicht innerhalb des angegebenen Timeouts abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-247">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="37d0c-248">Der Vorgang wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-248">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="37d0c-249">Ausnahme gibt an, dass die <cref name="IReliableQueue{T}" /> Lesevorgänge im Moment kann nicht verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="37d0c-249">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="37d0c-250"><cref name="FabricNotReadableException" />ausgelöst werden kann, in allen <cref name="ReplicaRole" />s.</span><span class="sxs-lookup"><span data-stu-id="37d0c-250"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="37d0c-251">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.Primary" /> ist der Verlust der <cref name="IStatefulServicePartition.ReadStatus" />.</span><span class="sxs-lookup"><span data-stu-id="37d0c-251">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="37d0c-252">Ein Beispiel dafür ausgelöst wird, der <cref name="ReplicaRole.ActiveSecondary" /> ist, dass zuverlässige Warteschlangenstatus noch nicht konsistent ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-252">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="37d0c-253">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-253">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="37d0c-254">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="37d0c-254">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="37d0c-255">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-255">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="37d0c-256">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="37d0c-256">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="37d0c-257">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="37d0c-257">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>