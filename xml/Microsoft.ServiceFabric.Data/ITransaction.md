<Type Name="ITransaction" FullName="Microsoft.ServiceFabric.Data.ITransaction">
  <TypeSignature Language="C#" Value="public interface ITransaction : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransaction implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ITransaction" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransaction&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITransaction = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="0dd90-101">Eine Sequenz von Vorgängen werden als einzelne logische Arbeitseinheit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="0dd90-101">A sequence of operations performed as a single logical unit of work.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="0dd90-102">Eine Transaktion muss die folgenden ACID-Eigenschaften aufweisen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-102">A transaction must exhibit the following ACID properties.</span></span> <span data-ttu-id="0dd90-103">(finden Sie unter: https://technet.microsoft.com/en-us/library/ms190612) <list type="bullet"> <item> <description> Unteilbarkeit - in eine Transaktion muss eine unteilbare Arbeitseinheit; entweder werden alle vorgesehenen datenänderungen ausgeführt oder keine von ihnen ausgeführt wird. </description></item><item><description>Konsistenz - muss nach Abschluss eine Transaktion alle Daten in einem konsistenten Zustand lassen. Alle internen Datenstrukturen müssen am Ende der Transaktion korrekt sein. </description></item><item><description>Isolation - Änderungen, die von gleichzeitigen Transaktionen müssen von den Änderungen, die von anderen gleichzeitigen Transaktionen isoliert sein. Die Isolationsstufe für einen Vorgang in einem <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> richtet sich nach der <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> Ausführen des Vorgangs. </description></item><item><description>Dauerhaftigkeit - nach dem Abschluss einer Transaktions sind ihre Auswirkungen dauerhaft im System. Die Änderungen bleiben sogar auch bei Systemausfällen erhalten. </description></item></list><para>Beliebiger Instanzmember dieses Typs wird nicht unbedingt threadsicher sein. Dies macht Transaktionen auf die Einheit der Parallelität: Benutzer können mehrere Transaktionen, die in-Flight zu einem bestimmten Zeitpunkt Zeit haben, aber für eine bestimmte Transaktion jedes-API muss aufgerufen werden einzeln an. Alle <see cref="T:IReliableCollection{T}" /> APIs, annehmen, eine Transaktion und der Rückgabewert eine Aufgabe muss, erwartet einzeln nacheinander. </para><para>Es folgt ein Beispiel für eine richtige Verwendung.</span><span class="sxs-lookup"><span data-stu-id="0dd90-103">(see: https://technet.microsoft.com/en-us/library/ms190612) <list type="bullet"><item><description> Atomicity - A transaction must be an atomic unit of work; either all of its data modifications are performed, or none of them is performed. </description></item><item><description> Consistency - When completed, a transaction must leave all data in a consistent state. All internal data structures must be correct at the end of the transaction. </description></item><item><description> Isolation - Modifications made by concurrent transactions must be isolated from the modifications made by any other concurrent transactions. The isolation level used for an operation within an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> is determined by the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> performing the operation. </description></item><item><description> Durability - After a transaction has completed, its effects are permanently in place in the system. The modifications persist even in the event of a system failure. </description></item></list><para> Any instance member of this type is not guaranteed to be thread safe. This makes transactions the unit of concurrency: Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time. All <see cref="T:IReliableCollection{T}" /> APIs that accept a transaction and return a Task must be awaited one at a time. </para><para> Following is an example of a correct usage.</span></span>
             <span data-ttu-id="0dd90-104"><code><![CDATA[
                         
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
                         
                         // Delay and retry.
                         await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                     }
                     ]]></code></para><para>Im folgenden ist ein Beispiel für falsche Verwendung, die Verhalten nicht definiert wurde.</span><span class="sxs-lookup"><span data-stu-id="0dd90-104"><code><![CDATA[
                     
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

// Delay and retry.
await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
}
]]></code></para><para> The following is an example of incorrect usage that has undefined behavior.</span></span>
<code><![CDATA[
using (var txn = this.StateManager.CreateTransaction())
{
List<Task> taskList = new List<Task>();
taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));
taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));

await Task.WhenAll(taskList);
await txn.CommitAsync();
}
]]></code></para></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iTransaction.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0dd90-105">Abbruch Rollback () der Transaktion.</span><span class="sxs-lookup"><span data-stu-id="0dd90-105">Abort (rolls back) the transaction.</span></span>
            </summary>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="0dd90-106">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-106">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="0dd90-107">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="0dd90-107">Retry the operation on a new transaction</span></span></exception>
          <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="0dd90-108">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-108">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="0dd90-109">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-109">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="0dd90-110">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-110">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
          <exception cref="T:System.Fabric.FabricNotPrimaryException">
            <span data-ttu-id="0dd90-111">Die Transaktion umfasst Updates für <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:System.Fabric.ReplicaRole" /> hat nicht die primäre.</span><span class="sxs-lookup"><span data-stu-id="0dd90-111">The transaction includes updates to <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and the <see cref="T:System.Fabric.ReplicaRole" /> is not Primary.</span></span>
            <span data-ttu-id="0dd90-112">Nur primäre Replikate Schreibstatus erhalten.</span><span class="sxs-lookup"><span data-stu-id="0dd90-112">Only Primary replicas are given write status.</span></span>
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CommitAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.CommitAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CommitAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CommitAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iTransaction.CommitAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0dd90-113">Commit für die Transaktion aus.</span><span class="sxs-lookup"><span data-stu-id="0dd90-113">Commit the transaction.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0dd90-114">Eine Aufgabe, die den asynchronen Commitvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="0dd90-114">A task that represents the asynchronous commit operation.</span></span> 
            </returns>
        <remarks>
            <span data-ttu-id="0dd90-115">Eine Transaktion kann nicht abgebrochen werden, nachdem sie ein Commit ausgeführt wurde, da alle Änderungen persistent gespeichert und repliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="0dd90-115">You cannot abort a transaction once it has been committed, because all modifications have been persisted and replicated.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="0dd90-116">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-116">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="0dd90-117">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="0dd90-117">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="0dd90-118">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-118">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="0dd90-119">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-119">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="0dd90-120">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-120">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
            <span data-ttu-id="0dd90-121">Die Transaktion umfasst Updates für <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> und <see cref="T:System.Fabric.ReplicaRole" /> hat nicht die primäre.</span><span class="sxs-lookup"><span data-stu-id="0dd90-121">The transaction includes updates to <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and the <see cref="T:System.Fabric.ReplicaRole" /> is not Primary.</span></span>
            <span data-ttu-id="0dd90-122">Nur primäre Replikate Schreibstatus erhalten.</span><span class="sxs-lookup"><span data-stu-id="0dd90-122">Only Primary replicas are given write status.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CommitSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommitSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommitSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommitSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommitSequenceNumber : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
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
            <span data-ttu-id="0dd90-123">Die Sequenznummer für den Commitvorgang.</span><span class="sxs-lookup"><span data-stu-id="0dd90-123">Sequence number for the commit operation.</span></span>
            </summary>
        <value>
            <span data-ttu-id="0dd90-124">Die Sequenznummer, an dem die Transaktion ein Commit ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="0dd90-124">The sequence number at which the the transaction was committed.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVisibilitySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetVisibilitySequenceNumberAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetVisibilitySequenceNumberAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.GetVisibilitySequenceNumberAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVisibilitySequenceNumberAsync () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetVisibilitySequenceNumberAsync : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iTransaction.GetVisibilitySequenceNumberAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0dd90-125">Ruft die Sichtbarkeit Sequenznummer ab.</span><span class="sxs-lookup"><span data-stu-id="0dd90-125">Gets the visibility sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="0dd90-126">Die Sequenznummer der Sichtbarkeit.</span><span class="sxs-lookup"><span data-stu-id="0dd90-126">The visibility sequence number.</span></span></returns>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="0dd90-127">Die Transaktion wurde vom System intern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-127">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="0dd90-128">Wiederholen Sie den Vorgang einer neuen Transaktion</span><span class="sxs-lookup"><span data-stu-id="0dd90-128">Retry the operation on a new transaction</span></span></exception>
          <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="0dd90-129">Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-129">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="0dd90-130">Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="0dd90-130">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="0dd90-131">Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="0dd90-131">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionId">
      <MemberSignature Language="C#" Value="public long TransactionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransactionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransactionId As Long" />
      <MemberSignature Language="F#" Value="member this.TransactionId : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
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
            <span data-ttu-id="0dd90-132">Ruft einen Wert, der die Transaktion identifiziert.</span><span class="sxs-lookup"><span data-stu-id="0dd90-132">Gets a value identifying the transaction.</span></span>
            </summary>
        <value><span data-ttu-id="0dd90-133">Die Transaktions-Id.</span><span class="sxs-lookup"><span data-stu-id="0dd90-133">The transaction id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>