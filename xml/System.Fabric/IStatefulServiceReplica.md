<Type Name="IStatefulServiceReplica" FullName="System.Fabric.IStatefulServiceReplica">
  <TypeSignature Language="C#" Value="public interface IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type IStatefulServiceReplica = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="a19ed-101">Definiert das Verhalten, die den Lebenszyklus eines Replikats, z. B. starten, Initialisierung, rollenänderungen und Herunterfahren bestimmt.</span><span class="sxs-lookup"><span data-stu-id="a19ed-101">Defines behavior that governs the lifecycle of a replica, such as startup, initialization, role changes, and shutdown.</span></span> </para>
    </summary>
    <remarks>
      <para>
                <span data-ttu-id="a19ed-102">Zustandsbehaftete Diensttypen müssen diese Schnittstelle implementieren.</span><span class="sxs-lookup"><span data-stu-id="a19ed-102">Stateful service types must implement this interface.</span></span> <span data-ttu-id="a19ed-103">Die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">zuverlässige Stateful Service</see> implementiert diese Schnittstelle und Replikat-Lebenszyklus intern behandelt.</span><span class="sxs-lookup"><span data-stu-id="a19ed-103">The <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">Reliable Stateful service</see> implements this interface and handles replica lifecycle internally.</span></span> </para>
      <para>
                <span data-ttu-id="a19ed-104">Die Logik der einen zustandsbehafteten Diensttyp enthält, die auf primären Replikaten aufgerufen wird und Verhalten, die auf sekundären Replikaten aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-104">The logic of a stateful service type includes behavior that is invoked on primary replicas and behavior that is invoked on secondary replicas.</span></span></para>
      <para>
                <span data-ttu-id="a19ed-105">Wenn dienstautor vornehmen möchte mithilfe des bereitgestellten <see cref="T:System.Fabric.FabricReplicator" />, und klicken Sie dann der Dienst, auch implementieren muss <see cref="T:System.Fabric.IStateProvider" /> verwenden Sie die Implementierung der <see cref="T:System.Fabric.IStateReplicator" /> , die vom bereitgestellt <see cref="T:System.Fabric.FabricReplicator" />.</span><span class="sxs-lookup"><span data-stu-id="a19ed-105">If the service author wants to make use of the provided <see cref="T:System.Fabric.FabricReplicator" />, then the service must also implement <see cref="T:System.Fabric.IStateProvider" /> to use the implementation of <see cref="T:System.Fabric.IStateReplicator" /> that is provided by <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatefulServiceReplica.Abort " />
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
          <para><span data-ttu-id="a19ed-106">Nicht ordnungsgemäß beendet die dienstreplikats.</span><span class="sxs-lookup"><span data-stu-id="a19ed-106">Ungracefully terminates the service replica.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="a19ed-107">Netzwerk-Probleme, wodurch Service Fabric-Prozess heruntergefahren und die Verwendung von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Bericht eine <see cref="F:System.Fabric.FaultType.Permanent" /> Fehler finden Sie Beispiele für geordnete und ungeordnete Abbrüche beenden.</span><span class="sxs-lookup"><span data-stu-id="a19ed-107">Network issues resulting in Service Fabric process shutdown and the use of <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> to report a <see cref="F:System.Fabric.FaultType.Permanent" /> fault are examples of ungraceful termination.</span></span> <span data-ttu-id="a19ed-108">Wenn diese Methode aufgerufen wird, sollten die dienstreplikats sofort freigeben und bereinigen Sie alle Verweise und zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="a19ed-108">When this method is invoked, the service replica should immediately release and clean up all references and return.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatefulServiceReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para><span data-ttu-id="a19ed-109">Die aktualisierte <see cref="T:System.Fabric.ReplicaRole" /> , die dieses Replikat zum übergehen soll.</span><span class="sxs-lookup"><span data-stu-id="a19ed-109">The updated <see cref="T:System.Fabric.ReplicaRole" /> that this replica should transition to.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="a19ed-110">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a19ed-110">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a19ed-111">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a19ed-111">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="a19ed-112">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="a19ed-113">Ändert die Rolle des Replikats Service in eines der <see cref="T:System.Fabric.ReplicaRole" />.</span><span class="sxs-lookup"><span data-stu-id="a19ed-113">Changes the role of the service replica to one of the <see cref="T:System.Fabric.ReplicaRole" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="a19ed-114">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.String" />, der Dienst neue Adresse für die Verbindung, die über die Benennung von Service Fabric-Replikat zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a19ed-114">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.String" />, the service’s new connection address that is to be associated with the replica via Service Fabric Naming.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="a19ed-115">Die neue Rolle wird als Parameter angegeben.</span><span class="sxs-lookup"><span data-stu-id="a19ed-115">The new role is indicated as a parameter.</span></span> <span data-ttu-id="a19ed-116">Wenn die Dienst-Übergänge in die neue Rolle, verfügt der Dienst eine Möglichkeit, ihre aktuellen abhöradresse zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="a19ed-116">When the service transitions to the new role, the service has a chance to update its current listening address.</span></span>
            <span data-ttu-id="a19ed-117">Die abhöradresse ist die Adresse, in dem Clients eine Verbindung herstellen, und die über zurückgegeben, der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API.</span><span class="sxs-lookup"><span data-stu-id="a19ed-117">The listening address is the address where clients connect to it and the one returned via the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API.</span></span> <span data-ttu-id="a19ed-118">Dies ermöglicht dem Dienst wird ein primäres Replikat, Anspruch nur einige Ressourcen wie z. B. Ports aus, bei der Kommunikation von Clients erwartet wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-118">This enables the service when it is a primary replica to only claim some resources such as ports when communication from clients is expected.</span></span></para>
          <seealso href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-communication" />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatefulServiceReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="a19ed-119">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a19ed-119">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a19ed-120">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a19ed-120">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a19ed-121">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-121">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="a19ed-122">Schließt die dienstreplikats ordnungsgemäß, wenn er heruntergefahren wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-122">Closes the service replica gracefully when it is being shut down.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="a19ed-123">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="a19ed-123">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="iStatefulServiceReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="a19ed-124">Die <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> für dieses Replikat.</span><span class="sxs-lookup"><span data-stu-id="a19ed-124">The <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> for this replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="a19ed-125">Initialisiert eine neu erstellte dienstreplikats an.</span><span class="sxs-lookup"><span data-stu-id="a19ed-125">Initializes a newly created service replica.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="iStatefulServiceReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para><span data-ttu-id="a19ed-126">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a19ed-126">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="partition">
          <para><span data-ttu-id="a19ed-127">Die <see cref="T:System.Fabric.IStatefulServicePartition" /> Informationen für dieses Replikat.</span><span class="sxs-lookup"><span data-stu-id="a19ed-127">The <see cref="T:System.Fabric.IStatefulServicePartition" /> information for this replica.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="a19ed-128">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a19ed-128">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="a19ed-129">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="a19ed-129">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="a19ed-130">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-130">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="a19ed-131">Wird ein initialisierter dienstreplikats geöffnet, sodass zusätzliche Aktionen ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="a19ed-131">Opens an initialized service replica so that additional actions can be taken.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="a19ed-132">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> &lt; <see cref="T:System.Fabric.IReplicator" /> &gt;, <see cref="T:System.Fabric.IReplicator" /> , das von der zustandsbehaftete Dienst verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a19ed-132">Returns <see cref="T:System.Threading.Tasks.Task`1" />&lt;<see cref="T:System.Fabric.IReplicator" />&gt;, the <see cref="T:System.Fabric.IReplicator" /> that is used by the stateful service.</span></span> <span data-ttu-id="a19ed-133">Verwenden Sie die Service Fabric-Implementierung in <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />, sollte das Replikat Zurückgeben einer <see cref="T:System.Fabric.FabricReplicator" /> abgerufener <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span><span class="sxs-lookup"><span data-stu-id="a19ed-133">To use the Service Fabric implementation, in <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />, the replica should return a <see cref="T:System.Fabric.FabricReplicator" /> that is obtained from  <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>