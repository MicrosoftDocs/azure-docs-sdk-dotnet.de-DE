<Type Name="IOperation" FullName="System.Fabric.IOperation">
  <TypeSignature Language="C#" Value="public interface IOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperation" />
  <TypeSignature Language="F#" Value="type IOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="90b75-101">Beschreibt die Daten, die aus der zustandsreplikator abgerufen.</span><span class="sxs-lookup"><span data-stu-id="90b75-101">Describes the data that is obtained from the state replicator.</span></span> </para>
    </summary>
    <remarks>
      <para>
        <span data-ttu-id="90b75-102"><see cref="T:System.Fabric.IOperation" />ist die Basisschnittstelle, die Änderungen beschreibt, die an ein sekundäres Replikat übermittelt werden.</span><span class="sxs-lookup"><span data-stu-id="90b75-102"><see cref="T:System.Fabric.IOperation" /> is the base interface that describes state changes that are delivered to a Secondary replica.</span></span> </para>
      <para>
                <span data-ttu-id="90b75-103">Sie enthalten die <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> und identifizieren Sie die Sequenznummer und andere Informationen.</span><span class="sxs-lookup"><span data-stu-id="90b75-103">They contain the <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> and the sequence number and other identifying information.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Acknowledge">
      <MemberSignature Language="C#" Value="public void Acknowledge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Acknowledge() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperation.Acknowledge" />
      <MemberSignature Language="VB.NET" Value="Public Sub Acknowledge ()" />
      <MemberSignature Language="F#" Value="abstract member Acknowledge : unit -&gt; unit" Usage="iOperation.Acknowledge " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="90b75-104">Bestätigt, dass dieser Vorgang erfolgreich auf das sekundäre Replikat angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="90b75-104">Acknowledges that this operation has been successfully applied at the Secondary replica.</span></span>  </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="90b75-105">Dienste sollten diese Methode aufrufen, wenn sie gewonnen haben eine <see cref="T:System.Fabric.IOperation" /> aus dem Replicator und erfolgreich auf ihren lokalen Speicher angewendet.</span><span class="sxs-lookup"><span data-stu-id="90b75-105">Services should call this method when they have obtained an <see cref="T:System.Fabric.IOperation" /> from the replicator and successfully applied it to their local store.</span></span>
            <span data-ttu-id="90b75-106">Beim Aufrufen dieser Methode für persistente Dienste obligatorisch ist da die <see cref="T:System.Fabric.FabricReplicator" /> aufgehoben wird, zusätzliche Objekte, die implementieren <see cref="T:System.Fabric.IOperation" />.</span><span class="sxs-lookup"><span data-stu-id="90b75-106">For persisted services, calling this method is mandatory because the <see cref="T:System.Fabric.FabricReplicator" /> does not release additional objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="90b75-107">Für Dienste volatile Vorgänge Replikator implizit bestätigt, wenn sie empfangen werden, es sei denn, sie andernfalls konfiguriert sind, durch Festlegen des Werts <see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /> auf "true".</span><span class="sxs-lookup"><span data-stu-id="90b75-107">For volatile services, the replicator implicitly acknowledges operations when they are received unless they are configured otherwise by setting the value <see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /> to true.</span></span>
            <span data-ttu-id="90b75-108">Ein Vorgang muss durch ein Quorum der Replikate bestätigt werden, bevor das primäre Replikat empfängt die <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> Vorgangsantworten abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="90b75-108">An operation must be acknowledged by a quorum of replicas before the Primary replica receives the <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> operation complete responses.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupId">
      <MemberSignature Language="C#" Value="public long AtomicGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AtomicGroupId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.AtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AtomicGroupId As Long" />
      <MemberSignature Language="F#" Value="member this.AtomicGroupId : int64" Usage="System.Fabric.IOperation.AtomicGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="90b75-109">Gibt die atomare Gruppe an, wenn dieses Objekt, die implementiert <see cref="T:System.Fabric.IOperation" /> unteilbare Gruppe gehört.</span><span class="sxs-lookup"><span data-stu-id="90b75-109">Identifies the atomic group, if this object that implements <see cref="T:System.Fabric.IOperation" /> is a part of an atomic group.</span></span> <span data-ttu-id="90b75-110">Atomische-Gruppen sind nur verfügbar, wenn ein Dienst ein Teil der Gruppe "Datenzugriffsdienst" ist.</span><span class="sxs-lookup"><span data-stu-id="90b75-110">Atomic groups are only available when a service is a part of service group.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="90b75-111">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="90b75-111">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationData Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.OperationData Data" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As OperationData" />
      <MemberSignature Language="F#" Value="member this.Data : System.Fabric.OperationData" Usage="System.Fabric.IOperation.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="90b75-112">Ruft die <see cref="T:System.Fabric.OperationData" /> , die vom primären Replikat bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="90b75-112">Gets the <see cref="T:System.Fabric.OperationData" /> that are provided by the Primary replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="90b75-113">Gibt <see cref="T:System.Fabric.OperationData" />zurück.</span><span class="sxs-lookup"><span data-stu-id="90b75-113">Returns <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.OperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As OperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : System.Fabric.OperationType" Usage="System.Fabric.IOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="90b75-114">Ruft den Typ dieses Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="90b75-114">Gets the type of this operation.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="90b75-115">Gibt <see cref="T:System.Fabric.OperationType" />zurück.</span><span class="sxs-lookup"><span data-stu-id="90b75-115">Returns <see cref="T:System.Fabric.OperationType" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="90b75-116">Die <see cref="T:System.Fabric.OperationType" /> gibt den Typ des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="90b75-116">The <see cref="T:System.Fabric.OperationType" /> indicates the type of operation.</span></span> <span data-ttu-id="90b75-117">"Normal"-Vorgänge sind diejenigen, die im Rahmen des Streams für das Kopieren oder die Replikation von nicht-gruppierten Services gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="90b75-117">"Normal" operations are those operations that are sent by non-service grouped services as part of either the copy or replication streams.</span></span> <span data-ttu-id="90b75-118">Andere Arten von Vorgängen Steuerelement Vorgänge dar, die für Dienstgruppen spezifisch sind.</span><span class="sxs-lookup"><span data-stu-id="90b75-118">Other types of operations represent control operations that are specific to service groups.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.IOperation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="90b75-119">Ruft die Sequenznummer dieses Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="90b75-119">Gets the sequence number of this operation.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="90b75-120">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="90b75-120">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>
          <para>
                <span data-ttu-id="90b75-121">Die Sequenznummer wird bereitgestellt, als Teil der<see cref="P:System.Fabric.IOperation.SequenceNumber" /></span><span class="sxs-lookup"><span data-stu-id="90b75-121">The sequence number is provided as a part of the <see cref="P:System.Fabric.IOperation.SequenceNumber" /></span></span></para>
          <para>
                <span data-ttu-id="90b75-122">Für Vorgänge, die von der Replikationsstream empfangen (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) die Sequenznummer ist identisch, die das primäre Replikat, die von erhält <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="90b75-122">For operations received from the replication stream (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) the sequence number is the same that the Primary replica that are receives from <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>