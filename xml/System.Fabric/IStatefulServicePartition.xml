<Type Name="IStatefulServicePartition" FullName="System.Fabric.IStatefulServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatefulServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatefulServicePartition = interface&#xA;    interface IServicePartition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IServicePartition</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="3b694-101">Stellt eine Partition, die eines zustandsbehafteten dienstreplikats zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-101">Represents a partition that is associated with a stateful service replica.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="3b694-102">Abgeleitet von <see cref="T:System.Fabric.IServicePartition" />.</span><span class="sxs-lookup"><span data-stu-id="3b694-102">Derived from <see cref="T:System.Fabric.IServicePartition" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricReplicator CreateReplicator (System.Fabric.IStateProvider stateProvider, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.FabricReplicator CreateReplicator(class System.Fabric.IStateProvider stateProvider, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member CreateReplicator : System.Fabric.IStateProvider * System.Fabric.ReplicatorSettings -&gt; System.Fabric.FabricReplicator" Usage="iStatefulServicePartition.CreateReplicator (stateProvider, replicatorSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricReplicator</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateProvider" Type="System.Fabric.IStateProvider" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="stateProvider">
          <para><span data-ttu-id="3b694-103">Die <see cref="T:System.Fabric.IStateProvider" /> mit dem zurückgegebenen <see cref="T:System.Fabric.FabricReplicator" /> verknüpft werden sollen.</span><span class="sxs-lookup"><span data-stu-id="3b694-103">The <see cref="T:System.Fabric.IStateProvider" /> with which the returned <see cref="T:System.Fabric.FabricReplicator" /> should be associated.</span></span> <span data-ttu-id="3b694-104">Dies ist häufig das gleiche Objekt, das implementiert <see cref="T:System.Fabric.IStatefulServiceReplica" />, jedoch bestimmte Dienste möglicherweise anders behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-104">This is often the same object that implements <see cref="T:System.Fabric.IStatefulServiceReplica" />, but certain services might be factored differently.</span></span> </para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="3b694-105">Die <see cref="T:System.Fabric.ReplicatorSettings" /> mit dem zurückgegebenen <see cref="T:System.Fabric.FabricReplicator" /> muss konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-105">The <see cref="T:System.Fabric.ReplicatorSettings" /> with which the returned <see cref="T:System.Fabric.FabricReplicator" /> should be configured.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="3b694-106">Erstellt eine <see cref="T:System.Fabric.FabricReplicator" /> mit den angegebenen Einstellungen und gibt ihn an das Replikat zurück.</span><span class="sxs-lookup"><span data-stu-id="3b694-106">Creates a <see cref="T:System.Fabric.FabricReplicator" /> with the specified settings and returns it to the replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="3b694-107">Gibt <see cref="T:System.Fabric.FabricReplicator" />zurück.</span><span class="sxs-lookup"><span data-stu-id="3b694-107">Returns <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="3b694-108">Diese Methode sollte verwendet werden, zum Erstellen einer <see cref="T:System.Fabric.FabricReplicator" /> Service als die <see cref="T:System.Fabric.IStateReplicator" /> für ein zustandsbehafteter Dienst, der implementiert <see cref="T:System.Fabric.IStateProvider" />.</span><span class="sxs-lookup"><span data-stu-id="3b694-108">This method should be used to create a <see cref="T:System.Fabric.FabricReplicator" /> to service as the <see cref="T:System.Fabric.IStateReplicator" /> for a stateful service that implements <see cref="T:System.Fabric.IStateProvider" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3b694-109">Verwendet, um die Bereitschaft des Replikats hinsichtlich Lesevorgänge zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="3b694-109">Used to check the readiness of the replica in regard to read operations.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="3b694-110">Gibt <see cref="T:System.Fabric.PartitionAccessStatus" />zurück.</span><span class="sxs-lookup"><span data-stu-id="3b694-110">Returns <see cref="T:System.Fabric.PartitionAccessStatus" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3b694-111">Die <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> sollte aktiviert sein, bevor das Replikat eine kundenanforderung verarbeitet wird, die ein Lesevorgang ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-111">The <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> should be checked before the replica is servicing a customer request that is a read operation.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="3b694-112">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-112">This indicates that the partition object is closed.</span></span> <span data-ttu-id="3b694-113">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-113">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="3b694-114">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</span><span class="sxs-lookup"><span data-stu-id="3b694-114">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="3b694-115">Integrität für die aktuelle zustandsbehafteten dienstreplikats der Partition gemeldet.</span><span class="sxs-lookup"><span data-stu-id="3b694-115">Reports health on the current stateful service replica of the partition.</span></span>
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="3b694-116">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="3b694-116">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="3b694-117">Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="3b694-117">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="3b694-118">Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).</span><span class="sxs-lookup"><span data-stu-id="3b694-118">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="3b694-119">Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="3b694-119">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="3b694-120">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="3b694-120">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="3b694-121">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-121">This indicates that the partition object is closed.</span></span> <span data-ttu-id="3b694-122">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-122">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="3b694-123">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</span><span class="sxs-lookup"><span data-stu-id="3b694-123">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="3b694-124">Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="3b694-124">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="3b694-125">Integrität für die aktuelle zustandsbehafteten dienstreplikats der Partition gemeldet.</span><span class="sxs-lookup"><span data-stu-id="3b694-125">Reports health on the current stateful service replica of the partition.</span></span>
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="3b694-126">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="3b694-126">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="3b694-127">Intern verwendet die Partition einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="3b694-127">Internally, the partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="3b694-128">Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).</span><span class="sxs-lookup"><span data-stu-id="3b694-128">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="3b694-129">Wenn der Bericht hohen Priorität verfügt, können Sie die Sendeoptionen sofort senden angeben.</span><span class="sxs-lookup"><span data-stu-id="3b694-129">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="3b694-130">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="3b694-130">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="3b694-131">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-131">This indicates that the partition object is closed.</span></span> <span data-ttu-id="3b694-132">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-132">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3b694-133">Verwendet, um die Bereitschaft der Partition hinsichtlich Schreibvorgänge zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="3b694-133">Used to check the readiness of the partition in regard to write operations.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="3b694-134">Gibt <see cref="T:System.Fabric.PartitionAccessStatus" />zurück.</span><span class="sxs-lookup"><span data-stu-id="3b694-134">Returns <see cref="T:System.Fabric.PartitionAccessStatus" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3b694-135">Die <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> sollte aktiviert sein, bevor das Replikat eine kundenanforderung Dienste, von denen ein Schreibvorgang ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-135">The <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> should be checked before the replica services a customer request that is a write operation.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="3b694-136">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3b694-136">This indicates that the partition object is closed.</span></span> <span data-ttu-id="3b694-137">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="3b694-137">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>