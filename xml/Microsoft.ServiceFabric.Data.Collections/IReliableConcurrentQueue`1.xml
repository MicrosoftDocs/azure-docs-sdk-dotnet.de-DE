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
            <span data-ttu-id="6dcb5-101">Der Typ der Werte in der slim zuverlässige Warteschlange enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-101">The type of the values contained in the reliable queue slim.</span></span>
            </typeparam>
    <summary>
      <para>
            <span data-ttu-id="6dcb5-102">Stellt eine zuverlässige Auflistung erhalten bleibt, replizierten Werte mit Best-Effort-FIFO-Reihenfolge zu sortieren.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-102">Represents a reliable collection of persisted, replicated values with best-effort first-in first-out ordering.</span></span>
            </para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="6dcb5-103">Als Alternative zur vorgesehen <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> für arbeitsauslastungen, in denen strenge Sortierung nicht erforderlich ist, als durch lockern die Reihenfolge Einschränkung Parallelität kann erheblich verbessert werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-103">Intended as an alternative to <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> for workloads where strict ordering is not required, as by relaxing the ordering constraint, concurrency can be greatly improved.</span></span>  <span data-ttu-id="6dcb5-104"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />gleichzeitige Consumer und Producer beschränkt, auf ein Maximum von einem einzelnen, während <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> erzwingt diese Einschränkung nicht.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-104"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> restricts concurrent consumers and producers to a maximum of one each, while <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> imposes no such restriction.</span></span>
            </para>
      <para>
        <span data-ttu-id="6dcb5-105"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />bietet die gleiche Transaktion Isolationssemantik als die zuverlässige Datenstrukturen nicht.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-105"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not offer the same transaction isolation semantics as the other reliable data structures.</span></span>  <span data-ttu-id="6dcb5-106">Finden Sie die einzelnen Vorgänge und die Eigenschaften (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> und <see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) für Details dazu, welche Isolation, sofern vorhanden, sie bieten.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-106">See the individual operations and properties (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> and <see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) for details on what isolation, if any, they provide.</span></span>
            </para>
      <para>
            <span data-ttu-id="6dcb5-107">Es wird erwartet, dass Werte in der Warteschlange relativ kurzlebig sind; Anders gesagt, ausgehenden (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) zu rechnen ist gleich oder größer als die eingehend (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) Rate.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-107">It is expected that values will be relatively short-lived in the queue; in other words, that the egress (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) rate is equal to or greater than the ingress (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) rate.</span></span>  <span data-ttu-id="6dcb5-108">Diese Vorgabe verletzen kann die Systemleistung verschlechtern.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-108">Violating this expectation may worsen system performance.</span></span>  <span data-ttu-id="6dcb5-109">Eine Einschränkung der geplanten Warteschlange-Kapazität, die eingehende reiht Drosselung wird, sobald die Kapazität erreicht ist, hilft dabei, die diese Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-109">A planned queue capacity constraint which will throttle incoming Enqueues once the capacity is reached will help in maintaining this property.</span></span>
            <span data-ttu-id="6dcb5-110">-Eigenschaft veranschaulicht.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-110">property.</span></span>
            </para>
      <para>
            <span data-ttu-id="6dcb5-111">Wie die Reihenfolge der Elemente nicht unbedingt gewährleistet ist, Annahmen über die Reihenfolge der zwei beliebige Werte in der Warteschlange darf nicht hergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-111">As the ordering of elements is not strictly guaranteed, assumptions about the ordering of any two values in the queue MUST NOT be made.</span></span>  <span data-ttu-id="6dcb5-112">Die Reihenfolge der Best-Effort-FIFO-Reihenfolge ist für Ausgewogenheit bereitgestellt wird. die Zeit, die ein Wert in der Warteschlange verbringt sollte verknüpft sein, um die Fehlerrate (Fehler können der Warteschlange Sortierung alter) und den Dequeue-Rate, aber nicht die Rate der in die Warteschlange einzureihen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-112">The best-effort first-in first-out ordering is provided for fairness; the time that an value spends in the queue should be related to the failure rate (failures may alter the queue's ordering) and the dequeue rate, but not the enqueue rate.</span></span>
            </para>
      <para>
        <span data-ttu-id="6dcb5-113"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />bieten einen Lesevorgang, nicht jedoch durch Kombinieren von <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> und <see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" /> identisch semantische erreicht werden kann.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-113"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not offer a Peek operation, however by combining <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> and <see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" /> the same semantic can be achieved.</span></span>  <span data-ttu-id="6dcb5-114">Finden Sie unter <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Weitere Informationen und ein Beispiel.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-114">See <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> for additional details and an example.</span></span>
            </para>
      <para>
            <span data-ttu-id="6dcb5-115">In dieser Warteschlange darf keinen gespeicherte Werten werden geändert, außerhalb des Kontexts eines Vorgangs in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-115">Values stored in this queue MUST NOT be mutated outside the context of an operation on the queue.</span></span> <span data-ttu-id="6dcb5-116">Es wird dringend empfohlen, stellen <typeparamref name="T" /> unveränderlich, um versehentliche Datenverluste zu vermeiden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-116">It is highly recommended to make <typeparamref name="T" /> immutable in order to avoid accidental data corruption.</span></span>
            </para>
      <para>
            <span data-ttu-id="6dcb5-117">Transaktion ist die Einheit der Parallelität: Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden jeweils einzeln.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-117">Transaction is the unit of concurrency: Users can have multiple transactions in-flight at any given point of time but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="6dcb5-118">Daher sind alle zuverlässige Auflistung-APIs, die in einer Transaktion annehmen und eine Aufgabe zurückgeben muss erwartete einzeln nacheinander.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-118">So all Reliable Collection APIs that take in a transaction and return a Task, must be awaited one at a time.</span></span>
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
             <span data-ttu-id="6dcb5-119">Ruft die Anzahl der Werte in der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-119">Gets the number of values in the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span></span>
             </para>
        </summary>
        <value><span data-ttu-id="6dcb5-120">Die Anzahl der Werte in der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-120">The number of values in  the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span></span></value>
        <remarks>
          <para>
             <span data-ttu-id="6dcb5-121">Diese Zahl stellt die Anzahl der Werte, die derzeit für sichtbar <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-121">This count represents the number of values currently visible to <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />.</span></span>  <span data-ttu-id="6dcb5-122">UNCOMMITTED reiht wird nicht die Anzahl erhöhen, jedoch ohne Commit Dequeues die Anzahl verringert.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-122">Uncommitted Enqueues will not increase the count, however uncommitted Dequeues will decrease the count.</span></span>
             </para>
          <para>
             <span data-ttu-id="6dcb5-123">Beachten Sie, dass diese API nicht mit einem Transaktionsparameter übernimmt.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-123">Note that this API does not take a transaction parameter.</span></span>  <span data-ttu-id="6dcb5-124">Seit der Auswirkungen der <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> werden nicht von anderen Transaktionen isoliert, die die Anzahl auch darf nicht von anderen Transaktionen isoliert.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-124">Since the effects of <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> are not isolated from other transactions, the count also cannot be isolated from other transactions.</span></span>  
             </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="6dcb5-125">Das Replikat ist derzeit nicht lesbar.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-125">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6dcb5-126">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-126">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <example>
             <span data-ttu-id="6dcb5-127">Dieses Beispiel zeigt die Anzahl der Warteschlangen überwachen unbegrenzt, bis das Abbruchtoken abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-127">This example shows how to monitor the queue's count infinitely, until the cancellation token is canceled.</span></span>
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
        <param name="tx"><span data-ttu-id="6dcb5-128">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-128">Transaction to associate this operation with.</span></span></param>
        <param name="value"><span data-ttu-id="6dcb5-129">Der Wert am Ende der Warteschlange hinzu.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-129">The value to add to the end of the queue.</span></span> <span data-ttu-id="6dcb5-130">Der Wert kann für Verweistypen NULL sein.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-130">The value can be null for reference types.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6dcb5-131">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-131">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6dcb5-132">Der Standardwert lautet <see cref="P:System.Threading.CancellationToken.None" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-132">The default is <see cref="P:System.Threading.CancellationToken.None" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="6dcb5-133">Die Zeitspanne zu warten, bis der Vorgang abgeschlossen ist, bevor eine TimeoutException ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-133">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="6dcb5-134">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-134">The default is null.</span></span>  <span data-ttu-id="6dcb5-135">Wenn Null übergeben wird, wird ein Standardtimeout verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-135">If null is passed, a default timeout will be used.</span></span></param>
        <summary>
          <para>
             <span data-ttu-id="6dcb5-136">Phase der eines Werts in die Warteschlange einreihen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-136">Stage the enqueue of a value into the queue.</span></span>
             </para>
        </summary>
        <returns><span data-ttu-id="6dcb5-137">Eine Aufgabe, die den asynchronen Enqueue-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-137">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks>
             <span data-ttu-id="6dcb5-138">Ein <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgang kann keiner Wert zurück, für die die <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> noch kein Commit ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-138">A <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operation cannot return any value for which its <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> has not yet been committed.</span></span>
             <span data-ttu-id="6dcb5-139">Dies schließt die Transaktion, in der der Wert in die Warteschlange eingereiht wurde; Daher <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> Your-Lese-nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-139">This includes the transaction in which the value was enqueued; as a consequence, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not support Read-Your-Writes.</span></span>
             </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6dcb5-140">Das Replikat ist nicht mehr in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-140">The replica is no longer in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="6dcb5-141">Das Replikat ist derzeit nicht lesbar.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-141">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6dcb5-142">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-142">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <exception cref="T:System.Fabric.FabricTransientException"><span data-ttu-id="6dcb5-143">Das Replikat gesehen haben, um einen vorübergehenden Fehler.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-143">The replica saw a transient failure.</span></span> <span data-ttu-id="6dcb5-144">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="6dcb5-144">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="6dcb5-145">Das Replikat wurde einen anderer oben definierten Typen nicht wiederholbar Fehler erläutert.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-145">The replica saw a non retriable failure other than the types defined above.</span></span> <span data-ttu-id="6dcb5-146">Die Bereinigung und Rethrow-Ausnahme</span><span class="sxs-lookup"><span data-stu-id="6dcb5-146">Cleanup and rethrow the exception</span></span></exception>
        <exception cref="T:System.TimeoutException">
             <span data-ttu-id="6dcb5-147">Der Vorgang konnte nicht innerhalb des angegebenen Zeitlimits abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-147">The operation was unable to be completed within the given timeout.</span></span>  <span data-ttu-id="6dcb5-148">Die Transaktion abgebrochen werden soll, und eine neue Transaktion erstellt werden soll, um erneut zu versuchen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-148">The transaction should be aborted and a new transaction should be created to retry.</span></span>
             </exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6dcb5-149"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-149"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6dcb5-150">Der Vorgang wurde abgebrochen, über <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-150">The operation was canceled via <paramref name="cancellationToken" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6dcb5-151">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-151">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6dcb5-152">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="6dcb5-152">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
             <span data-ttu-id="6dcb5-153">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-153">Thrown when a method call is invalid for the object's current state.</span></span>
             <span data-ttu-id="6dcb5-154">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-154">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
             <span data-ttu-id="6dcb5-155">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-155">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
             </exception>
        <example>
             <span data-ttu-id="6dcb5-156">Dieses Beispiel zeigt, wie <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> in die Warteschlange einzureihende Wert mit Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-156">This example shows how to use <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> to enqueue a value with retry.</span></span>
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
        <param name="tx"><span data-ttu-id="6dcb5-157">Transaktion, die diesen Vorgang zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-157">Transaction to associate this operation with.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6dcb5-158">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-158">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="6dcb5-159">Der Standardwert lautet <see cref="P:System.Threading.CancellationToken.None" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-159">The default is <see cref="P:System.Threading.CancellationToken.None" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="6dcb5-160">Die Zeitspanne zum Abschließen des Vorgangs warten.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-160">The amount of time to wait for the operation to complete.</span></span> <span data-ttu-id="6dcb5-161">Der Standardwert ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-161">The default is null.</span></span>  <span data-ttu-id="6dcb5-162">Wenn Null übergeben wird, wird ein Standardtimeout verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-162">If null is passed, a default timeout will be used.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="6dcb5-163">Mit Vorbehalt dequeue einen Wert aus der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-163">Tentatively dequeue a value from the queue.</span></span> <span data-ttu-id="6dcb5-164">Wenn die Warteschlange leer ist, wartet der Dequeue-Vorgang für ein Element zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-164">If the queue is empty, the dequeue operation will wait for an item to become available.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="6dcb5-165">Eine Aufgabe, die den asynchronen stellt dequeue-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-165">A task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="6dcb5-166">Das Ergebnis ist eine ConditionalValue vom Typ t Wenn Sie ein Wert innerhalb der angegebenen Zeit aus der Warteschlange entfernt wurde, Zurückgeben einer ConditionalValue mit HasValue als "false", ansonsten Längenwert ein ConditionalValue bei HasValue als "true" und Wert wie das Element aus der Warteschlange entfernt, der Typ T</span><span class="sxs-lookup"><span data-stu-id="6dcb5-166">The task's result is a ConditionalValue of type T. If a value was dequeued within the given time, return a ConditionalValue with HasValue as false, else it returns a ConditionalValue with HasValue as true and the Value as the dequeued item of Type T</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="6dcb5-167">Während <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> nur Werte zurückgeben, für die entsprechenden <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> wurde ein Commit ausgeführt wurde, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgänge sind nicht voneinander isoliert.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-167">While <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> can only return values for which the corresponding <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> was committed, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operations are not isolated from one another.</span></span>  <span data-ttu-id="6dcb5-168">Sobald eine Transaktion einen Wert aus der Warteschlange entfernt wurde, werden andere Transaktionen können nicht aus der Warteschlange entfernt, jedoch nicht aus anderen Werten daraus entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-168">Once a transaction has dequeued a value, other transactions cannot dequeue it, but are not blocked from dequeuing other values.</span></span>
            </para>
          <para>
            <span data-ttu-id="6dcb5-169">Wenn eine Transaktion oder Transaktionen, die eine oder mehrere einschließlich <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Vorgänge wird abgebrochen, die Werte aus der Warteschlange entfernt werden wieder am Anfang der Warteschlange in einer beliebigen Reihenfolge hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-169">When a transaction or transactions including one or more <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operations aborts, the dequeued values will be added back at the head of the queue in an arbitrary order.</span></span>  <span data-ttu-id="6dcb5-170">Dadurch wird sichergestellt, dass diese Werte bald wieder vorbei, aus der Warteschlange werden die Fairness der Datenstruktur, jedoch entfernt werden ohne strenge Sortierung Durchsetzung verbessern (was erfordern würde, reduzieren die zulässige Parallelität als in <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />).</span><span class="sxs-lookup"><span data-stu-id="6dcb5-170">This will ensure that these values will be dequeued again soon, improving the fairness of the data structure, but without enforcing strict ordering (which would require reducing the allowed concurrency, as in <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />).</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="6dcb5-171">Das Replikat ist nicht mehr in <cref name="ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-171">The replica is no longer in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="6dcb5-172">Das Replikat ist derzeit nicht lesbar.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-172">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="6dcb5-173">Die <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> , die von der Laufzeit geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-173">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <exception cref="T:System.Fabric.FabricTransientException"><span data-ttu-id="6dcb5-174">Das Replikat gesehen haben, um einen vorübergehenden Fehler.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-174">The replica saw a transient failure.</span></span> <span data-ttu-id="6dcb5-175">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="6dcb5-175">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="6dcb5-176">Das Replikat wurde einen anderer oben definierten Typen nicht wiederholbar Fehler erläutert.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-176">The replica saw a non retriable failure other than the types defined above.</span></span> <span data-ttu-id="6dcb5-177">Die Bereinigung und Rethrow-Ausnahme</span><span class="sxs-lookup"><span data-stu-id="6dcb5-177">Cleanup and rethrow the exception</span></span></exception>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="6dcb5-178">Der Vorgang konnte nicht innerhalb des angegebenen Zeitlimits abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-178">The operation was unable to be completed within the given timeout.</span></span>  <span data-ttu-id="6dcb5-179">Die Transaktion abgebrochen werden soll, und eine neue Transaktion erstellt werden soll, um erneut zu versuchen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-179">The transaction should be aborted and a new transaction should be created to retry.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="6dcb5-180"><paramref name="tx" /> ist NULL.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-180"><paramref name="tx" /> is null.</span></span> <span data-ttu-id="6dcb5-181">Diese Ausnahme nicht behandelt.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-181">Do not handle this exception.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="6dcb5-182">Der Vorgang wurde abgebrochen, über <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-182">The operation was canceled via <paramref name="cancellationToken" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="6dcb5-183">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-183">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="6dcb5-184">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="6dcb5-184">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6dcb5-185">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-185">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="6dcb5-186">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-186">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="6dcb5-187">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-187">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <example>
            <span data-ttu-id="6dcb5-188">Dieses Beispiel zeigt, wie Sie aus der Warteschlange entfernen und melden Sie sich unbegrenzt wiederholen, bis das Abbruchtoken abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="6dcb5-188">This example shows how to dequeue and log infinitely with retry, until the cancellation token is canceled.</span></span>  
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