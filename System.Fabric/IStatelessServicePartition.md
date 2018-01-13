<Type Name="IStatelessServicePartition" FullName="System.Fabric.IStatelessServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatelessServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatelessServicePartition = interface&#xA;    interface IServicePartition" />
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
      <para><span data-ttu-id="7fc2a-101">Stellt eine Partition, die einer zustandslosen Dienstinstanz zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-101">Represents a partition that is associated with a stateless service instance.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="7fc2a-102">Bereitgestellt, um eines zustandslosen Diensts als Parameter an die <see cref="T:System.Fabric.IServicePartition" />.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-102">Provided to a stateless service as a parameter to the <see cref="T:System.Fabric.IServicePartition" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth healthInfo" />
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
        <param name="healthInfo"><span data-ttu-id="7fc2a-103">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , die Integrität Berichtsinformationen, wie z. B. Quelle bzw. Integrität Status beschreibt.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-103">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="7fc2a-104">Meldet Zustandsinformationen für die aktuelle statusfreien Dienstinstanz der Partition an.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-104">Reports health information on the current stateless service instance of the partition.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="7fc2a-105">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-105">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="7fc2a-106">Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-106">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="7fc2a-107">Wenn der Bericht hohen Priorität verfügt, können Sie angeben, dass Sendeoptionen an, es sofort senden <see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-107">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="7fc2a-108">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-108">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7fc2a-109">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-109">This indicates that the partition object is closed.</span></span> <span data-ttu-id="7fc2a-110">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-110">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth (healthInfo, sendOptions)" />
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
        <param name="healthInfo"><span data-ttu-id="7fc2a-111">Die <see cref="T:System.Fabric.Health.HealthInformation" /> , beschreibt die Berichtsinformationen Integrität z. B. Quelle, der Eigenschaft und der Integrität.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-111">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="7fc2a-112">Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-112">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="7fc2a-113">Meldet Zustandsinformationen für die aktuelle statusfreien Dienstinstanz der Partition an.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-113">Reports health information on the current stateless service instance of the partition.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="7fc2a-114">Die Zustandsinformationen beschreibt die Berichtsdetails, wie die Quell-ID, die Eigenschaft, den Integritätsstatus und andere relevante Details an.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-114">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="7fc2a-115">Die Partition verwendet einen internen Health-Client zum Senden der Berichte im Health Store.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-115">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="7fc2a-116">Der Client Nachrichten an den Integritätsdienst durch Batchverarbeitung Berichte pro einen konfigurierten Zeitraum optimiert (Standardwert: 30 Sekunden).</span><span class="sxs-lookup"><span data-stu-id="7fc2a-116">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="7fc2a-117">Wenn der Bericht hohen Priorität verfügt, können Sie die Sendeoptionen sofort senden angeben.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-117">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="7fc2a-118">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">Clientintegritätsberichte</see>.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-118">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7fc2a-119">Dies gibt an, dass die Partitionsobjekt geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-119">This indicates that the partition object is closed.</span></span> <span data-ttu-id="7fc2a-120">Die/Replikator/Replikatinstanz entweder geschlossen wurde oder wird jetzt geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="7fc2a-120">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>