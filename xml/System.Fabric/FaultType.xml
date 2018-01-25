<Type Name="FaultType" FullName="System.Fabric.FaultType">
  <TypeSignature Language="C#" Value="public enum FaultType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FaultType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FaultType" />
  <TypeSignature Language="VB.NET" Value="Public Enum FaultType" />
  <TypeSignature Language="F#" Value="type FaultType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="dacd9-101">Gibt den Typ des Fehlers, der ein Dienst meldet: ungültig, vorübergehend oder dauerhaft.</span><span class="sxs-lookup"><span data-stu-id="dacd9-101">Indicates the type of fault that a service reports: invalid, transient or permanent.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="dacd9-102">Dienste können Fehler während der Laufzeit per melden die <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Methode, um den Typ des Fehlers anzugeben.</span><span class="sxs-lookup"><span data-stu-id="dacd9-102">Services can report faults during runtime by using the <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> method to indicate the type of fault.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.FaultType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dacd9-103">Der Typ ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="dacd9-103">The type is invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Permanent">
      <MemberSignature Language="C#" Value="Permanent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Permanent = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Permanent" />
      <MemberSignature Language="VB.NET" Value="Permanent" />
      <MemberSignature Language="F#" Value="Permanent = 1" Usage="System.Fabric.FaultType.Permanent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dacd9-104">Ein dauerhafter Fehler ist ein Fehler, dem das Replikat von wiederhergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="dacd9-104">A permanent fault is a fault that the replica cannot recover from.</span></span> <span data-ttu-id="dacd9-105">Diese Art von Fehler gibt an, dass das Replikat kann keine weitere Bearbeitung vornehmen und entfernt und ersetzt.</span><span class="sxs-lookup"><span data-stu-id="dacd9-105">This type of fault indicates that the replica can make no further progress and should be removed and replaced.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="dacd9-106">Ein Beispiel für einen dauerhaften Fehler wäre eine permanente zustandsbehaftete Dienst, der versucht, Informationen auf den Datenträger schreibt und feststellt, dass der Datenträger entfernt wurde oder wurde nicht verwendbar.</span><span class="sxs-lookup"><span data-stu-id="dacd9-106">An example of a permanent fault would be a persistent stateful service that tries to write information to disk and determines that the disk had been removed or was unusable.</span></span> <span data-ttu-id="dacd9-107">Aufrufen von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> und ein Ergebnis dauerhaften Fehler im Dienst über abgebrochen reporting <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span><span class="sxs-lookup"><span data-stu-id="dacd9-107">Calling <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> and reporting a permanent fault result in the service to be Aborted via <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span></span> <span data-ttu-id="dacd9-108">oder <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span><span class="sxs-lookup"><span data-stu-id="dacd9-108">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span></span> <span data-ttu-id="dacd9-109">ohne die Möglichkeit, Status oder abgeschlossener Vorgänge ordnungsgemäß bereinigen.</span><span class="sxs-lookup"><span data-stu-id="dacd9-109">without a chance to gracefully clean up state or complete operations.</span></span> <span data-ttu-id="dacd9-110">Daher, wenn eine Bereinigung ausführen oder andere langer erforderlich ist, sie sollten ausgeführt werden vor dem <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dacd9-110">Therefore, if any cleanup or other long-running work is necessary, it should be performed before <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> is called.</span></span> <span data-ttu-id="dacd9-111">Beachten Sie, dass die Unterscheidung zwischen permanente und flüchtige Fehler hauptsächlich für beständige zustandsbehaftete Dienste nützlich ist.</span><span class="sxs-lookup"><span data-stu-id="dacd9-111">Note that the distinction between permanent and transient faults is useful mainly for persistent stateful services.</span></span> <span data-ttu-id="dacd9-112">Abgesehen von der Aufruffolge sind die Auswirkungen auf andere Diensttypen identisch: das Replikat oder eine Instanz entfernt wird, alle Zustände an dieses Replikat oder Instanz verloren gegangen ist und das Replikat oder eine Instanz wird neu erstellt, möglicherweise in einem anderen Speicherort.</span><span class="sxs-lookup"><span data-stu-id="dacd9-112">Other than the call sequence, the effects on other service types are the same: the replica or instance is removed, all state at that replica or instance is lost, and the replica or instance is recreated, potentially in a different location.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Transient">
      <MemberSignature Language="C#" Value="Transient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Transient = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Transient" />
      <MemberSignature Language="VB.NET" Value="Transient" />
      <MemberSignature Language="F#" Value="Transient = 2" Usage="System.Fabric.FaultType.Transient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dacd9-113">Ein vorübergehender Fehler gibt an, dass einige temporäre Bedingung verhindert, das Replikat dass von weiteren Fortschritte oder weitere benutzeranforderungen verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="dacd9-113">A transient fault indicates that there is some temporary condition which prevents the replica from making further progress or from processing further user requests.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="dacd9-114">Ein Beispiel eines vorübergehenden Fehlers ist ein Dienst, der feststellt, dass ein Teil des Datenbankzustands oder einige Referenzdatei ist beschädigt, doch repariert werden kann, wäre der Dienst erneut initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="dacd9-114">An example of a transient fault is a service that determines that a portion of its state or some reference file is corrupted, but can be repaired if the service were to be re-initialized.</span></span> <span data-ttu-id="dacd9-115">Der Dienst in diesem Fall verwendet die <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Methode, um einen vorübergehenden Fehler zu melden.</span><span class="sxs-lookup"><span data-stu-id="dacd9-115">In this case, the service uses the <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> method to report a transient fault.</span></span> <span data-ttu-id="dacd9-116">Einen vorübergehenden Fehler Reporting schließt den Dienst über <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /></span><span class="sxs-lookup"><span data-stu-id="dacd9-116">Reporting a transient fault closes the service via <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /></span></span> <span data-ttu-id="dacd9-117">oder <languageKeyword>IStatelessServiceInstance.</languageKeyword> <see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="dacd9-117">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="dacd9-118">Beachten Sie, dass für Zustandslose und zustandsbehaftete Dienste volatile vorübergehende Fehler nicht sehr nützlich sind, da über den Fehler nicht beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="dacd9-118">Note that for stateless and stateful services, volatile transient faults are not very useful because state is not preserved across the failure.</span></span> <span data-ttu-id="dacd9-119">Für diese Dienste ist, ob vorübergehende oder dauerhafte Fehlern verwendet abhängig, ob der Dienst ordnungsgemäß asynchron with Cleanup, geschlossen oder mit einer synchronen nicht ordnungsgemäß geschlossen werden sollte <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span><span class="sxs-lookup"><span data-stu-id="dacd9-119">For these services, whether to use transient or permanent faults is dependent on whether the service should be gracefully closed asynchronously with cleanup or ungracefully closed with a synchronous <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span></span> <span data-ttu-id="dacd9-120">oder <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span><span class="sxs-lookup"><span data-stu-id="dacd9-120">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span></span> <span data-ttu-id="dacd9-121">-Methode.</span><span class="sxs-lookup"><span data-stu-id="dacd9-121">method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>