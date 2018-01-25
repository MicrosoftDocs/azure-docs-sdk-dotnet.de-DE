<Type Name="IServicePartition" FullName="System.Fabric.IServicePartition">
  <TypeSignature Language="C#" Value="public interface IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartition" />
  <TypeSignature Language="F#" Value="type IServicePartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public interface member from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="05ae7-101">Enthält Informationen zum Dienst die Partition, zu der sie gehört, und bietet Methoden für den Dienst für die Interaktion mit dem System während der Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="05ae7-101">Provides information to the service about the partition to which it belongs and provides methods for the service to interact with the system during runtime.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IServicePartition.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.IServicePartition.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="05ae7-102">Ermöglicht den Zugriff auf die <see cref="T:System.Fabric.ServicePartitionInformation" /> des Diensts, enthält die Partitionstyp und -ID.</span><span class="sxs-lookup"><span data-stu-id="05ae7-102">Provides access to the <see cref="T:System.Fabric.ServicePartitionInformation" /> of the service, which contains the partition type and ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="05ae7-103">Gibt <see cref="T:System.Fabric.ServicePartitionInformation" />zurück.</span><span class="sxs-lookup"><span data-stu-id="05ae7-103">Returns <see cref="T:System.Fabric.ServicePartitionInformation" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-104">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-104">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-105">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-105">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportFault">
      <MemberSignature Language="C#" Value="public void ReportFault (System.Fabric.FaultType faultType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportFault(valuetype System.Fabric.FaultType faultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />
      <MemberSignature Language="F#" Value="abstract member ReportFault : System.Fabric.FaultType -&gt; unit" Usage="iServicePartition.ReportFault faultType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="faultType" Type="System.Fabric.FaultType" />
      </Parameters>
      <Docs>
        <param name="faultType">
          <para><span data-ttu-id="05ae7-106">Die <see cref="T:System.Fabric.FaultType" /> , die der Dienst aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="05ae7-106">The <see cref="T:System.Fabric.FaultType" /> that the service has encountered.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="05ae7-107">Das Replikat für die Laufzeit einen Fehler melden können, und gibt an, dass er einen Fehler gestoßen ist, aus dem es wiederherstellen und neu gestartet oder entfernt werden müssen kann nicht.</span><span class="sxs-lookup"><span data-stu-id="05ae7-107">Enables the replica to report a fault to the runtime and indicates that it has encountered an error from which it cannot recover and must either be restarted or removed.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="05ae7-108">Ein Fehler wird i. d. r. gemeldet, wenn der Dienstcode ein Problem festgestellt wird von dem es nicht wiederhergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="05ae7-108">A fault is typically reported when the service code encounters an issue from which it cannot recover.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-109">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-109">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-110">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-110">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportLoad">
      <MemberSignature Language="C#" Value="public void ReportLoad (System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportLoad(class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.LoadMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportLoad (metrics As IEnumerable(Of LoadMetric))" />
      <MemberSignature Language="F#" Value="abstract member ReportLoad : seq&lt;System.Fabric.LoadMetric&gt; -&gt; unit" Usage="iServicePartition.ReportLoad metrics" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metrics" Type="System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="metrics">
          <para><span data-ttu-id="05ae7-111">Eine Auflistung von <see cref="T:System.Fabric.LoadMetric" /> um die Last zu melden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-111">A collection of <see cref="T:System.Fabric.LoadMetric" /> to report the load for.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="05ae7-112">Meldet die Last für einen Satz von Metriken für den Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="05ae7-112">Reports the load for a set of load balancing metrics.</span></span> <span data-ttu-id="05ae7-113">Die Auslastung kann zu einem beliebigen Zeitpunkt über gemeldet werden die <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" /> Methode und stellt eine oder mehrere Eigenschaften von der <see cref="T:System.Fabric.LoadMetric" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="05ae7-113">The load can be reported at any time via the <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" /> method and provides one or more properties of the <see cref="T:System.Fabric.LoadMetric" /> method.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="05ae7-114">Sollte die gemeldeten Metriken entsprechen, auf die finden Sie in der <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> als Teil der <see cref="T:System.Fabric.Description.ServiceDescription" /> , die zum Erstellen des Diensts verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="05ae7-114">The reported metrics should correspond to those that are provided in the <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> as a part of the <see cref="T:System.Fabric.Description.ServiceDescription" /> that is used to create the service.</span></span> <span data-ttu-id="05ae7-115">Lastmetriken, die nicht in der Beschreibung vorhanden sind, werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="05ae7-115">Load metrics that are not present in the description are ignored.</span></span> <span data-ttu-id="05ae7-116">Können benutzerdefinierte Metriken Reporting Service Fabric zum Lastenausgleich für Dienste, die zusätzliche benutzerdefinierte Informationen basieren.</span><span class="sxs-lookup"><span data-stu-id="05ae7-116">Reporting custom metrics allows Service Fabric to balance services that are based on additional custom information.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-117">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-117">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-118">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-118">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportMoveCost">
      <MemberSignature Language="C#" Value="public void ReportMoveCost (System.Fabric.MoveCost moveCost);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportMoveCost(valuetype System.Fabric.MoveCost moveCost) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportMoveCost(System.Fabric.MoveCost)" />
      <MemberSignature Language="F#" Value="abstract member ReportMoveCost : System.Fabric.MoveCost -&gt; unit" Usage="iServicePartition.ReportMoveCost moveCost" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="moveCost" Type="System.Fabric.MoveCost" />
      </Parameters>
      <Docs>
        <param name="moveCost">
          <para><span data-ttu-id="05ae7-119">Die gemeldete <see cref="T:System.Fabric.MoveCost" />.</span><span class="sxs-lookup"><span data-stu-id="05ae7-119">The reported <see cref="T:System.Fabric.MoveCost" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="05ae7-120">Meldet die Move-Kosten für ein Replikat.</span><span class="sxs-lookup"><span data-stu-id="05ae7-120">Reports the move cost for a replica.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="05ae7-121">Dienste können verschieben Kosten für ein Replikat, das mit dieser Methode gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-121">Services can report move cost of a replica using this method.</span></span> <span data-ttu-id="05ae7-122">Während der Service Fabric-Ressource Bilanzen den besten Kompromiss im Cluster sucht, überprüft es Informationen geladen und Kosten für jedes Replikat verschieben.</span><span class="sxs-lookup"><span data-stu-id="05ae7-122">While the Service Fabric Resource Balances searches for the best balance in the cluster, it examines both load information and move cost of each replica.</span></span> <span data-ttu-id="05ae7-123">Ressource Bilanzen, bevorzugen wahrscheinlich Replikate mit niedrigeren Kosten zu verschieben, um einen Lastenausgleich zu erzielen.</span><span class="sxs-lookup"><span data-stu-id="05ae7-123">Resource balances will prefer to move replicas with lower cost in order to achieve balance.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-124">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-124">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-125">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-125">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iServicePartition.ReportPartitionHealth healthInfo" />
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
        <param name="healthInfo"><span data-ttu-id="05ae7-126">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</span><span class="sxs-lookup"><span data-stu-id="05ae7-126">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="05ae7-127">Partitionsintegrität der aktuellen gemeldet.</span><span class="sxs-lookup"><span data-stu-id="05ae7-127">Reports current partition health.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="05ae7-128">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="05ae7-128">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="05ae7-129">Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="05ae7-129">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="05ae7-130">Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).</span><span class="sxs-lookup"><span data-stu-id="05ae7-130">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="05ae7-131">Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="05ae7-131">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="05ae7-132">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="05ae7-132">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-133">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-133">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-134">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-134">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iServicePartition.ReportPartitionHealth (healthInfo, sendOptions)" />
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
        <param name="healthInfo"><span data-ttu-id="05ae7-135">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</span><span class="sxs-lookup"><span data-stu-id="05ae7-135">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="05ae7-136">Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Partition Bericht gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="05ae7-136">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the partition report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="05ae7-137">Partitionsintegrität der aktuellen gemeldet.</span><span class="sxs-lookup"><span data-stu-id="05ae7-137">Reports current partition health.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="05ae7-138">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="05ae7-138">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="05ae7-139">Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="05ae7-139">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="05ae7-140">Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).</span><span class="sxs-lookup"><span data-stu-id="05ae7-140">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="05ae7-141">Wenn der Bericht hohen Priorität verfügt, können Sie die Sendeoptionen sofort senden angeben.</span><span class="sxs-lookup"><span data-stu-id="05ae7-141">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="05ae7-142">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="05ae7-142">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="05ae7-143">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="05ae7-143">This indicates that the partition object is closed.</span></span> <span data-ttu-id="05ae7-144">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="05ae7-144">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>