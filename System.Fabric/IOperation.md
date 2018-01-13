<Type Name="IOperation" FullName="System.Fabric.IOperation">
  <TypeSignature Language="C#" Value="public interface IOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperation" />
  <TypeSignature Language="F#" Value="type IOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt die Daten, die aus der zustandsreplikator abgerufen. </para>
    </summary>
    <remarks>
      <para>
        <see cref="T:System.Fabric.IOperation" />ist die Basisschnittstelle, die Änderungen beschreibt, die an ein sekundäres Replikat übermittelt werden. </para>
      <para>
                Sie enthalten die <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> und identifizieren Sie die Sequenznummer und andere Informationen.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Acknowledge">
      <MemberSignature Language="C#" Value="public void Acknowledge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Acknowledge() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperation.Acknowledge" />
      <MemberSignature Language="VB.NET" Value="Public Sub Acknowledge ()" />
      <MemberSignature Language="F#" Value="abstract member Acknowledge : unit -&gt; unit" Usage="iOperation.Acknowledge " />
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
          <para>Bestätigt, dass dieser Vorgang erfolgreich auf das sekundäre Replikat angewendet wurde.  </para>
        </summary>
        <remarks>
          <para>Dienste sollten diese Methode aufrufen, wenn sie gewonnen haben eine <see cref="T:System.Fabric.IOperation" /> aus dem Replicator und erfolgreich auf ihren lokalen Speicher angewendet.
            Beim Aufrufen dieser Methode für persistente Dienste obligatorisch ist da die <see cref="T:System.Fabric.FabricReplicator" /> aufgehoben wird, zusätzliche Objekte, die implementieren <see cref="T:System.Fabric.IOperation" />. Für Dienste volatile Vorgänge Replikator implizit bestätigt, wenn sie empfangen werden, es sei denn, sie andernfalls konfiguriert sind, durch Festlegen des Werts <see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /> auf "true".
            Ein Vorgang muss durch ein Quorum der Replikate bestätigt werden, bevor das primäre Replikat empfängt die <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> Vorgangsantworten abgeschlossen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupId">
      <MemberSignature Language="C#" Value="public long AtomicGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AtomicGroupId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.AtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AtomicGroupId As Long" />
      <MemberSignature Language="F#" Value="member this.AtomicGroupId : int64" Usage="System.Fabric.IOperation.AtomicGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt die atomare Gruppe an, wenn dieses Objekt, die implementiert <see cref="T:System.Fabric.IOperation" /> unteilbare Gruppe gehört. Atomische-Gruppen sind nur verfügbar, wenn ein Dienst ein Teil der Gruppe "Datenzugriffsdienst" ist.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationData Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.OperationData Data" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As OperationData" />
      <MemberSignature Language="F#" Value="member this.Data : System.Fabric.OperationData" Usage="System.Fabric.IOperation.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.OperationData" /> , die vom primären Replikat bereitgestellt werden.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.OperationData" />zurück.</para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.OperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As OperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : System.Fabric.OperationType" Usage="System.Fabric.IOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Typ dieses Vorgangs ab. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.OperationType" />zurück.</para>
        </value>
        <remarks>
          <para>Die <see cref="T:System.Fabric.OperationType" /> gibt den Typ des Vorgangs an. "Normal"-Vorgänge sind diejenigen, die im Rahmen des Streams für das Kopieren oder die Replikation von nicht-gruppierten Services gesendet werden. Andere Arten von Vorgängen Steuerelement Vorgänge dar, die für Dienstgruppen spezifisch sind.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.IOperation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Sequenznummer dieses Vorgangs ab. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int64" />zurück.</para>
        </value>
        <remarks>
          <para>
                Die Sequenznummer wird bereitgestellt, als Teil der<see cref="P:System.Fabric.IOperation.SequenceNumber" /></para>
          <para>
                Für Vorgänge, die von der Replikationsstream empfangen (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) die Sequenznummer ist identisch, die das primäre Replikat, die von erhält <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> Methode.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>