<Type Name="StatefulServiceDescription" FullName="System.Fabric.Description.StatefulServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b31b4-101">Stellt das Erweitern <see cref="T:System.Fabric.Description.ServiceDescription" /> zum Bereitstellen zusätzlicher Informationen zum Erstellen von zustandsbehaftete Dienste erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="b31b4-101">Represents the extend <see cref="T:System.Fabric.Description.ServiceDescription" /> to provide additional information necessary to create stateful services.</span></span></para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.StatefulServiceDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b31b4-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.StatefulServiceDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-103">Ruft ab oder legt einen Wert, der angibt, ob diese Instanz einen persistenten Zustand aufweist.</span><span class="sxs-lookup"><span data-stu-id="b31b4-103">Gets or sets a value indicating whether this instance has persisted state.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="b31b4-104"><languageKeyword>"true"</languageKeyword> , wenn die Instanz, wechselt, andernfalls beibehalten wurde <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="b31b4-104"><languageKeyword>true</languageKeyword> if the instance has persisted state; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-105">Wenn eine <see cref="T:System.Fabric.FabricReplicator" /> an einem sekundären Replikat empfängt, einen Vorgang für einen permanenten Dienst, muss der Prinzipalserver wartet dabei für den Dienst zu bestätigen, dass die Daten persistent gespeichert wurde, bevor sie diese Bestätigung zurück an das primäre senden kann.</span><span class="sxs-lookup"><span data-stu-id="b31b4-105">When a <see cref="T:System.Fabric.FabricReplicator" /> at a secondary replica receives an operation for a persistent service, it must wait for the service to acknowledge that the data has been persisted before it can send that acknowledgment back to the primary.</span></span> <span data-ttu-id="b31b4-106">Für nicht persistente Dienste kann der Vorgang sofort nach Erhalt bestätigt werden.</span><span class="sxs-lookup"><span data-stu-id="b31b4-106">For non-persistent services, the operation can be acknowledged immediately upon receipt.</span></span></para>
          <para><span data-ttu-id="b31b4-107">Wenn ein Replikat der permanente Dienst ein Fehler auftritt, wird der Service Fabric nicht sofort dieses Replikat als verloren berücksichtigt, da für dieses Replikat der permanente Status noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="b31b4-107">When a persistent service replica fails, the Service Fabric will not immediately consider that replica as lost because the persistent state for that replica still exists.</span></span> <span data-ttu-id="b31b4-108">Wenn das Replikat wiederhergestellt wird, kann es mit dem beibehaltenen Zustand neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="b31b4-108">If the replica is recovered, it can be recreated using the persisted state.</span></span> <span data-ttu-id="b31b4-109">Im Gegensatz dazu ab, um ein Ersatz-Replikat sofort erstellen möglicherweise kostenintensive und unnötig, insbesondere, wenn die Fehler vorübergehend sind.</span><span class="sxs-lookup"><span data-stu-id="b31b4-109">In contrast, beginning to build a replacement replica immediately may be costly and unnecessary, especially when the failures are transient.</span></span> <span data-ttu-id="b31b4-110">Verwenden Sie zum Konfigurieren, wie lange Service Fabric warten soll, für die permanente Replikat her, bevor Sie ein neues Replikat für (Austausch) von Grund auf neu erstellen, die <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="b31b4-110">To configure how long Service Fabric should wait for the persistent replica to recover before building a new (replacement) replica from scratch, use the <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> parameter.</span></span> <span data-ttu-id="b31b4-111">Für nicht persistente Dienste (mit <see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" /> festgelegt <languageKeyword>"false"</languageKeyword>), Service Fabric beginnt sofort mit dem Erstellen eines neuen Replikats (da kein persistenten Zustand die Wiederherstellung, und daher kein Punkt beim Warten auf lokale Wiederherstellung ).</span><span class="sxs-lookup"><span data-stu-id="b31b4-111">For non-persistent services (those with <see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" /> set to <languageKeyword>false</languageKeyword>), Service Fabric will immediately begin creating a new replica (since there is no persistent state to recover from, and hence no point in waiting for local recovery).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public int MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-112">Ruft ab oder legt die zulässige Mindestgröße des Replikatsatzes Satz Größe für diesen Dienst fest.</span><span class="sxs-lookup"><span data-stu-id="b31b4-112">Gets or sets the minimum allowed replica set size for this service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b31b4-113">Der kleinste zulässige Größe des Replikats für diesen Dienst.</span><span class="sxs-lookup"><span data-stu-id="b31b4-113">The minimum allowed replica set size for this service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-114">Definiert die minimale Anzahl der Replikate, die Service Fabric in eine Ansicht der Replikatgruppe für eine bestimmte Partition beibehalten werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b31b4-114">Defines the minimum number of replicas that Service Fabric will keep in its view of the Replica Set for a given partition.</span></span> <span data-ttu-id="b31b4-115">Beispielsweise, wenn die <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> ist auf fünf (5) (fehlerfrei) normalerweise dann dort festgelegt werden fünf Replikate in der Ansicht des Replikatsatzes.</span><span class="sxs-lookup"><span data-stu-id="b31b4-115">For example, if the <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> is set to five (5) then normally (without failures) there will be five replicas in the view of the replica set.</span></span> <span data-ttu-id="b31b4-116">Diese Zahl wird jedoch bei Ausfällen verringern.</span><span class="sxs-lookup"><span data-stu-id="b31b4-116">However this number will decrease during failures.</span></span> <span data-ttu-id="b31b4-117">Die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> definiert die minimale Anzahl der Replikate in der Ansicht z. B. wenn die <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> werden fünf und die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> ist drei, und auch wenn drei gleichzeitiger Ausfälle (wodurch nur zwei verbleibenden Replikaten ausgeführt) werden, muss drei Replikate in der Ansicht der Replikatgruppe (zwei oben bzw. nach unten).</span><span class="sxs-lookup"><span data-stu-id="b31b4-117">The <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> defines the minimum number of replicas in the view, so for example if the <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> is five and the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> is three, then even if there are three concurrent failures (resulting  in only two remaining replicas running) will still have three replicas in its view of the replica set (two up and one down).</span></span> <span data-ttu-id="b31b4-118">Seit</span><span class="sxs-lookup"><span data-stu-id="b31b4-118">Since</span></span>  
            <span data-ttu-id="b31b4-119">verwendet mehrheitsquorummodus, der die Anzahl der Replikate, die in dieser Ansicht des mehrheitsquorummodus verwaltet die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> ist die minimale Maß an Zuverlässigkeit eines: im vorherigen Beispiel mit Ziel = 5 und Min = 3, mit 3 gleichzeitiger Ausfälle, es gibt zwei verbleibende einrichten Replikate (und ein nach unten), und die mehrheitsquorummodus 3 (die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) ist 2.</span><span class="sxs-lookup"><span data-stu-id="b31b4-119">uses majority quorum of the number of replicas maintained in this view, majority quorum of the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> is minimum level of reliability of any operation: in the prior example, with Target = 5 and Min = 3, with 3 concurrent failures, there are two remaining up replicas (and one down), and the majority quorum of 3 (the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) is 2.</span></span> <span data-ttu-id="b31b4-120">Dies bedeutet, dass der primären weiterhin Vorgänge replizieren können, dass es sich bei das verbleibende sekundäre Replikat den Vorgang in der Reihenfolge für das Replikat angewendet werden muss (Partition) Fortschritte festlegen.</span><span class="sxs-lookup"><span data-stu-id="b31b4-120">This means that the primary will continue to be able to replicate operations AND that the remaining secondary replica MUST apply the operation in order for the replica set (partition) to make progress.</span></span> <span data-ttu-id="b31b4-121">Wenn die Anzahl von Replikaten unter der mehrheitsquorummodus von fällt die <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> und weiteren Schreibvorgänge nicht zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="b31b4-121">If the total number of replicas drops below the majority quorum of the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> then further writes will be disallowed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-122">Ruft ab oder legt die maximale Dauer in Sekunden, für die eine Partition in einem Zustand des quorumverlusts sein darf.</span><span class="sxs-lookup"><span data-stu-id="b31b4-122">Gets or sets the maximum duration, in seconds, for which a partition is allowed to be in a state of quorum loss.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b31b4-123">Die Wartedauer als ein <see cref="T:System.TimeSpan" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b31b4-123">The wait duration as a <see cref="T:System.TimeSpan" /> object.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-124">Wenn die Partition noch quorumsverlust nach Ablauf dieses Zeitraums wird, wird die Partition von quorumsverlusten wiederhergestellt, Hinblick auf die nach-unten Replikate als verloren.</span><span class="sxs-lookup"><span data-stu-id="b31b4-124">If the partition is still in quorum loss after this duration, the partition is recovered from quorum loss by considering the down replicas as lost.</span></span> <span data-ttu-id="b31b4-125">Beachten Sie, dass dies möglicherweise Datenverluste verursachen kann.</span><span class="sxs-lookup"><span data-stu-id="b31b4-125">Note that this can potentially incur data loss.</span></span> <span data-ttu-id="b31b4-126">Der Standardwert ist unendlich, und es wird nicht empfohlen, diesen Wert zu ändern.</span><span class="sxs-lookup"><span data-stu-id="b31b4-126">The default value is Infinity and it is not recommended to change this value.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-127">Ruft ab oder legt die Dauer in Sekunden zwischen Wenn ein Replikat ausfällt und wann ein neues Replikat erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="b31b4-127">Gets or sets the duration, in seconds, between when a replica goes down and when a new replica is created.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b31b4-128">Die Dauer als ein <see cref="T:System.TimeSpan" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="b31b4-128">The duration as a <see cref="T:System.TimeSpan" /> object.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-129">Ein Replikat der permanente ausfällt, wird dieser Zeitgeber gestartet.</span><span class="sxs-lookup"><span data-stu-id="b31b4-129">When a persistent replica goes down, this timer starts.</span></span>  <span data-ttu-id="b31b4-130">Nach Ablauf der Evaluierung wird Service Fabric ein neues Replikat auf einem beliebigen Knoten im Cluster erstellt.</span><span class="sxs-lookup"><span data-stu-id="b31b4-130">When it expires Service Fabric will create a new replica on any node in the cluster.</span></span> <span data-ttu-id="b31b4-131">Diese Konfiguration ist um unnötige Zustand Kopien zu reduzieren.</span><span class="sxs-lookup"><span data-stu-id="b31b4-131">This configuration is to reduce unnecessary state copies.</span></span> <span data-ttu-id="b31b4-132">Wenn eine beibehaltene Replikat ausfällt, wird das System wartet, dafür für wiederkehren <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> Sekunden, bevor Sie ein neues Replikat die benötigen eine Kopie erstellen.</span><span class="sxs-lookup"><span data-stu-id="b31b4-132">When a persisted replica goes down, the system waits for it to come back up for <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> seconds before creating a new replica which will require a copy.</span></span> <span data-ttu-id="b31b4-133">Beachten Sie, dass ein Replikat, das nicht ausgeführt wird, nicht berücksichtigt wird verloren hat, noch.</span><span class="sxs-lookup"><span data-stu-id="b31b4-133">Note that a replica that is down is not considered lost, yet.</span></span></para>
          <para><span data-ttu-id="b31b4-134">Der Standardwert ist 300 (Sekunden).</span><span class="sxs-lookup"><span data-stu-id="b31b4-134">The default value is 300 (seconds).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b31b4-135">Ruft auf oder legt die Definition wie lange StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="b31b4-135">Gets or sets the definition on how long StandBy replicas should be maintained before being removed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b31b4-136">Die Definition für wie lange StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="b31b4-136">The definition on how long StandBy replicas should be maintained before being removed.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-137">In einigen Fällen ein Replikat wird inaktiv sein länger als die <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />.</span><span class="sxs-lookup"><span data-stu-id="b31b4-137">Sometimes a replica will be down for longer than the <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />.</span></span> <span data-ttu-id="b31b4-138">In diesen Fällen wird ein neues Replikat erstellt werden, um ihn zu ersetzen.</span><span class="sxs-lookup"><span data-stu-id="b31b4-138">In these cases a new replica will be built to replace it.</span></span> <span data-ttu-id="b31b4-139">In einigen Fällen wird jedoch zum Verlust nicht permanent ist und das Replikat der permanente schließlich wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="b31b4-139">Sometimes however the loss is not permanent and the persistent replica is eventually recovered.</span></span> <span data-ttu-id="b31b4-140">Nun bildet eine standbyreplikat.</span><span class="sxs-lookup"><span data-stu-id="b31b4-140">This now constitutes a StandBy replica.</span></span> <span data-ttu-id="b31b4-141">StandBy-Replikaten werden bevorzugt im Fall von nachfolgende Fehler oder Ressourcenausgleich für Aktionen, da sie bereits vorhanden ist und die verwendet werden können, um die Wiederherstellung zu beschleunigen, persistenten Status darstellen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b31b4-141">StandBy replicas will preferentially be used in the case of subsequent failures or resource balancing actions, since they represent persistent state that already exists and which can be used to expedite recovery.</span></span> <span data-ttu-id="b31b4-142">Die <see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" /> definiert, wie lange eine solche StandBy-Replikaten beibehalten werden soll, bevor Sie entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="b31b4-142">The <see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" /> defines how long such StandBy replicas should be maintained before being removed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public int TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> <span data-ttu-id="b31b4-143">Ruft ab oder legt die Zielgröße des Replikatsatzes.</span><span class="sxs-lookup"><span data-stu-id="b31b4-143">Gets or sets the target size of the replica set.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b31b4-144">Die Zielgröße des Replikatsatzes.</span><span class="sxs-lookup"><span data-stu-id="b31b4-144">The target size of the replica set.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b31b4-145">Die Anzahl der Replikate, die das System erstellt und verwaltet für jede Partition dieses Diensts.</span><span class="sxs-lookup"><span data-stu-id="b31b4-145">The number of replicas that the system creates and maintains for each partition of this service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>