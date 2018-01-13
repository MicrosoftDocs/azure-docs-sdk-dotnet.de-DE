<Type Name="IAtomicGroupStateProvider" FullName="System.Fabric.IAtomicGroupStateProvider">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateProvider : System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateProvider implements class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateProvider&#xA;Implements IStateProvider" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateProvider = interface&#xA;    interface IStateProvider" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Beschreibt zusätzliche Methoden, mit der die <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> -Schnittstelle, die ein Dienst des Benutzers implementieren muss, um die Funktionalität der atomare Gruppe einer Dienstgruppe nutzen. </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupCommitAsync (long atomicGroupId, long commitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupCommitAsync(int64 atomicGroupId, int64 commitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupCommitAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupCommitAsync (atomicGroupId, commitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>Die ID der Gruppe, die ein Commit ausgeführt werden.</para>
        </param>
        <param name="commitSequenceNumber">
          <para>Die Sequenznummer für den Commitvorgang.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Führt einen Commit für eine bestimmte unteilbare Gruppe.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupRollbackAsync (long atomicGroupId, long rollbackSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupRollbackAsync(int64 atomicGroupId, int64 rollbackSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupRollbackAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupRollbackAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupRollbackAsync (atomicGroupId, rollbackSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>Die ID der Gruppe, die für einen Rollback auszuführen.</para>
        </param>
        <param name="rollbackSequenceNumber">
          <para>Die Sequenznummer für den Rollbackvorgang.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Führt einen Rollback für eine bestimmte unteilbare Gruppe aus.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupUndoProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupUndoProgressAsync (long fromCommitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupUndoProgressAsync(int64 fromCommitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupUndoProgressAsync(System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupUndoProgressAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupUndoProgressAsync (fromCommitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromCommitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fromCommitSequenceNumber">
          <para>Die LSN eines Commit-Vorgangs. Alle Status über diesen Punkt hinaus sollte rückgängig gemacht werden.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Gibt dieser Status über einen bestimmten commitfolgenummer, die über bereitgestellt wird <see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" /> sollte nicht rückgängig gemacht werden. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>