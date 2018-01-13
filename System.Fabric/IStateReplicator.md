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
      <para>Macht Funktionen im Zusammenhang mit Replikation, von der <see cref="T:System.Fabric.FabricReplicator" /> Klasse, mit denen <see cref="T:System.Fabric.IStateProvider" /> zum Replizieren von Zustand, um hohe Verfügbarkeit sicherzustellen. </para>
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
          <para>Ruft kopieren Stream.</para>
        </summary>
        <returns>
          <para>Gibt die Kopie zurück <see cref="T:System.Fabric.IOperationStream" />. </para>
        </returns>
        <remarks>
          <para>Die zurückgegebenen CopyStream ist ein <see cref="T:System.Fabric.IOperationStream" /> enthält <see cref="T:System.Fabric.OperationData" /> Objekten implementiert, <see cref="T:System.Fabric.IOperation" />. Die <see cref="T:System.Fabric.OperationData" /> -Objekte werden abgerufen, von der CopyState <see cref="T:System.Fabric.IOperationDataStream" /> , die das primäre Replikat zurückgibt <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />. Wenn ein Replikat erstellt und auf den aktuellen Stand ist, erhalten die CopyStream und sollte beginnen zu senden, anwenden und bestätigen das Kopieren von Objekten, die implementieren <see cref="T:System.Fabric.IOperation" />. Parallel, reagiert das Replikat auf den entsprechenden <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> und <see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" /> aufrufen. Der Datenstrom ist leer, wenn das zurückgegebene <see cref="T:System.Fabric.IOperation" /> Methode ist null.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme. Es ist eines der folgenden; zurückzuführen</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</para>
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
          <para>Ruft die replikationsdatenstrom ab.</para>
        </summary>
        <returns>
          <para>Gibt die Replikation <see cref="T:System.Fabric.IOperationStream" />.</para>
        </returns>
        <remarks>
          <para>Implementiert die ReplicationStream <see cref="T:System.Fabric.IOperationStream" />. Enthält die ReplicationStream <see cref="T:System.Fabric.OperationData" /> Objekten implementiert, <see cref="T:System.Fabric.IOperation" />. Die Objekte werden vom primären Replikat über bereitgestellt <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />. Im Allgemeinen sollte ein sekundäres Replikat senden <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />. Service Fabric Services dazu nicht notwendig, in der Regel Dienste sollten alle übertragen <see cref="T:System.Fabric.OperationData" /> Objekten aus der Kopie zuerst zu streamen, übertragen und dann Vorgänge aus dem replikationsdatenstrom. Die Übertragung von beide Kopien parallel wird unterstützt, aber erhöht die Komplexität des Anwendens der Zustand ordnungsgemäß aktualisiert und wird nur für erweiterte Dienste empfohlen. Der Datenstrom ist leer, wenn das zurückgegebene <see cref="T:System.Fabric.IOperation" /> Methode ist null.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme. Es ist eines der folgenden; zurückzuführen</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</para>
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
          <para>Die <see cref="T:System.Fabric.OperationData" /> , die die Änderung des Zustands, die das primäre Replikat replizieren möchte darstellt.</para>
        </param>
        <param name="cancellationToken">
          <para> Ein Schreibvorgang Quorum der Replikate, die verloren gegangen sein. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <param name="sequenceNumber">
          <para>Lange, die LSN des Vorgangs. Beachten Sie, dass dies der gleiche Wert zurückgegeben, von der Aufgabe. Bereitstellen als Out-Parameter ist nützlich für Dienste, die vorzubereitenden lokalen Schreibzugriffs auf übertragen, wenn die Aufgabe abgeschlossen ist.</para>
        </param>
        <summary>
          <para>Zustandsänderungen aus dem primären Replikat an die sekundären Replikate repliziert und empfängt eine Quorum-Bestätigung, dass diese Änderungen angewendet wurden.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN des Vorgangs.</para>
        </returns>
        <remarks>
          <para>Replikation auf dem primären Replikat erzeugt, die Objekte, die implementieren <see cref="T:System.Fabric.IOperation" /> , aus dem Replikationsstream über das sekundäre Replikat übernimmt <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />, gefolgt von <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />. </para>
          <para>Das primäre Replikat verfügt über viele Aufgaben, die verknüpft sind, um statusaktualisierungen zu verarbeiten. Die folgenden Schritte zeigen die allgemeine Abfolge der Ereignisse, die ein primäres Replikat behandelt werden muss, für die Replikation und eine Änderung zu bestätigen. </para>
          <para>Teil 1: Behandlung von eingehenden Anforderungen: Empfangen der Anforderung: Write(x) – Dienst empfängt eine schreibanforderung X. CheckArguments – der Dienst überprüft die Argumente der Anforderung. Diese Überprüfung sichergestellt, dass die Konsistenz der Zustand des Diensts.</para>
          <para>Aktuellen Status Überprüfen – der Dienst überprüft seinem aktuellen Status, um sicherzustellen, dass der Vorgang gültig ist und kann oder ausgeführt werden soll. Diese Prüfung kann auch die Datenkonsistenz sicherzustellen. Es wird von der Dienstcode ausgeführt.</para>
          <para>Sperren: der Dienst sollte die erforderlichen sperren, um zu verhindern, dass zusätzliche Vorgänge zur gleichen Zeit auftreten von abrufen. Dieser Vorgang hilft dabei, Isolation und Konsistenz gewährleistet.</para>
          <para>Versuch-Vorgang (optional) – der Dienst den Vorgang lokal ausführen kann. Dieser Schritt reserviert und Speicherplatz belegt und die notwendigen Berechnungen ausführt. Dieser Schritt umfasst alle Elemente außer den eigentlichen Commit des Ergebnisses. Dieser Vorgang verbessert die Dauerhaftigkeit des Vorgangs und höher Fehler sehr unwahrscheinlich ist.</para>
          <para>Herstellung OperationData – ein <see cref="T:System.Fabric.OperationData" /> Objekt ist die Darstellung der Write(x), die der Dienst bereitgestellt wurde. Die <see cref="T:System.Fabric.OperationData" /> Objekt enthält die statusänderung auf der sekundären Replikate mit Bestätigung vom primären Replikat übertragen werden sollen. Die Daten, die der Dienst in der OperationData platziert definiert den atomaren zu aktualisieren, die die <see cref="T:System.Fabric.FabricReplicator" /> Übertragungen an die sekundären Replikate. Beachten Sie, dass das Erstellen von der <see cref="T:System.Fabric.OperationData" /> Objekt erfordert mindestens ein Byte-Arrays. Der Dienst selbst zu bestimmen und Serialisieren Sie die Änderung am Zustand, und geben Sie dieser Gruppe von Bytes auf die FabricReplicator über muss <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />. Der Dienst den Vorgang an die FabricReplicator gesendet und eine logische Sequenznummer (LSN) im Gegenzug empfängt. Die LSN ist die Identität für den Vorgang, und hilft dabei, den Dienst und die Service Fabric-stellen Sie sicher, dass Vorgänge immer in der gleichen Reihenfolge überall angewendet werden. Der Dienst sollte eine geordnete Liste von in-Flight-Vorgänge die OperationData zusammen mit der LSN aufgezeichnet. Dadurch wird sichergestellt, dass wenn die Vorgänge abgeschlossen sind, sie konsistent in der richtigen Reihenfolge angewendet werden können.</para>
          <para>Sperren aufheben – weiterhin verarbeiten, oder warten weitere Anforderungen.</para>
          <para>Teil 2: Ausführen von Anforderungen und Antworten: das primäre Replikat empfängt, einen Rückruf, der angibt, dass der Vorgang angewendet wurde. ReplicateAsync abgeschlossen ist. Dieser Rückruf gibt an, dass der Vorgang durch ein Quorum der Replikate in der Replikatgruppe bestätigt wurde. Wenn das primäre Replikat dieser Rückruf empfängt, sollten sie die folgenden Aktionen ausführen: </para>
          <para>Suchen Sie den entsprechenden Vorgang, der durch die lange LSN angegeben ist, die von ReplicateAsync in in-Flight Dienstliste zurückgegeben wird, und markieren Sie es als "QuorumAck würde". </para>
          <para>Beginnend mit der erste Vorgang in der in-Flight-Liste, wechseln Sie nun über der Liste als auch lokal Commit aller der QuorumAck Vorgänge, die alle Fertig stellen verdächtigem ändert sich in den lokalen Zustand und die Markierung, die mit ihren entsprechenden LSN der Status ändert, bis der erste Vorgang unvollständige ist gefunden. Dadurch wird sichergestellt, dass die Reihenfolge beibehalten (Konsistenz) ist und tatsächlich die Vorgänge angewendet werden. Dies nutzt die vorherigen Dauerhaftigkeit und Isolation Vorbereitungen. Hinweis: Sollten die meisten Dienste den letzten Commit-LSN-Wert also zwischenspeichern, Antworten auf die <see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" /> erfordern keine Abfragen von den tatsächlichen Speicher für die größte LSN. </para>
          <para>Wenn ein Vorgang wurde erfolgreich auf dem primären Replikat ein Commit ausgeführt wird, kann jetzt das primäre Replikat Antworten an den Client, der den Aufruf initiiert hat und entfernen den Vorgang aus der in-Flight-Liste. Für den nächsten Quorum Bestätigung Rückruf Wartevorgang wird fortgesetzt.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />ist eine wiederholbar Ausnahme. Es ist eines der folgenden; zurückzuführen</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" />wird zurückgegeben, wenn der Replikator derzeit nicht über Schreibzugriff Quorum verfügt...</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />wird zurückgegeben, wenn die Replicator-Warteschlange voll ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>
            <see cref="T:System.Fabric.FabricNotPrimaryException" />wird durch eines der folgenden; verursacht</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NotPrimary" />wird zurückgegeben, wenn der Replikator eine ausstehende Neukonfiguration hat.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />wird durch eines der folgenden; verursacht</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />wird zurückgegeben, wenn der Replikator geschlossen wurde.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>
            <see cref="T:System.OperationCanceledException" />wird durch eines der folgenden; verursacht</para>
          <para>E_ABORT beim Abbruch einer Replikator eines in-Flight-Replikationsvorgang.</para>
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
          <para>Die neue <see cref="T:System.Fabric.ReplicatorSettings" /> mit den aktualisierten Anmeldeinformationen.</para>
        </param>
        <summary>
          <para>Ermöglicht die Änderung der Replikator Einstellungen während der Laufzeit. Die einzige Einstellung, die geändert werden kann, ist die Sicherheitsanmeldeinformationen. </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>