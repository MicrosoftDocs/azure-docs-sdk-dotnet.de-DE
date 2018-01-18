<Type Name="IAtomicGroupStateProvider" FullName="System.Fabric.IAtomicGroupStateProvider">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateProvider : System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateProvider implements class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateProvider&#xA;Implements IStateProvider" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateProvider = interface&#xA;    interface IStateProvider" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="8e3c7-101">Beschreibt zusätzliche Methoden, mit der die <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> -Schnittstelle, die ein Dienst des Benutzers implementieren muss, um die Funktionalität der atomare Gruppe einer Dienstgruppe nutzen.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-101">Describes additional methods of the <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> interface that a user service must implement to take advantage of the atomic group functionality of a service group.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupCommitAsync (long atomicGroupId, long commitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupCommitAsync(int64 atomicGroupId, int64 commitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupCommitAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupCommitAsync (atomicGroupId, commitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="8e3c7-102">Die ID der Gruppe, die ein Commit ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-102">The ID of the group to be committed.</span></span></para>
        </param>
        <param name="commitSequenceNumber">
          <para><span data-ttu-id="8e3c7-103">Die Sequenznummer für den Commitvorgang.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-103">The sequence number for the commit operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="8e3c7-104">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-104">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="8e3c7-105">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-105">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="8e3c7-106">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-106">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8e3c7-107">Führt einen Commit für eine bestimmte unteilbare Gruppe.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-107">Commits a particular atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8e3c7-108">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-108">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupRollbackAsync (long atomicGroupId, long rollbackSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupRollbackAsync(int64 atomicGroupId, int64 rollbackSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupRollbackAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupRollbackAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupRollbackAsync (atomicGroupId, rollbackSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="8e3c7-109">Die ID der Gruppe, die für einen Rollback auszuführen.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-109">The ID of the group to roll back.</span></span></para>
        </param>
        <param name="rollbackSequenceNumber">
          <para><span data-ttu-id="8e3c7-110">Die Sequenznummer für den Rollbackvorgang.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-110">The sequence number for the rollback operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="8e3c7-111">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-111">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="8e3c7-112">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-112">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="8e3c7-113">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-113">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8e3c7-114">Führt einen Rollback für eine bestimmte unteilbare Gruppe aus.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-114">Rolls back a particular atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="8e3c7-115">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-115">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupUndoProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupUndoProgressAsync (long fromCommitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupUndoProgressAsync(int64 fromCommitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupUndoProgressAsync(System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupUndoProgressAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupUndoProgressAsync (fromCommitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromCommitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fromCommitSequenceNumber">
          <para><span data-ttu-id="8e3c7-116">Die LSN eines Commit-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-116">The LSN of a commit operation.</span></span> <span data-ttu-id="8e3c7-117">Alle Status über diesen Punkt hinaus sollte rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-117">All progress past this point should be undone.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="8e3c7-118">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-118">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="8e3c7-119">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="8e3c7-120">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-120">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8e3c7-121">Gibt dieser Status über einen bestimmten commitfolgenummer, die über bereitgestellt wird <see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" /> sollte nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-121">Indicates that progress beyond a particular commit sequence number that is provided via <see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" /> should be undone.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="8e3c7-122">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8e3c7-122">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>