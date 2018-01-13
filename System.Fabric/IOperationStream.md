<Type Name="IOperationStream" FullName="System.Fabric.IOperationStream">
  <TypeSignature Language="C#" Value="public interface IOperationStream" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationStream" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperationStream" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationStream" />
  <TypeSignature Language="F#" Value="type IOperationStream = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt einen Datenstrom von Replikation oder Kopiervorgänge, die vom primären zum sekundären Replikat gesendet werden.  </para>
    </summary>
    <remarks>
      <para>Die Datenströme vom zurückgegebenen <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> und <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> sind Objekte, implementieren <see cref="T:System.Fabric.IOperationStream" />.</para>
    </remarks>
    <exception cref="T:System.TimeoutException">
      <para>Die Ausnahme, die ausgelöst wird, wenn die für einen Prozess oder einen Vorgang vorgesehene Zeit abgelaufen ist.</para>
    </exception>
  </Docs>
  <Members>
    <Member MemberName="GetOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt; GetOperationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IOperation&gt; GetOperationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt;" Usage="iOperationStream.GetOperationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft das nächste Objekt, das implementiert <see cref="T:System.Fabric.IOperation" /> aus der zugrunde liegenden <see cref="T:System.Fabric.IOperationStream" />.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.Fabric.IOperation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>