<Type Name="RestoreContext" FullName="Microsoft.ServiceFabric.Data.RestoreContext">
  <TypeSignature Language="C#" Value="public struct RestoreContext" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreContext extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreContext" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreContext" />
  <TypeSignature Language="F#" Value="type RestoreContext = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <span data-ttu-id="56f09-101"><cref name="RestoreContext" />enthält die <cref name="RestoreContext.RestoreAsync(RestoreDescription)" /> , die verwendet werden kann, um den Status des Replikats aus einer Sicherung wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="56f09-101"><cref name="RestoreContext" /> contains the <cref name="RestoreContext.RestoreAsync(RestoreDescription)" /> that can be used to restore the state of the replica from a backup.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreContext (Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.#ctor(Microsoft.ServiceFabric.Data.IStateProviderReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (stateProviderReplica As IStateProviderReplica)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreContext : Microsoft.ServiceFabric.Data.IStateProviderReplica -&gt; Microsoft.ServiceFabric.Data.RestoreContext" Usage="new Microsoft.ServiceFabric.Data.RestoreContext stateProviderReplica" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica" />
      </Parameters>
      <Docs>
        <param name="stateProviderReplica">
            <span data-ttu-id="56f09-102">Eine <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> , die ein Replikat des zuverlässigen Zustand Anbieter darstellt.</span><span class="sxs-lookup"><span data-stu-id="56f09-102">An <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> representing a reliable state provider replica.</span></span>
            </param>
        <summary>
            <span data-ttu-id="56f09-103">Initialisiert eine neue Instanz der <cref name="RestoreContext" />-Struktur.</span><span class="sxs-lookup"><span data-stu-id="56f09-103">Initializes a new instance of the <cref name="RestoreContext" /> structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync restoreDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
      </Parameters>
      <Docs>
        <param name="restoreDescription"><span data-ttu-id="56f09-104">Beschreibung für die Anforderung zum Wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="56f09-104">Description for the restore request.</span></span></param>
        <summary>
            <span data-ttu-id="56f09-105">Eine Sicherung von beschriebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span><span class="sxs-lookup"><span data-stu-id="56f09-105">Restores a backup described by <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="56f09-106">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="56f09-106">Task that represents the asynchronous restore operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="56f09-107">Diese API muss von OnDataLossAsync-Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="56f09-107">This API must be called from OnDataLossAsync method.</span></span> <span data-ttu-id="56f09-108">Nur ein RestoreAsync-API kann in-Flight pro Replikat zu einem bestimmten Zeitpunkt Zeit sein.</span><span class="sxs-lookup"><span data-stu-id="56f09-108">Only one RestoreAsync API can be inflight per replica at any given point of time.</span></span>
            
            <span data-ttu-id="56f09-109">Beachten Sie, dass diese API ausgelöste Ausnahmen abhängig von zugrunde liegenden zustandsanbieter unterscheiden.</span><span class="sxs-lookup"><span data-stu-id="56f09-109">Note that exceptions thrown by this API differ depending on of underlying state provider.</span></span> <span data-ttu-id="56f09-110">Die Ausnahmen, die für diese API nur für die Out-of-Box-Status-Anbieter von Service Fabric bereitgestellt wird, für zuverlässige Dienste und Reliable Actors gilt derzeit dokumentiert sind.</span><span class="sxs-lookup"><span data-stu-id="56f09-110">The exceptions that are currently documented for this API applies only to out-of-box state providers provided by Service Fabric for Reliable Services and Reliable Actors.</span></span>
            <span data-ttu-id="56f09-111"><para>Folgende Ausnahmen werden ausgelöst, über diese API, wenn die im zuverlässigen Dienst aufgerufen: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list> </para> <para> Folgende Ausnahmen werden über diese API, wenn im Akteur-Dienst mit KvsActorStateProvider als seine State-Anbieter aufgerufen wird (also den Status Standardanbieter für Reliable Actors) ausgelöst:<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span><span class="sxs-lookup"><span data-stu-id="56f09-111"><para> Following exceptions are thrown by this API when invoked in Reliable Service: <list type="bullet"><item><description><see cref="T:System.Fabric.FabricMissingFullBackupException" /></description></item><item><description><see cref="T:System.ArgumentException" /></description></item></list></para><para> Following exceptions are thrown by this API when invoked in Actor Service with KvsActorStateProvider as its state provider (which is the default state provider for Reliable Actors): <list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span></span></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            <span data-ttu-id="56f09-112">Gibt an, dass die Eingabe Sicherungsordner keine vollständige Sicherung enthält.</span><span class="sxs-lookup"><span data-stu-id="56f09-112">Indicates that the input backup folder does not contain a full backup.</span></span>
            <span data-ttu-id="56f09-113">Für einen Sicherungsordner wiederherstellbar sein muss sie genau eine vollständige Sicherung und eine beliebige Anzahl von inkrementellen Sicherungen enthalten.</span><span class="sxs-lookup"><span data-stu-id="56f09-113">For a backup folder to be restorable, it must contain exactly one full backup and any number of incremental backups.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="56f09-114">Gibt an, dass eines der Argumente nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-114">Indicates that one of the arguments is not valid.</span></span> <span data-ttu-id="56f09-115">Z. B. wenn zuverlässig wiederherstellen, wenn RestorePolicy Safe, aber die Eingabe Sicherungsordner festgelegt ist eine Version des Status enthält, die älter als der Status, in das aktuelle Replikat beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="56f09-115">For example, when restoring a Reliable Service if RestorePolicy is set to Safe, but the input backup folder contains a version of the state that is older than the state maintained in the current replica.</span></span>
            
            <span data-ttu-id="56f09-116">Beim Wiederherstellen von einem Akteur-Dienst wird diese Ausnahme ausgelöst, wenn der angegebene <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> ist leer.</span><span class="sxs-lookup"><span data-stu-id="56f09-116">When restoring an Actor Service this exception is thrown if specified <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> is empty.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            <span data-ttu-id="56f09-117">Gibt an, dass die Wiederherstellung angegebene Verzeichnis nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-117">Indicates that the supplied restore directory does not exist.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            <span data-ttu-id="56f09-118">Gibt an, dass das Replikat geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="56f09-118">Indicates that the replica is closing.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="56f09-119">Gibt an, dass die aktuellen Restore-Vorgang ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-119">Indicates that current restore operation is not valid.</span></span> <span data-ttu-id="56f09-120">Z. B. die <see cref="T:System.Fabric.ServicePartitionKind" /> der Partition aus, in dem Sicherung erstellt wurde unterscheidet sich von der aktuellen Partition, die wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="56f09-120">For example, the <see cref="T:System.Fabric.ServicePartitionKind" /> of the partition from where backup was taken is different than that of current partition being restored.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="56f09-121">Gibt an, die erwartete Sicherungsdateien unter dem angegebenen Restore-Verzeichnis wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="56f09-121">Indicates the expected backup files under the supplied restore directory is not found.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="56f09-122">Gibt an, der Restore-Vorgang ist einen unerwarteter Fehler aufgetreten, oder die Sicherungsdateien im Restore-Verzeichnis sind nicht gültig.</span><span class="sxs-lookup"><span data-stu-id="56f09-122">Indicates either the restore operation encountered an unexpected error or the backup files in restore directory are not valid.</span></span>
            <span data-ttu-id="56f09-123">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft gibt den Typ des aufgetretenen Fehlers.</span><span class="sxs-lookup"><span data-stu-id="56f09-123">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property indicates the type of error that occurred.</span></span>
            <span data-ttu-id="56f09-124"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>Gibt an, dass die Sicherungsdateien in das Verzeichnis für die Wiederherstellung angegebene entweder fehlen Dateien oder über zusätzliche unerwartete Dateien. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>Gibt an, dass die Metadatendateien (restore.dat) im Verzeichnis der Wiederherstellung ist entweder beschädigt oder enthält ungültige Daten. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) angegebene Verzeichnis bei der Wiederherstellung ist unterbrochen. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) bereitgestellten bei der Wiederherstellung Verzeichnis doppelte Sicherungen enthält. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>Wenn <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> wird im Rahmen des angegebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, bedeutet dies, dass die Sicherung, Wiederherstellung vorgesehenen ältere Daten als die zurzeit im Dienst vorhanden ist.</description></item></list></span><span class="sxs-lookup"><span data-stu-id="56f09-124"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description> Indicates that the backup files supplied in the restore directory are either missing files or have extra unexpected files. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description> Indicates that metadata files (restore.dat) present in restore directory is either corrupt or contains invalid information. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory is broken. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory contains duplicate backups. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description> If <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> is specified as part of <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, it indicates that the backup provided for restore has older data than currently present in service. </description></item></list></span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync (restoreDescription, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreDescription"><span data-ttu-id="56f09-125">Beschreibung für die Anforderung zum Wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="56f09-125">Description for the restore request.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="56f09-126">Das Token zum überwachen von Abbruchanforderungen.</span><span class="sxs-lookup"><span data-stu-id="56f09-126">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="56f09-127">Wiederherstellen einer Sicherung von beschriebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span><span class="sxs-lookup"><span data-stu-id="56f09-127">Restore a backup described by <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="56f09-128">Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="56f09-128">Task that represents the asynchronous restore operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="56f09-129">Diese API muss von OnDataLossAsync-Methode aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="56f09-129">This API must be called from OnDataLossAsync method.</span></span> <span data-ttu-id="56f09-130">Nur ein RestoreAsync-API kann in-Flight pro Replikat zu einem bestimmten Zeitpunkt Zeit sein.</span><span class="sxs-lookup"><span data-stu-id="56f09-130">Only one RestoreAsync API can be inflight per replica at any given point of time.</span></span>
            
            <span data-ttu-id="56f09-131">Beachten Sie, dass diese API ausgelöste Ausnahmen abhängig von zugrunde liegenden zustandsanbieter unterscheiden.</span><span class="sxs-lookup"><span data-stu-id="56f09-131">Note that exceptions thrown by this API differ depending on of underlying state provider.</span></span> <span data-ttu-id="56f09-132">Die Ausnahmen, die für diese API nur für die Out-of-Box-Status-Anbieter von Service Fabric bereitgestellt wird, für zuverlässige Dienste und Reliable Actors gilt derzeit dokumentiert sind.</span><span class="sxs-lookup"><span data-stu-id="56f09-132">The exceptions that are currently documented for this API applies only to out-of-box state providers provided by Service Fabric for Reliable Services and Reliable Actors.</span></span>
            <span data-ttu-id="56f09-133"><para>Folgende Ausnahmen werden ausgelöst, über diese API, wenn die im zuverlässigen Dienst aufgerufen: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list> </para> <para> Folgende Ausnahmen werden über diese API, wenn im Akteur-Dienst mit KvsActorStateProvider als seine State-Anbieter aufgerufen wird (also den Status Standardanbieter für Reliable Actors) ausgelöst:<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span><span class="sxs-lookup"><span data-stu-id="56f09-133"><para> Following exceptions are thrown by this API when invoked in Reliable Service: <list type="bullet"><item><description><see cref="T:System.Fabric.FabricMissingFullBackupException" /></description></item><item><description><see cref="T:System.ArgumentException" /></description></item></list></para><para> Following exceptions are thrown by this API when invoked in Actor Service with KvsActorStateProvider as its state provider (which is the default state provider for Reliable Actors): <list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span></span></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            <span data-ttu-id="56f09-134">Gibt an, dass die Eingabe Sicherungsordner keine vollständige Sicherung enthält.</span><span class="sxs-lookup"><span data-stu-id="56f09-134">Indicates that the input backup folder does not contain a full backup.</span></span>
            <span data-ttu-id="56f09-135">Für einen Sicherungsordner wiederherstellbar sein muss sie genau eine vollständige Sicherung und eine beliebige Anzahl von inkrementellen Sicherungen enthalten.</span><span class="sxs-lookup"><span data-stu-id="56f09-135">For a backup folder to be restorable, it must contain exactly one full backup and any number of incremental backups.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="56f09-136">Gibt an, dass eines der Argumente nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-136">Indicates that one of the arguments is not valid.</span></span> <span data-ttu-id="56f09-137">Z. B. wenn zuverlässig wiederherstellen, wenn RestorePolicy Safe, aber die Eingabe Sicherungsordner festgelegt ist eine Version des Status enthält, die älter als der Status, in das aktuelle Replikat beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="56f09-137">For example, when restoring a Reliable Service if RestorePolicy is set to Safe, but the input backup folder contains a version of the state that is older than the state maintained in the current replica.</span></span>
            
            <span data-ttu-id="56f09-138">Beim Wiederherstellen von einem Akteur-Dienst wird diese Ausnahme ausgelöst, wenn der angegebene <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> ist leer.</span><span class="sxs-lookup"><span data-stu-id="56f09-138">When restoring an Actor Service this exception is thrown if specified <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> is empty.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            <span data-ttu-id="56f09-139">Gibt an, dass die Wiederherstellung angegebene Verzeichnis nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-139">Indicates that the supplied restore directory does not exist.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            <span data-ttu-id="56f09-140">Gibt an, dass das Replikat geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="56f09-140">Indicates that the replica is closing.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="56f09-141">Gibt an, dass die aktuellen Restore-Vorgang ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="56f09-141">Indicates that current restore operation is not valid.</span></span> <span data-ttu-id="56f09-142">Z. B. die <see cref="T:System.Fabric.ServicePartitionKind" /> der Partition aus, in dem Sicherung erstellt wurde unterscheidet sich von der aktuellen Partition, die wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="56f09-142">For example, the <see cref="T:System.Fabric.ServicePartitionKind" /> of the partition from where backup was taken is different than that of current partition being restored.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="56f09-143">Gibt an, die erwartete Sicherungsdateien unter dem angegebenen Restore-Verzeichnis wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="56f09-143">Indicates the expected backup files under the supplied restore directory is not found.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="56f09-144">Gibt an, der Restore-Vorgang ist einen unerwarteter Fehler aufgetreten, oder die Sicherungsdateien im Restore-Verzeichnis sind nicht gültig.</span><span class="sxs-lookup"><span data-stu-id="56f09-144">Indicates either the restore operation encountered an unexpected error or the backup files in restore directory are not valid.</span></span>
            <span data-ttu-id="56f09-145">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft gibt den Typ des aufgetretenen Fehlers.</span><span class="sxs-lookup"><span data-stu-id="56f09-145">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property indicates the type of error that occurred.</span></span>
            <span data-ttu-id="56f09-146"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>Gibt an, dass die Sicherungsdateien in das Verzeichnis für die Wiederherstellung angegebene entweder fehlen Dateien oder über zusätzliche unerwartete Dateien. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>Gibt an, dass die Metadatendateien (restore.dat) im Verzeichnis der Wiederherstellung ist entweder beschädigt oder enthält ungültige Daten. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) angegebene Verzeichnis bei der Wiederherstellung ist unterbrochen. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) bereitgestellten bei der Wiederherstellung Verzeichnis doppelte Sicherungen enthält. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>Wenn <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> wird im Rahmen des angegebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, bedeutet dies, dass die Sicherung, Wiederherstellung vorgesehenen ältere Daten als die zurzeit im Dienst vorhanden ist.</description></item></list></span><span class="sxs-lookup"><span data-stu-id="56f09-146"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description> Indicates that the backup files supplied in the restore directory are either missing files or have extra unexpected files. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description> Indicates that metadata files (restore.dat) present in restore directory is either corrupt or contains invalid information. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory is broken. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory contains duplicate backups. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description> If <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> is specified as part of <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, it indicates that the backup provided for restore has older data than currently present in service. </description></item></list></span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>