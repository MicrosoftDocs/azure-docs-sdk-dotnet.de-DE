<Type Name="IAtomicGroupStateReplicator" FullName="System.Fabric.IAtomicGroupStateReplicator">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Macht Funktionen für atomic-Gruppen im Zusammenhang mit Replikation. </para>
    </summary>
    <remarks>
      <para>Die <see cref="T:System.Fabric.IAtomicGroupStateReplicator" /> ist verfügbar, wenn der Dienst einer Dienstgruppe angehört. Implementieren des Diensts muss <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> und statusbehaftete sein. Beim Erstellen einer <see cref="T:System.Fabric.FabricReplicator" /> über <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />, anstelle der Übergabe einer reguläres <see cref="T:System.Fabric.IStateProvider" />, kann der Dienst übergeben der <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> , die ihn implementiert stattdessen. Daher erhält er eine <see cref="T:System.Fabric.IAtomicGroupStateReplicator" />.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAtomicGroup">
      <MemberSignature Language="C#" Value="public long CreateAtomicGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 CreateAtomicGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAtomicGroup () As Long" />
      <MemberSignature Language="F#" Value="abstract member CreateAtomicGroup : unit -&gt; int64" Usage="iAtomicGroupStateReplicator.CreateAtomicGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt eine neue atomare Gruppe und ruft die ID der Gruppe "atomic" ab.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Int64" /> die ID von der atomare Gruppe.</para>
        </returns>
        <remarks>
          <para>Atomische Gruppen werden verwendet, um einen Satz von Änderungen auf die Mitglieder einer Dienstgruppe zu koordinieren.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupCommitAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupCommitAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupCommitAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync (atomicGroupId, cancellationToken, commitSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>Die ID der Gruppe, die ein Commit ausgeführt werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <param name="commitSequenceNumber">
          <para>Die LSN des Commitvorgangs als Out-Parameter.</para>
        </param>
        <summary>
          <para>Führt einen Commit asynchron Status der Replikation für atomare Gruppe an.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN des Commitvorgangs.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupOperationAsync (long atomicGroupId, System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupOperationAsync(int64 atomicGroupId, class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync(System.Int64,System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupOperationAsync : int64 * System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync (atomicGroupId, operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>Die ID von der atomare Gruppe, die aus abgerufen <see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" /> und enthält die <see cref="T:System.Fabric.OperationData" />.</para>
        </param>
        <param name="operationData">
          <para>Ein <see cref="T:System.Fabric.OperationData" /> repliziert werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Das CancellationToken-Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <param name="sequenceNumber">
          <para>Die LSN des Vorgangs, als Out-Parameter.</para>
        </param>
        <summary>
          <para>Einige repliziert <see cref="T:System.Fabric.OperationData" /> als Teil einer atomare Gruppe.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN der die replizierten atomaren Vorgang "Gruppe".</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupRollbackAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long rollbackSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupRollbackAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; rollbackSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupRollbackAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync (atomicGroupId, cancellationToken, rollbackSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>Die ID von der atomare Gruppe Rollback.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <param name="rollbackSequenceNumber">
          <para>Die LSN der Rollback-Vorgangs, als Out-Parameter.</para>
        </param>
        <summary>
          <para>Asynchron ein Rollback des Status der Replikation für atomare Gruppe.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ long, die LSN der Rollback-Vorgangs.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>