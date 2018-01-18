<Type Name="IAtomicGroupStateReplicator" FullName="System.Fabric.IAtomicGroupStateReplicator">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b0b3c-101">Macht Funktionen für atomic-Gruppen im Zusammenhang mit Replikation.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-101">Exposes replication-related functions for atomic groups.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="b0b3c-102">Die <see cref="T:System.Fabric.IAtomicGroupStateReplicator" /> ist verfügbar, wenn der Dienst einer Dienstgruppe angehört.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-102">The <see cref="T:System.Fabric.IAtomicGroupStateReplicator" /> is available if the service is a member of a service group.</span></span> <span data-ttu-id="b0b3c-103">Implementieren des Diensts muss <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> und statusbehaftete sein.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-103">The service must implement <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> and be stateful.</span></span> <span data-ttu-id="b0b3c-104">Beim Erstellen einer <see cref="T:System.Fabric.FabricReplicator" /> über <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />, anstelle der Übergabe einer reguläres <see cref="T:System.Fabric.IStateProvider" />, kann der Dienst übergeben der <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> , die ihn implementiert stattdessen.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-104">When creating a <see cref="T:System.Fabric.FabricReplicator" /> via <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />, instead of passing in a regular <see cref="T:System.Fabric.IStateProvider" />, the service can pass in the <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> that it implements instead.</span></span> <span data-ttu-id="b0b3c-105">Daher erhält er eine <see cref="T:System.Fabric.IAtomicGroupStateReplicator" />.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-105">As a result, it receives a <see cref="T:System.Fabric.IAtomicGroupStateReplicator" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAtomicGroup">
      <MemberSignature Language="C#" Value="public long CreateAtomicGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 CreateAtomicGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAtomicGroup () As Long" />
      <MemberSignature Language="F#" Value="abstract member CreateAtomicGroup : unit -&gt; int64" Usage="iAtomicGroupStateReplicator.CreateAtomicGroup " />
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
          <para><span data-ttu-id="b0b3c-106">Erstellt eine neue atomare Gruppe und ruft die ID der Gruppe "atomic" ab.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-106">Creates a new atomic group and obtains the ID of the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b0b3c-107">Gibt <see cref="T:System.Int64" /> die ID von der atomare Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-107">Returns <see cref="T:System.Int64" /> the ID of the created atomic group.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="b0b3c-108">Atomische Gruppen werden verwendet, um einen Satz von Änderungen auf die Mitglieder einer Dienstgruppe zu koordinieren.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-108">Atomic groups are used to coordinate a set of changes across the members of a service group.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupCommitAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupCommitAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupCommitAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync (atomicGroupId, cancellationToken, commitSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b0b3c-109">Die ID der Gruppe, die ein Commit ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-109">The ID of the group to be committed.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b0b3c-110">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-110">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="b0b3c-111">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-111">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b0b3c-112">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="commitSequenceNumber">
          <para><span data-ttu-id="b0b3c-113">Die LSN des Commitvorgangs als Out-Parameter.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-113">The LSN of the commit operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b0b3c-114">Führt einen Commit asynchron Status der Replikation für atomare Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-114">Asynchronously commits state replication for the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b0b3c-115">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN des Commitvorgangs.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-115">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the commit operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupOperationAsync (long atomicGroupId, System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupOperationAsync(int64 atomicGroupId, class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync(System.Int64,System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupOperationAsync : int64 * System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync (atomicGroupId, operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b0b3c-116">Die ID von der atomare Gruppe, die aus abgerufen <see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" /> und enthält die <see cref="T:System.Fabric.OperationData" />.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-116">The ID of the atomic group that is obtained from <see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" /> and includes the <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </param>
        <param name="operationData">
          <para><span data-ttu-id="b0b3c-117">Ein <see cref="T:System.Fabric.OperationData" /> repliziert werden.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-117">An <see cref="T:System.Fabric.OperationData" /> to be replicated.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b0b3c-118">Das CancellationToken-Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-118">The CancellationToken object that the operation is observing.</span></span> <span data-ttu-id="b0b3c-119">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b0b3c-120">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-120">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="sequenceNumber">
          <para><span data-ttu-id="b0b3c-121">Die LSN des Vorgangs, als Out-Parameter.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-121">The LSN of the operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b0b3c-122">Einige repliziert <see cref="T:System.Fabric.OperationData" /> als Teil einer atomare Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-122">Replicates some <see cref="T:System.Fabric.OperationData" /> as a part of an atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b0b3c-123">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN der die replizierten atomaren Vorgang "Gruppe".</span><span class="sxs-lookup"><span data-stu-id="b0b3c-123">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the replicated atomic group operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupRollbackAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long rollbackSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupRollbackAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; rollbackSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupRollbackAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync (atomicGroupId, cancellationToken, rollbackSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b0b3c-124">Die ID von der atomare Gruppe Rollback.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-124">The ID of the atomic group to roll back.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b0b3c-125">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-125">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="b0b3c-126">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-126">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b0b3c-127">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-127">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="rollbackSequenceNumber">
          <para><span data-ttu-id="b0b3c-128">Die LSN der Rollback-Vorgangs, als Out-Parameter.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-128">The LSN of the rollback operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b0b3c-129">Asynchron ein Rollback des Status der Replikation für atomare Gruppe.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-129">Asynchronously rolls-back state replication for the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b0b3c-130">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN der Rollback-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b0b3c-130">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the rollback operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>