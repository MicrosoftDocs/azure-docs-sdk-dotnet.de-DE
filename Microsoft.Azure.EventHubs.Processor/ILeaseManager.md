<Type Name="ILeaseManager" FullName="Microsoft.Azure.EventHubs.Processor.ILeaseManager">
  <TypeSignature Language="C#" Value="public interface ILeaseManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILeaseManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILeaseManager" />
  <TypeSignature Language="F#" Value="type ILeaseManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9e0a-101">Wenn Sie EventProcessorHost Leases an einer anderen Stelle als Azure-Speicher gespeichert haben möchten, können Sie eigene Verwendung dieser Schnittstelle Lease-Manager schreiben.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-101">If you wish to have EventProcessorHost store leases somewhere other than Azure Storage, you can write your own lease manager using this interface.</span></span>  
            
            <span data-ttu-id="c9e0a-102"><para>Die Azure-Speicher-Manager verwenden den gleichen Speicher wie für Lease und Prüfpunkte, sodass beide Schnittstellen von derselben Klasse implementiert werden. Sie können dasselbe nicht tun, wenn Sie einheitlichen Speicher für beide Arten von Daten. </para> <para>Diese Schnittstelle nicht Initialisierungsmethoden angeben, da es keine Möglichkeit, zu wissen, welche Informationen, die Ihre Implementierung haben.</para></span><span class="sxs-lookup"><span data-stu-id="c9e0a-102"><para>The Azure Storage managers use the same storage for both lease and checkpoints, so both interfaces are implemented by the same class. You are free to do the same thing if you have a unified store for both types of data.</para><para>This interface does not specify initialization methods because we have no way of knowing what information your implementation will require.</para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; AcquireLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; AcquireLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.AcquireLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.AcquireLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="c9e0a-103">Lease-Informationen für die gewünschte Partition aus GetLeaseAsync() wie zuvor abgerufene</span><span class="sxs-lookup"><span data-stu-id="c9e0a-103">Lease info for the desired partition as previously obtained from GetLeaseAsync()</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-104">Die Lease für die gewünschte Partition für diese EventProcessorHost abrufen.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-104">Acquire the lease on the desired partition for this EventProcessorHost.</span></span>
            
            <span data-ttu-id="c9e0a-105"><para>Beachten Sie, dass es zulässig ist, eine Lease abgerufen werden, die bereits von einem anderen Host gehört. Lease stehlen ist wie die Partitionen verteilt werden, wenn weitere Hosts gestartet werden.</para></span><span class="sxs-lookup"><span data-stu-id="c9e0a-105"><para>Note that it is legal to acquire a lease that is already owned by another host. Lease-stealing is how partitions are redistributed when additional hosts are started.</para></span></span></summary>
        <returns><span data-ttu-id="c9e0a-106">"true", wenn die Lease erfolgreich, "false" ist dies nicht eingerichtet wurde</span><span class="sxs-lookup"><span data-stu-id="c9e0a-106">true if the lease was acquired successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseIfNotExistsAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.CreateLeaseIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="c9e0a-107">ID des zu erstellenden Lease-Informationen für die partition</span><span class="sxs-lookup"><span data-stu-id="c9e0a-107">id of partition to create lease info for</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-108">Erstellen Sie im Store die Lease-Informationen für die angegebene Partition ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-108">Create in the store the lease info for the given partition, if it does not exist.</span></span> <span data-ttu-id="c9e0a-109">Tun Sie nichts, wenn sie bereits im Speicher vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-109">Do nothing if it does exist in the store already.</span></span> 
            </summary>
        <returns><span data-ttu-id="c9e0a-110">die vorhandenen oder neu erstellten Lease-Informationen für die partition</span><span class="sxs-lookup"><span data-stu-id="c9e0a-110">the existing or newly-created lease info for the partition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.CreateLeaseStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-111">Die Lease-Speicher erstellen, wenn sie nicht vorhanden ist, werden keine Aktionen ausgeführt, wenn er vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-111">Create the lease store if it does not exist, do nothing if it does exist.</span></span>
            </summary>
        <returns><span data-ttu-id="c9e0a-112">"true", wenn die Lease bereits speichern vorhanden oder wurde erfolgreich erstellt, "false" ist dies nicht der</span><span class="sxs-lookup"><span data-stu-id="c9e0a-112">true if the lease store already exists or was created successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task" Usage="iLeaseManager.DeleteLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="c9e0a-113">Lease-Informationen für die gewünschte Partition aus GetLeaseAsync() wie zuvor abgerufene</span><span class="sxs-lookup"><span data-stu-id="c9e0a-113">Lease info for the desired partition as previously obtained from GetLeaseAsync()</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-114">Löschen Sie die Lease-Informationen für die angegebene Partition aus dem Speicher.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-114">Delete the lease info for the given partition from the store.</span></span> <span data-ttu-id="c9e0a-115">Wenn keine gespeicherten Leasedauer für die angegebene Partition vorhanden ist, wird, erfolgreich behandelt.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-115">If there is no stored lease for the given partition, that is treated as success.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseStoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteLeaseStoreAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteLeaseStoreAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseStoreAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteLeaseStoreAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseStoreAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.DeleteLeaseStoreAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-116">EventProcessorHost, aber eine praktische Funktion verwendet zum Testen haben nicht.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-116">Not used by EventProcessorHost, but a convenient function to have for testing.</span></span>
            </summary>
        <returns><span data-ttu-id="c9e0a-117">True, wenn der Lease Speicher erfolgreich, "false" ist dies nicht der gelöscht wurde</span><span class="sxs-lookup"><span data-stu-id="c9e0a-117">true if the lease store was deleted successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLeases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetAllLeases" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLeases () As IEnumerable(Of Task(Of Lease))" />
      <MemberSignature Language="F#" Value="abstract member GetAllLeases : unit -&gt; seq&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;" Usage="iLeaseManager.GetAllLeases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-118">Geben Sie die Lease-Informationen für alle Partitionen zurück.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-118">Return the lease info for all partitions.</span></span>
            <span data-ttu-id="c9e0a-119">Eine typische Implementierung aufrufen für alle Partitionen nur GetLeaseAsync().</span><span class="sxs-lookup"><span data-stu-id="c9e0a-119">A typical implementation could just call GetLeaseAsync() on all partitions.</span></span>
            </summary>
        <returns><span data-ttu-id="c9e0a-120">Liste der Lease-Informationen.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-120">list of lease info.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetLeaseAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLeaseAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member GetLeaseAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.GetLeaseAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="c9e0a-121">ID der Partition zum Abrufen der Lease für</span><span class="sxs-lookup"><span data-stu-id="c9e0a-121">id of partition to get lease for</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-122">Geben Sie die Lease-Informationen für die angegebene Partition zurück.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-122">Return the lease info for the specified partition.</span></span> <span data-ttu-id="c9e0a-123">Kann null zurück, wenn keine Lease im Speicher für die angegebene Partition erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-123">Can return null if no lease has been created in the store for the specified partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c9e0a-124">Lease-Informationen für die Partition, oder null</span><span class="sxs-lookup"><span data-stu-id="c9e0a-124">lease info for the partition, or null</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-125">Meistens zum Testen hilfreich.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-125">Mostly useful for testing.</span></span>
            </summary>
        <value><span data-ttu-id="c9e0a-126">Die Dauer eines Lease, bevor es abläuft, es sei denn, erneuert.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-126">Duration of a lease before it expires unless renewed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-127">Ermöglicht eine Lease-Manager-Implementierung PartitionManager angeben, wie oft Leases überprüfen und erneuern, werden sollte.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-127">Allows a lease manager implementation to specify to PartitionManager how often it should scan leases and renew them.</span></span> <span data-ttu-id="c9e0a-128">Um verteilen Leases rechtzeitig verarbeitet, nachdem ein Host wird nicht mehr funktioniert, empfiehlt es sich um einen relativ kurzen Intervall wie an den zehn Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-128">In order to redistribute leases in a timely fashion after a host ceases operating, we recommend a relatively short interval, such as ten seconds.</span></span> <span data-ttu-id="c9e0a-129">Selbstverständlich sollte weniger als die Hälfte der Lease length-Funktion, um eine versehentliche Ablauf zu verhindern können.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-129">Obviously it should be less than half of the lease length, to prevent accidental expiration.</span></span>
            </summary>
        <value><span data-ttu-id="c9e0a-130">Das Ruheintervall zwischen scans</span><span class="sxs-lookup"><span data-stu-id="c9e0a-130">The sleep interval between scans</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; LeaseStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; LeaseStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LeaseStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member LeaseStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.LeaseStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9e0a-131">Ist der Lease-Speicher vorhanden?</span><span class="sxs-lookup"><span data-stu-id="c9e0a-131">Does the lease store exist?</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ReleaseLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ReleaseLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.ReleaseLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.ReleaseLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="c9e0a-132">Leasedauer zugewiesen werden, einrichten</span><span class="sxs-lookup"><span data-stu-id="c9e0a-132">Lease to be given up</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-133">Geben Sie auf eine Lease, die derzeit von diesem Host aufrecht erhalten.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-133">Give up a lease currently held by this host.</span></span>
            <span data-ttu-id="c9e0a-134"><para>Wenn die Lease, abgelaufen sind oder gestohlen wurden, freigegeben wurde, ist nicht erforderlich, und schlägt fehl, wenn versucht.</para></span><span class="sxs-lookup"><span data-stu-id="c9e0a-134"><para>If the lease has been stolen, or expired, releasing it is unnecessary, and will fail if attempted.</para></span></span></summary>
        <returns><span data-ttu-id="c9e0a-135">"true", wenn die Lease erfolgreich, "false" ist dies nicht veröffentlicht wurde</span><span class="sxs-lookup"><span data-stu-id="c9e0a-135">true if the lease was released successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RenewLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; RenewLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.RenewLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.RenewLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="c9e0a-136">Lease erneuert werden soll.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-136">Lease to be renewed</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-137">Erneuert eine Lease, die derzeit von diesem Host aufrecht erhalten.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-137">Renew a lease currently held by this host.</span></span>
            
            <span data-ttu-id="c9e0a-138"><para>Wenn die Lease wurde gestohlen wird oder abgelaufen oder freigegeben wurde, ist es nicht möglich, es zu erneuern. Sie müssen Sie getLease(), und klicken Sie dann acquireLease() erneut aufrufen.</para></span><span class="sxs-lookup"><span data-stu-id="c9e0a-138"><para>If the lease has been stolen, or expired, or released, it is not possible to renew it. You will have to call getLease() and then acquireLease() again.</para></span></span></summary>
        <returns><span data-ttu-id="c9e0a-139">"true", wenn die Lease erfolgreich, "false" ist dies nicht der erneuert wurde</span><span class="sxs-lookup"><span data-stu-id="c9e0a-139">true if the lease was renewed successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; UpdateLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; UpdateLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.UpdateLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member UpdateLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.UpdateLeaseAsync lease" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="c9e0a-140">Neue Lease-Informationen gespeichert werden</span><span class="sxs-lookup"><span data-stu-id="c9e0a-140">New lease info to be stored</span></span></param>
        <summary>
            <span data-ttu-id="c9e0a-141">Aktualisieren Sie den Store mit den Informationen in der angegebenen Lease an.</span><span class="sxs-lookup"><span data-stu-id="c9e0a-141">Update the store with the information in the provided lease.</span></span>
            
            <span data-ttu-id="c9e0a-142"><para>Es ist notwendig, eine Lease aktuell zu halten, um es zu aktualisieren. Wenn die Lease wurde gestohlen wird oder abgelaufen oder freigegeben wurde, kann er nicht aktualisiert werden. Aktualisieren von sollte die Lease verlängern, vor dem Ausführen der Update aus, um den Ablauf der Lease während des Prozesses zu vermeiden.</para></span><span class="sxs-lookup"><span data-stu-id="c9e0a-142"><para>It is necessary to currently hold a lease in order to update it. If the lease has been stolen, or expired, or released, it cannot be updated. Updating should renew the lease before performing the update to avoid lease expiration during the process.</para></span></span></summary>
        <returns><span data-ttu-id="c9e0a-143">"true", wenn die aktualisierte erfolgreich, "false" ist dies nicht ausgeführt wurde</span><span class="sxs-lookup"><span data-stu-id="c9e0a-143">true if the updated was performed successfully, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>