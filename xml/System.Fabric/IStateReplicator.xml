<Type Name="IStateReplicator" FullName="System.Fabric.IStateReplicator">
  <TypeSignature Language="C#" Value="public interface IStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateReplicator" />
  <TypeSignature Language="F#" Value="type IStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="77d33-101">Macht Funktionen im Zusammenhang mit Replikation, von der <see cref="T:System.Fabric.FabricReplicator" /> Klasse, mit denen <see cref="T:System.Fabric.IStateProvider" /> zum Replizieren von Zustand, um hohe Verfügbarkeit sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="77d33-101">Exposes replication-related functions of the <see cref="T:System.Fabric.FabricReplicator" /> class that are used by <see cref="T:System.Fabric.IStateProvider" /> to replicate state to ensure high availability.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetCopyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetCopyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetCopyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetCopyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="77d33-102">Ruft kopieren Stream.</span><span class="sxs-lookup"><span data-stu-id="77d33-102">Gets copy stream.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="77d33-103">Gibt die Kopie zurück <see cref="T:System.Fabric.IOperationStream" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-103">Returns the copy <see cref="T:System.Fabric.IOperationStream" />.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="77d33-104">Die zurückgegebenen CopyStream ist ein <see cref="T:System.Fabric.IOperationStream" /> enthält <see cref="T:System.Fabric.OperationData" /> Objekten implementiert, <see cref="T:System.Fabric.IOperation" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-104">The returned CopyStream is an <see cref="T:System.Fabric.IOperationStream" /> that contains <see cref="T:System.Fabric.OperationData" /> objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="77d33-105">Die <see cref="T:System.Fabric.OperationData" /> -Objekte werden abgerufen, von der CopyState <see cref="T:System.Fabric.IOperationDataStream" /> , die das primäre Replikat zurückgibt <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-105">The <see cref="T:System.Fabric.OperationData" /> objects are obtained from the CopyState <see cref="T:System.Fabric.IOperationDataStream" /> that the Primary replica returns from <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span> <span data-ttu-id="77d33-106">Wenn ein Replikat erstellt und auf den aktuellen Stand ist, erhalten die CopyStream und sollte beginnen zu senden, anwenden und bestätigen das Kopieren von Objekten, die implementieren <see cref="T:System.Fabric.IOperation" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-106">When a replica is created and has to catch up, it should obtain the CopyStream and begin to send, apply, and acknowledge the Copy objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="77d33-107">Parallel, reagiert das Replikat auf den entsprechenden <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> und <see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" /> aufrufen.</span><span class="sxs-lookup"><span data-stu-id="77d33-107">In parallel, the replica responds to the corresponding <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> and <see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" /> calls.</span></span> <span data-ttu-id="77d33-108">Der Datenstrom ist leer, wenn das zurückgegebene <see cref="T:System.Fabric.IOperation" /> Methode ist null.</span><span class="sxs-lookup"><span data-stu-id="77d33-108">The stream is empty when the returned <see cref="T:System.Fabric.IOperation" /> method is null.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="77d33-109"><see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="77d33-109"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="77d33-110">Es ist eines der folgenden; zurückzuführen</span><span class="sxs-lookup"><span data-stu-id="77d33-110">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-111"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</span><span class="sxs-lookup"><span data-stu-id="77d33-111"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="77d33-112"><see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</span><span class="sxs-lookup"><span data-stu-id="77d33-112"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-113"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-113"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetReplicationStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetReplicationStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetReplicationStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicationStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetReplicationStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetReplicationStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="77d33-114">Ruft die replikationsdatenstrom ab.</span><span class="sxs-lookup"><span data-stu-id="77d33-114">Gets replication stream.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="77d33-115">Gibt die Replikation <see cref="T:System.Fabric.IOperationStream" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-115">Returns the replication <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="77d33-116">Implementiert die ReplicationStream <see cref="T:System.Fabric.IOperationStream" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-116">The ReplicationStream implements <see cref="T:System.Fabric.IOperationStream" />.</span></span> <span data-ttu-id="77d33-117">Enthält die ReplicationStream <see cref="T:System.Fabric.OperationData" /> Objekten implementiert, <see cref="T:System.Fabric.IOperation" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-117">The ReplicationStream contains <see cref="T:System.Fabric.OperationData" /> objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="77d33-118">Die Objekte werden vom primären Replikat über bereitgestellt <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-118">The objects are provided by the Primary replica via <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> <span data-ttu-id="77d33-119">Im Allgemeinen sollte ein sekundäres Replikat senden <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-119">Generally a Secondary replica should send <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="77d33-120">Service Fabric Services dazu nicht notwendig, in der Regel Dienste sollten alle übertragen <see cref="T:System.Fabric.OperationData" /> Objekten aus der Kopie zuerst zu streamen, übertragen und dann Vorgänge aus dem replikationsdatenstrom.</span><span class="sxs-lookup"><span data-stu-id="77d33-120">Although Service Fabric does not require services to do so, generally services should transfer all <see cref="T:System.Fabric.OperationData" /> objects out of the copy stream first, and then transfer operations out of the replication stream.</span></span> <span data-ttu-id="77d33-121">Die Übertragung von beide Kopien parallel wird unterstützt, aber erhöht die Komplexität des Anwendens der Zustand ordnungsgemäß aktualisiert und wird nur für erweiterte Dienste empfohlen.</span><span class="sxs-lookup"><span data-stu-id="77d33-121">The transfer from both copies in parallel is supported but increases the complexity of applying state updates correctly and is recommended only for advanced services.</span></span> <span data-ttu-id="77d33-122">Der Datenstrom ist leer, wenn das zurückgegebene <see cref="T:System.Fabric.IOperation" /> Methode ist null.</span><span class="sxs-lookup"><span data-stu-id="77d33-122">The stream is empty when the returned <see cref="T:System.Fabric.IOperation" /> method is null.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="77d33-123"><see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="77d33-123"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="77d33-124">Es ist eines der folgenden; zurückzuführen</span><span class="sxs-lookup"><span data-stu-id="77d33-124">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-125"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</span><span class="sxs-lookup"><span data-stu-id="77d33-125"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="77d33-126"><see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</span><span class="sxs-lookup"><span data-stu-id="77d33-126"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-127"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-127"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAsync (System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAsync(class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAsync : System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iStateReplicator.ReplicateAsync (operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para><span data-ttu-id="77d33-128">Die <see cref="T:System.Fabric.OperationData" /> , die die Änderung des Zustands, die das primäre Replikat replizieren möchte darstellt.</span><span class="sxs-lookup"><span data-stu-id="77d33-128">The <see cref="T:System.Fabric.OperationData" /> that represents the state change that the Primary replica wants to replicate.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para> <span data-ttu-id="77d33-129">Ein Schreibvorgang Quorum der Replikate, die verloren gegangen sein.</span><span class="sxs-lookup"><span data-stu-id="77d33-129">A write quorum of replicas that have been lost.</span></span> <span data-ttu-id="77d33-130">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="77d33-130">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="77d33-131">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="77d33-131">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="sequenceNumber">
          <para><span data-ttu-id="77d33-132">Lange, die LSN des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="77d33-132">Long, the LSN of the operation.</span></span> <span data-ttu-id="77d33-133">Beachten Sie, dass dies der gleiche Wert zurückgegeben, von der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="77d33-133">Note that this is the same value which is returned by the task.</span></span> <span data-ttu-id="77d33-134">Bereitstellen als Out-Parameter ist nützlich für Dienste, die vorzubereitenden lokalen Schreibzugriffs auf übertragen, wenn die Aufgabe abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="77d33-134">Providing it as an out parameter is useful for services which want to prepare the local write to commit when the task finishes.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="77d33-135">Zustandsänderungen aus dem primären Replikat an die sekundären Replikate repliziert und empfängt eine Quorum-Bestätigung, dass diese Änderungen angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="77d33-135">Replicates state changes from Primary replica to the Secondary replicas and receives a quorum acknowledgement that those state changes have been applied.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="77d33-136">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="77d33-136">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="77d33-137">Replikation auf dem primären Replikat erzeugt, die Objekte, die implementieren <see cref="T:System.Fabric.IOperation" /> , aus dem Replikationsstream über das sekundäre Replikat übernimmt <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />, gefolgt von <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-137">Replication at the Primary replica produces the objects that implement <see cref="T:System.Fabric.IOperation" /> that the Secondary replica obtains from the Replication Stream via <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />, which is followed by <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span></span> </para>
          <para><span data-ttu-id="77d33-138">Das primäre Replikat verfügt über viele Aufgaben, die verknüpft sind, um statusaktualisierungen zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="77d33-138">The Primary replica has many duties that are related to process state updates.</span></span> <span data-ttu-id="77d33-139">Die folgenden Schritte zeigen die allgemeine Abfolge der Ereignisse, die ein primäres Replikat behandelt werden muss, für die Replikation und eine Änderung zu bestätigen.</span><span class="sxs-lookup"><span data-stu-id="77d33-139">The following steps show the general sequence of events that a Primary replica must handle to replicate and acknowledge a change.</span></span> </para>
          <para><span data-ttu-id="77d33-140">Teil 1: Behandlung von eingehenden Anforderungen: Empfangen der Anforderung: Write(x) – Dienst empfängt eine schreibanforderung X.</span><span class="sxs-lookup"><span data-stu-id="77d33-140">Part 1: Handling incoming requests: Receive request: Write(x) – Service receives a write request, x.</span></span> <span data-ttu-id="77d33-141">CheckArguments – der Dienst überprüft die Argumente der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="77d33-141">CheckArguments – The service checks the arguments of the request.</span></span> <span data-ttu-id="77d33-142">Diese Überprüfung sichergestellt, dass die Konsistenz der Zustand des Diensts.</span><span class="sxs-lookup"><span data-stu-id="77d33-142">This check helps ensure the consistency of the service’s state.</span></span></para>
          <para><span data-ttu-id="77d33-143">Aktuellen Status Überprüfen – der Dienst überprüft seinem aktuellen Status, um sicherzustellen, dass der Vorgang gültig ist und kann oder ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="77d33-143">Check current state – The service examines its current state to ensure that the operation is valid and can or should be performed.</span></span> <span data-ttu-id="77d33-144">Diese Prüfung kann auch die Datenkonsistenz sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="77d33-144">This check also helps ensure data consistency.</span></span> <span data-ttu-id="77d33-145">Es wird von der Dienstcode ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="77d33-145">It is performed by the service code.</span></span></para>
          <para><span data-ttu-id="77d33-146">Sperren: der Dienst sollte die erforderlichen sperren, um zu verhindern, dass zusätzliche Vorgänge zur gleichen Zeit auftreten von abrufen.</span><span class="sxs-lookup"><span data-stu-id="77d33-146">Acquire Locks – The service should acquire the necessary locks to prevent additional operations from occurring at the same time.</span></span> <span data-ttu-id="77d33-147">Dieser Vorgang hilft dabei, Isolation und Konsistenz gewährleistet.</span><span class="sxs-lookup"><span data-stu-id="77d33-147">This operation helps ensure isolation and consistency.</span></span></para>
          <para><span data-ttu-id="77d33-148">Versuch-Vorgang (optional) – der Dienst den Vorgang lokal ausführen kann.</span><span class="sxs-lookup"><span data-stu-id="77d33-148">Attempt Operation (optional) – The service can attempt the operation locally.</span></span> <span data-ttu-id="77d33-149">Dieser Schritt reserviert und Speicherplatz belegt und die notwendigen Berechnungen ausführt.</span><span class="sxs-lookup"><span data-stu-id="77d33-149">This step reserves and allocates space and performs all the necessary computations.</span></span> <span data-ttu-id="77d33-150">Dieser Schritt umfasst alle Elemente außer den eigentlichen Commit des Ergebnisses.</span><span class="sxs-lookup"><span data-stu-id="77d33-150">This step includes everything but the actual commit of the result.</span></span> <span data-ttu-id="77d33-151">Dieser Vorgang verbessert die Dauerhaftigkeit des Vorgangs und höher Fehler sehr unwahrscheinlich ist.</span><span class="sxs-lookup"><span data-stu-id="77d33-151">This operation improves the durability of the operation and makes later failures very unlikely.</span></span></para>
          <para><span data-ttu-id="77d33-152">Herstellung OperationData – ein <see cref="T:System.Fabric.OperationData" /> Objekt ist die Darstellung der Write(x), die der Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-152">Manufacture the OperationData – An <see cref="T:System.Fabric.OperationData" /> object is the representation of the Write(x) that was presented to the service.</span></span> <span data-ttu-id="77d33-153">Die <see cref="T:System.Fabric.OperationData" /> Objekt enthält die statusänderung auf der sekundären Replikate mit Bestätigung vom primären Replikat übertragen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="77d33-153">The <see cref="T:System.Fabric.OperationData" /> object contains the state change to be transferred with acknowledgement from the Primary replica to the Secondary replicas.</span></span> <span data-ttu-id="77d33-154">Die Daten, die der Dienst in der OperationData platziert definiert den atomaren zu aktualisieren, die die <see cref="T:System.Fabric.FabricReplicator" /> Übertragungen an die sekundären Replikate.</span><span class="sxs-lookup"><span data-stu-id="77d33-154">The data that the service places in the OperationData defines the atomic update that the <see cref="T:System.Fabric.FabricReplicator" /> transfers to the Secondary replicas.</span></span> <span data-ttu-id="77d33-155">Beachten Sie, dass das Erstellen von der <see cref="T:System.Fabric.OperationData" /> Objekt erfordert mindestens ein Byte-Arrays.</span><span class="sxs-lookup"><span data-stu-id="77d33-155">Note that creating of the <see cref="T:System.Fabric.OperationData" /> object requires one or more byte arrays.</span></span> <span data-ttu-id="77d33-156">Der Dienst selbst zu bestimmen und Serialisieren Sie die Änderung am Zustand, und geben Sie dieser Gruppe von Bytes auf die FabricReplicator über muss <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span><span class="sxs-lookup"><span data-stu-id="77d33-156">The service must itself determine and serialize the change in state, and then provide this set of bytes to the FabricReplicator via <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> <span data-ttu-id="77d33-157">Der Dienst den Vorgang an die FabricReplicator gesendet und eine logische Sequenznummer (LSN) im Gegenzug empfängt.</span><span class="sxs-lookup"><span data-stu-id="77d33-157">The service sends the operation to the FabricReplicator and receives a logical sequence number (LSN) in return.</span></span> <span data-ttu-id="77d33-158">Die LSN ist die Identität für den Vorgang, und hilft dabei, den Dienst und die Service Fabric-stellen Sie sicher, dass Vorgänge immer in der gleichen Reihenfolge überall angewendet werden. Der Dienst sollte eine geordnete Liste von in-Flight-Vorgänge die OperationData zusammen mit der LSN aufgezeichnet.</span><span class="sxs-lookup"><span data-stu-id="77d33-158">The LSN is the identity for the operation and helps both the service and Service Fabric ensure that operations are always applied in the same order everywhere.The service should record the OperationData along with its LSN in an ordered list of in-flight operations.</span></span> <span data-ttu-id="77d33-159">Dadurch wird sichergestellt, dass wenn die Vorgänge abgeschlossen sind, sie konsistent in der richtigen Reihenfolge angewendet werden können.</span><span class="sxs-lookup"><span data-stu-id="77d33-159">This ensures that when the operations are completed, they can be consistently applied in the correct order.</span></span></para>
          <para><span data-ttu-id="77d33-160">Sperren aufheben – weiterhin verarbeiten, oder warten weitere Anforderungen.</span><span class="sxs-lookup"><span data-stu-id="77d33-160">Release Locks - Continue processing or waiting for further requests.</span></span></para>
          <para><span data-ttu-id="77d33-161">Teil 2: Ausführen von Anforderungen und Antworten: das primäre Replikat empfängt, einen Rückruf, der angibt, dass der Vorgang angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-161">Part 2: Completing requests and responding: The Primary replica receives a callback that indicates that the operation has been applied.</span></span> <span data-ttu-id="77d33-162">ReplicateAsync abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="77d33-162">ReplicateAsync is completed.</span></span> <span data-ttu-id="77d33-163">Dieser Rückruf gibt an, dass der Vorgang durch ein Quorum der Replikate in der Replikatgruppe bestätigt wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-163">This callback indicates that the operation has been acknowledged by a quorum of the replicas in the replica set.</span></span> <span data-ttu-id="77d33-164">Wenn das primäre Replikat dieser Rückruf empfängt, sollten sie die folgenden Aktionen ausführen:</span><span class="sxs-lookup"><span data-stu-id="77d33-164">When the Primary replica receives this callback, it should perform the following actions:</span></span> </para>
          <para><span data-ttu-id="77d33-165">Suchen Sie den entsprechenden Vorgang, der durch die lange LSN angegeben ist, die von ReplicateAsync in in-Flight Dienstliste zurückgegeben wird, und markieren Sie es als "QuorumAck würde".</span><span class="sxs-lookup"><span data-stu-id="77d33-165">Find the corresponding operation that is indicated by the long LSN that is returned from ReplicateAsync in the service’s in-flight list and mark it as "QuorumAck’d".</span></span> </para>
          <para><span data-ttu-id="77d33-166">Beginnend mit der erste Vorgang in der in-Flight-Liste, wechseln Sie nun über der Liste als auch lokal Commit aller der QuorumAck Vorgänge, die alle Fertig stellen verdächtigem ändert sich in den lokalen Zustand und die Markierung, die mit ihren entsprechenden LSN der Status ändert, bis der erste Vorgang unvollständige ist gefunden.</span><span class="sxs-lookup"><span data-stu-id="77d33-166">Now, starting at the first operation in the in-flight list, go through the list and locally commit all of the QuorumAck’d operations, finish any changes to the local state and mark the state changes with their corresponding LSN, until the first incomplete operation is encountered.</span></span> <span data-ttu-id="77d33-167">Dadurch wird sichergestellt, dass die Reihenfolge beibehalten (Konsistenz) ist und tatsächlich die Vorgänge angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="77d33-167">This ensures that ordering is preserved (consistency) and that the operations are actually applied.</span></span> <span data-ttu-id="77d33-168">Dies nutzt die vorherigen Dauerhaftigkeit und Isolation Vorbereitungen.</span><span class="sxs-lookup"><span data-stu-id="77d33-168">This takes advantage of the previous durability and isolation preparations.</span></span> <span data-ttu-id="77d33-169">Hinweis: Sollten die meisten Dienste den letzten Commit-LSN-Wert also zwischenspeichern, Antworten auf die <see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" /> erfordern keine Abfragen von den tatsächlichen Speicher für die größte LSN.</span><span class="sxs-lookup"><span data-stu-id="77d33-169">Note: Most services should cache the last committed LSN value so that responses to the <see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" /> do not require querying the actual store for the greatest LSN.</span></span> </para>
          <para><span data-ttu-id="77d33-170">Wenn ein Vorgang wurde erfolgreich auf dem primären Replikat ein Commit ausgeführt wird, kann jetzt das primäre Replikat Antworten an den Client, der den Aufruf initiiert hat und entfernen den Vorgang aus der in-Flight-Liste.</span><span class="sxs-lookup"><span data-stu-id="77d33-170">When an operation is successfully committed at the Primary replica, the Primary replica can now reply to the client that initiated the call and remove the operation from the in-flight list.</span></span> <span data-ttu-id="77d33-171">Für den nächsten Quorum Bestätigung Rückruf Wartevorgang wird fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="77d33-171">Continue to wait for the next quorum-acknowledgment callback.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="77d33-172">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="77d33-172">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="77d33-173">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="77d33-173">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="77d33-174"><see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="77d33-174"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="77d33-175">Es ist eines der folgenden; zurückzuführen</span><span class="sxs-lookup"><span data-stu-id="77d33-175">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-176"><see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" />wird zurückgegeben, wenn der Replikator derzeit nicht über Schreibzugriff Quorum verfügt...</span><span class="sxs-lookup"><span data-stu-id="77d33-176"><see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" /> is returned when the replicator does not currently have write quorum..</span></span></para>
          <para>
            <span data-ttu-id="77d33-177"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</span><span class="sxs-lookup"><span data-stu-id="77d33-177"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
          <para>
            <span data-ttu-id="77d33-178"><see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />wird zurückgegeben, wenn die Replicator-Warteschlange voll ist.</span><span class="sxs-lookup"><span data-stu-id="77d33-178"><see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> is returned when the replicator queue is full.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>
            <span data-ttu-id="77d33-179"><see cref="T:System.Fabric.FabricNotPrimaryException" />wird durch eines der folgenden; verursacht</span><span class="sxs-lookup"><span data-stu-id="77d33-179"><see cref="T:System.Fabric.FabricNotPrimaryException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-180"><see cref="F:System.Fabric.FabricErrorCode.NotPrimary" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</span><span class="sxs-lookup"><span data-stu-id="77d33-180"><see cref="F:System.Fabric.FabricErrorCode.NotPrimary" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="77d33-181"><see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</span><span class="sxs-lookup"><span data-stu-id="77d33-181"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="77d33-182"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="77d33-182"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>
            <span data-ttu-id="77d33-183"><see cref="T:System.OperationCanceledException" />wird durch eines der folgenden; verursacht</span><span class="sxs-lookup"><span data-stu-id="77d33-183"><see cref="T:System.OperationCanceledException" /> is caused by one of the following;</span></span></para>
          <para><span data-ttu-id="77d33-184">E_ABORT beim Abbruch einer Replikator eines in-Flight-Replikationsvorgang.</span><span class="sxs-lookup"><span data-stu-id="77d33-184">E_ABORT when replicator cancels an inflight replication operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="iStateReplicator.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="77d33-185">Die neue <see cref="T:System.Fabric.ReplicatorSettings" /> mit den aktualisierten Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="77d33-185">The new <see cref="T:System.Fabric.ReplicatorSettings" /> with the updated credentials.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="77d33-186">Ermöglicht die Änderung der Replikator Einstellungen während der Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="77d33-186">Enables modification of replicator settings during runtime.</span></span> <span data-ttu-id="77d33-187">Die einzige Einstellung, die geändert werden kann, ist die Sicherheitsanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="77d33-187">The only setting which can be modified is the security credentials.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="77d33-188">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="77d33-188">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="77d33-189">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="77d33-189">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>