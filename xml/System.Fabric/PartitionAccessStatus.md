<Type Name="PartitionAccessStatus" FullName="System.Fabric.PartitionAccessStatus">
  <TypeSignature Language="C#" Value="public enum PartitionAccessStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionAccessStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionAccessStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionAccessStatus" />
  <TypeSignature Language="F#" Value="type PartitionAccessStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="71cfe-101">Listet die Zugriffsstatus der Partition an.</span><span class="sxs-lookup"><span data-stu-id="71cfe-101">Enumerates the access status of the partition.</span></span> </para>
    </summary>
    <remarks>
      <para>
        <span data-ttu-id="71cfe-102"><see cref="T:System.Fabric.PartitionAccessStatus" />wird verwendet, um zu überprüfen, dass ein Schreib- oder Lesevorgang zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="71cfe-102"><see cref="T:System.Fabric.PartitionAccessStatus" /> is used to check that a read or write operation is allowed.</span></span> <span data-ttu-id="71cfe-103">Beim dienstreplikate eine Clientanforderung behandeln sollten sie überprüfen, ob das System in einem Zustand befindet, die Verarbeitung ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="71cfe-103">When service replicas handle a client request, they should verify that the system is in a state that allows processing.</span></span> <span data-ttu-id="71cfe-104">Durch Überprüfen der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> oder <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> nach Bedarf, kann das Replikat von Bedingungen, die korrekte Ausführung verhindert benachrichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="71cfe-104">By checking the <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> or <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> as appropriate, the replica can be notified of conditions that prevent correct operation.</span></span> <span data-ttu-id="71cfe-105">Beachten Sie, die Schreibvorgänge möglicherweise eine Ausnahme aus dem Replicator für eine der folgenden Bedingungen weiterhin angezeigt, weil die Bedingung zwischen ändern kann die <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> Kontrollkästchen und der Aufruf von <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span><span class="sxs-lookup"><span data-stu-id="71cfe-105">Note that write operations might still see an exception from the replicator for one of these conditions, because the condition might change between the <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> check and the call to <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Granted">
      <MemberSignature Language="C#" Value="Granted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Granted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Granted" />
      <MemberSignature Language="VB.NET" Value="Granted" />
      <MemberSignature Language="F#" Value="Granted = 1" Usage="System.Fabric.PartitionAccessStatus.Granted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="71cfe-106">Gibt an, dass der Lese- oder Schreibberechtigungen Vorgang Zugriff erteilt, und der Vorgang ist nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="71cfe-106">Indicates that the read or write operation access is granted and the operation is allowed.</span></span> </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="71cfe-107">Gibt an, dass der Zugriffsstatus Lese- oder Schreibberechtigungen Vorgang ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="71cfe-107">Indicates that the read or write operation access status is not valid.</span></span> <span data-ttu-id="71cfe-108">Dieser Wert wird nicht an den Aufrufer zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="71cfe-108">This value is not returned to the caller.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotPrimary">
      <MemberSignature Language="C#" Value="NotPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NotPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberSignature Language="VB.NET" Value="NotPrimary" />
      <MemberSignature Language="F#" Value="NotPrimary = 3" Usage="System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="71cfe-109">Gibt an, dass diese Clientanforderung von einem Replikat empfangen wurde, die nicht über ein primäres Replikat handelt.</span><span class="sxs-lookup"><span data-stu-id="71cfe-109">Indicates that this client request was received by a replica that is not a Primary replica.</span></span> <span data-ttu-id="71cfe-110">Die Schreib- oder Lesevorgang kann nicht zu diesem Replikat ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="71cfe-110">The read or write operation cannot be performed at this replica.</span></span> <span data-ttu-id="71cfe-111">Der Client sollte versuchen naming Service zu verwenden, um das richtige primären Replikat zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="71cfe-111">The client should attempt to use the naming service to identify the correct primary replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NoWriteQuorum">
      <MemberSignature Language="C#" Value="NoWriteQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NoWriteQuorum = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberSignature Language="VB.NET" Value="NoWriteQuorum" />
      <MemberSignature Language="F#" Value="NoWriteQuorum = 4" Usage="System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="71cfe-112">Gibt an, dass kein Quorum Schreibzugriff verfügbar ist und daher keine Schreibvorgang akzeptiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="71cfe-112">Indicates that no write quorum is available and, therefore, no write operation can be accepted.</span></span> <span data-ttu-id="71cfe-113">Der Client sollte es sich um den Vorgang in diesem Replikat wiederholen.</span><span class="sxs-lookup"><span data-stu-id="71cfe-113">The client should retry the operation at this replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPending">
      <MemberSignature Language="C#" Value="ReconfigurationPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus ReconfigurationPending = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberSignature Language="VB.NET" Value="ReconfigurationPending" />
      <MemberSignature Language="F#" Value="ReconfigurationPending = 2" Usage="System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="71cfe-114">Gibt an, dass der Client später erneut versuchen soll, da eine Neukonfiguration ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="71cfe-114">Indicates that the client should try again later, because a reconfiguration is in progress.</span></span> <span data-ttu-id="71cfe-115">Nachdem die Neukonfiguration abgeschlossen ist, wird ein neuer Status, die weitere Anleitungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="71cfe-115">After the reconfiguration is completed, a new status is returned that gives further instructions.</span></span> <span data-ttu-id="71cfe-116">Der Client sollte wiederholen Sie den Vorgang in diesem Replikat</span><span class="sxs-lookup"><span data-stu-id="71cfe-116">The client should retry the operation at this replica</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>