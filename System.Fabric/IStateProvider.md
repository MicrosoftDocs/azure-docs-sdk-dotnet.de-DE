<Type Name="IStateProvider" FullName="System.Fabric.IStateProvider">
  <TypeSignature Language="C#" Value="public interface IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProvider" />
  <TypeSignature Language="F#" Value="type IStateProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="7797e-101">Definiert das Verhalten, das ein Dienst implementieren muss, um die Interaktion mit der <see cref="T:System.Fabric.FabricReplicator" />.</span><span class="sxs-lookup"><span data-stu-id="7797e-101">Defines the behavior that a service must implement to interact with the <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyContext">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyContext () As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyContext : unit -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7797e-102">Kontext auf einem sekundären Replikat erhält, nachdem es erstellt und geöffnet, um den Kontext mit dem primären Replikat zu senden.</span><span class="sxs-lookup"><span data-stu-id="7797e-102">Obtains context on a secondary replica after it is created and opened to send context to the primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7797e-103">Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7797e-103">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7797e-104">Das primäre Replikat analysiert den Kontext und zurücksendet Status über <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span><span class="sxs-lookup"><span data-stu-id="7797e-104">The primary replica analyzes the context and sends back state via <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span></para>
          <para>
            <span data-ttu-id="7797e-105"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" />wird aufgerufen, auf neu erstellt werden, inaktive sekundäre Replikate und bietet einen Mechanismus zum asynchron eine bidirektionale Konversation mit dem primären Replikat hergestellt.</span><span class="sxs-lookup"><span data-stu-id="7797e-105"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> is called on newly created, idle secondary replicas and provides a mechanism to asynchronously establish a bidirectional conversation with the primary replica.</span></span> <span data-ttu-id="7797e-106">Das sekundäre Replikat sendet <see cref="T:System.Fabric.OperationData" /> Objekte, die mit dem das primäre Replikat den Status des Sammelns von Kontext auf dem sekundären Replikat bestimmen kann.</span><span class="sxs-lookup"><span data-stu-id="7797e-106">The secondary replica sends <see cref="T:System.Fabric.OperationData" /> objects with which the primary replica can determine the progress of collecting context on the secondary replica.</span></span> <span data-ttu-id="7797e-107">Das primäre Replikat sendet seinerseits den erforderlichen Zustand zurück.</span><span class="sxs-lookup"><span data-stu-id="7797e-107">The primary replica responds by sending the required state back.</span></span>
                <span data-ttu-id="7797e-108">Finden Sie unter <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> an das primäre Replikat für die andere Hälfte des Austausches.</span><span class="sxs-lookup"><span data-stu-id="7797e-108">See <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> at the primary replica for the other half of the exchange.</span></span> </para>
          <para><span data-ttu-id="7797e-109">Für InMemory-Dienste die <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode wird nicht aufgerufen, da der Status der sekundären Replikate bekannt ist (sie sind leer und benötigen alle Status).</span><span class="sxs-lookup"><span data-stu-id="7797e-109">For in-memory services, the <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method is not called, as the state of the secondary replicas is known (they are empty and will require all of the state).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCopyState">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyState : int64 * System.Fabric.IOperationDataStream -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyState (upToSequenceNumber, copyContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.NamingRules", "SA1305:FieldNamesMustNotUseHungarianNotation", Justification="Not Hungarian notation.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para><span data-ttu-id="7797e-110">Die maximale letzte Sequenznummer, die in den Stream kopieren über eingefügt werden soll die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="7797e-110">The maximum last sequence number that should be placed in the copy stream via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method.</span></span>
            <span data-ttu-id="7797e-111">LSNs, die größer als diese Zahl werden an das sekundäre Replikat als Teil der replikationsdatenstrom über übermittelt die <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="7797e-111">LSNs greater than this number are delivered to the secondary replica as a part of the replication stream via the <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> method.</span></span></para>
        </param>
        <param name="copyContext">
          <para><span data-ttu-id="7797e-112">Ein <see cref="T:System.Fabric.IOperationDataStream" /> , enthält die <see cref="T:System.Fabric.OperationData" /> Objekte, die vom sekundären Replikat erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="7797e-112">An <see cref="T:System.Fabric.IOperationDataStream" /> that contains the <see cref="T:System.Fabric.OperationData" /> objects that are created by the secondary replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="7797e-113">Ruft die Status für ein primäres Replikat, das erforderlich sind, um ein sekundäres Replikat zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7797e-113">Obtains state on a primary replica that is required to build a secondary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7797e-114">Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7797e-114">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7797e-115">Ebenso wie <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> ermöglicht das sekundäre Replikat das primäre Replikat über Kontext an ein <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> ermöglicht das primäre Replikat antwortet ein <see cref="T:System.Fabric.IOperationDataStream" />.</span><span class="sxs-lookup"><span data-stu-id="7797e-115">Just as <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> enables the secondary replica to send context to the primary replica via an <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> enables the primary replica to respond with an <see cref="T:System.Fabric.IOperationDataStream" />.</span></span> <span data-ttu-id="7797e-116">Der Datenstrom enthält Objekte, die an das sekundäre Replikat über übermittelt werden die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode der <see cref="T:System.Fabric.FabricReplicator" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="7797e-116">The stream contains objects that are delivered to the secondary replica via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method of the <see cref="T:System.Fabric.FabricReplicator" /> class.</span></span> <span data-ttu-id="7797e-117">Implementieren Sie die Objekte <see cref="T:System.Fabric.IOperation" /> und die angegebenen Daten enthalten.</span><span class="sxs-lookup"><span data-stu-id="7797e-117">The objects implement <see cref="T:System.Fabric.IOperation" /> and contain the specified data.</span></span> </para>
          <para> <span data-ttu-id="7797e-118">Wenn das primäre Replikat dieser Aufruf empfängt, sollte er erstellen und Zurückgeben einer anderen <see cref="T:System.Fabric.IOperationDataStream" /> enthält <see cref="T:System.Fabric.OperationData" />.</span><span class="sxs-lookup"><span data-stu-id="7797e-118">When the primary replica receives this call, it should create and return another <see cref="T:System.Fabric.IOperationDataStream" /> that contains <see cref="T:System.Fabric.OperationData" />.</span></span> <span data-ttu-id="7797e-119"><see cref="T:System.Fabric.OperationData" />Stellt dar, die das sekundäre Replikat benötigt wird, um den aktuellen Stand zu bereitgestellten Daten/Status <paramref name="upToSequenceNumber" /> maximale LSN.</span><span class="sxs-lookup"><span data-stu-id="7797e-119"><see cref="T:System.Fabric.OperationData" /> represents the data/state that the secondary replica requires to catch up to the provided <paramref name="upToSequenceNumber" /> maximum LSN.</span></span> <span data-ttu-id="7797e-120">Wie viel und welchen Status hat, Versand kann bestimmt werden, über die Kontextinformationen, die das sekundäre Replikat über bereitstellt <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="7797e-120">How much and which state has to be sent can be determined via the context information that the secondary replica provides via <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastCommittedSequenceNumber () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetLastCommittedSequenceNumber : unit -&gt; int64" Usage="iStateProvider.GetLastCommittedSequenceNumber " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7797e-121">Ruft die letzte Sequenznummer, die der Dienst ein Commit ausgeführt wurde, auch bekannt als logische-Sequenz-Anzahl (LSN).</span><span class="sxs-lookup"><span data-stu-id="7797e-121">Obtains the last sequence number that the service has committed, also known as Logical Sequence Number (LSN).</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7797e-122">Gibt die letzte Sequenznummer für ein Commit ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="7797e-122">Returns the last committed sequence number.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iStateProvider.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="7797e-123">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7797e-123">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="7797e-124">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7797e-124">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="7797e-125">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="7797e-125">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7797e-126">Gibt an, dass ein schreibquorums Replikate in dieser Replikatsatz verloren gegangen ist und daher Datenverlust aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="7797e-126">Indicates that a write quorum of replicas in this replica set has been lost, and that therefore data loss might have occurred.</span></span> <span data-ttu-id="7797e-127">Die Replikatgruppe besteht aus der Mehrheit der Replikate, die das primäre Replikat enthält.</span><span class="sxs-lookup"><span data-stu-id="7797e-127">The replica set consists of a majority of replicas, which includes the primary replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7797e-128">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.Boolean" />, Wert, der angibt, ob die State-Anbieter als Teil der Verarbeitung dieser benachrichtigungs seinen Status geändert wurde</span><span class="sxs-lookup"><span data-stu-id="7797e-128">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Boolean" />, that indicates whether the state provider as part of processing this notification has changed its state</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7797e-129">Wenn die Service Fabric-Laufzeit einen Fehler des ein Quorum der Replikate, der das primäre Replikat enthält berücksichtigt, wählt ein neues primäres Replikat und sofort ruft diese Methode auf dem neuen primären Replikat.</span><span class="sxs-lookup"><span data-stu-id="7797e-129">When the Service Fabric runtime observes the failure of a quorum of replicas, which includes the primary replica, it elects a new primary replica and immediately calls this method on the new primary replica.</span></span> <span data-ttu-id="7797e-130">Ein primäres Replikat, das eines möglichen Datenverlusts informiert ist die Möglichkeit, den Zustand aus einer externen Datenquelle wiederherstellen oder kann weiterhin mit dem Status ausgeführt wird, die derzeit.</span><span class="sxs-lookup"><span data-stu-id="7797e-130">A primary replica that is informed of possible data loss can choose to restore its state from some external data source or can continue to run with the state that it currently has.</span></span> <span data-ttu-id="7797e-131">Wenn der Dienst mit seinem aktuellen Zustand ausgeführt werden weiterhin, sollte es "false" von dieser Methode zurückgeben, der gibt an, dass keine Änderung vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="7797e-131">If the service continues to run with its current state, it should return false from this method, which indicates that no state change has been made.</span></span> <span data-ttu-id="7797e-132">Wenn es wiederhergestellt oder geändert Datenbankzustands, z. B. unvollständige Arbeit ein Rollback sollte "true" zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="7797e-132">If it has restored or altered its state, such as rolling back incomplete work, it should return true.</span></span> <span data-ttu-id="7797e-133">Wenn "true" zurückgegeben wird, muss der Status in den anderen Replikaten angenommen werden, falsch zu sein.</span><span class="sxs-lookup"><span data-stu-id="7797e-133">If true is returned, then the state in other replicas must be assumed to be incorrect.</span></span>
            <span data-ttu-id="7797e-134">Aus diesem Grund die Service Fabric-Laufzeit die anderen Replikaten in der Replikatgruppe entfernt und erneut erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="7797e-134">Therefore, the Service Fabric runtime removes the other replicas from the replica set and recreates them.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProvider.UpdateEpochAsync (epoch, previousEpochLastSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="7797e-135">Die neue <see cref="T:System.Fabric.Epoch" />.</span><span class="sxs-lookup"><span data-stu-id="7797e-135">The new <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> <span data-ttu-id="7797e-136">Die maximale Sequenznummer (LSN) in der vorherigen Epoche.</span><span class="sxs-lookup"><span data-stu-id="7797e-136">The maximum sequence number (LSN) in the previous epoch.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7797e-137">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7797e-137">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="7797e-138">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7797e-138">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="7797e-139">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="7797e-139">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7797e-140">Ein Replikat zeigt an, dass die Konfiguration einer Replikatgruppe aufgrund einer Änderung der geändert oder ändern, mit dem primären Replikat versucht.</span><span class="sxs-lookup"><span data-stu-id="7797e-140">Indicates to a replica that the configuration of a replica set has changed due to a change or attempted change to the primary replica.</span></span> <span data-ttu-id="7797e-141">Die Änderung tritt aufgrund eines Fehlers oder Lastenausgleich des vorherigen primären Replikats.</span><span class="sxs-lookup"><span data-stu-id="7797e-141">The change occurs due to failure or load balancing of the previous primary replica.</span></span> <span data-ttu-id="7797e-142">Epoche Änderungen fungieren als einer Barrier-Klasse, indem Sie segmentieren Vorgänge in die genaue Konfiguration Zeiträume, in denen sie von einem bestimmten primären Replikat gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="7797e-142">Epoch changes act as a barrier by segmenting operations into the exact configuration periods in which they were sent by a specific primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7797e-143">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7797e-143">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="7797e-144">Die Informationen in der <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> -Methode ermöglicht dem Dienst um einen Vektor Status aufrecht ist eine Liste der einzelnen Epoche, die das Replikat empfangen hat und die maximale LSN, die sie enthalten.</span><span class="sxs-lookup"><span data-stu-id="7797e-144">The information in the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method enables the service to maintain a progress vector, which is a list of each epoch that the replica has received, and the maximum LSN that they contained.</span></span> </para>
          <para>
                <span data-ttu-id="7797e-145">Die Bearbeitung Vektordaten werden zusammen mit den aktuellen angewendeten maximale LSN eignet sich für ein sekundäres Replikat während des Kopiervorgangs zu senden, um den Status des Replikats zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="7797e-145">The progress vector data along with the current applied maximum LSN is useful for a secondary replica to send during the copy operation to describe the state of the replica.</span></span></para>
          <para>
                <span data-ttu-id="7797e-146">Vergleichen von Fortschritt Vektoren, die während des Kopiervorgangs von sekundären Replikaten empfangen werden primäre Replikate, um zu bestimmen, ob das sekundäre Replikat auf dem neuesten Stand ist, muss welchen Status an das sekundäre Replikat gesendet werden kann und ob das sekundäre Replikat ist "false" Fortschritt erzielt.</span><span class="sxs-lookup"><span data-stu-id="7797e-146">Comparing progress vectors that are received from secondary replicas during the copy operation enables primary replicas to determine whether the secondary replica is up-to-date, what state must be sent to the secondary replica, and whether the secondary replica has made false progress.</span></span> </para>
          <para><span data-ttu-id="7797e-147">"False" Status bedeutet, dass ein sekundäres Replikat meldet wurde eine LSN in einer vorherigen Epoche größer als die LSN, die das primäre Replikat in seinen Fortschritt Vektor verfügt.</span><span class="sxs-lookup"><span data-stu-id="7797e-147">False progress means that a secondary replica reports an LSN in a previous epoch was greater than the LSN that the primary replica has in its progress vector.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>