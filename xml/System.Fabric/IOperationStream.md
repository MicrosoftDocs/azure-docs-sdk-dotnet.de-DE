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
      <para><span data-ttu-id="ac44b-101">Stellt einen Datenstrom von Replikation oder Kopiervorgänge, die vom primären zum sekundären Replikat gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="ac44b-101">Represents a stream of replication or copy operations that are sent from the Primary to the Secondary replica.</span></span>  </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="ac44b-102">Die Datenströme vom zurückgegebenen <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> und <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> sind Objekte, implementieren <see cref="T:System.Fabric.IOperationStream" />.</span><span class="sxs-lookup"><span data-stu-id="ac44b-102">The streams returned from <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> and <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> are objects that implement <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
    </remarks>
    <exception cref="T:System.TimeoutException">
      <para><span data-ttu-id="ac44b-103">Die Ausnahme, die ausgelöst wird, wenn die für einen Prozess oder einen Vorgang vorgesehene Zeit abgelaufen ist.</span><span class="sxs-lookup"><span data-stu-id="ac44b-103">The exception that is thrown when the time allotted for a process or operation has expired.</span></span></para>
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
          <para><span data-ttu-id="ac44b-104">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ac44b-104">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="ac44b-105">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ac44b-105">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="ac44b-106">Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="ac44b-106">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ac44b-107">Ruft das nächste Objekt, das implementiert <see cref="T:System.Fabric.IOperation" /> aus der zugrunde liegenden <see cref="T:System.Fabric.IOperationStream" />.</span><span class="sxs-lookup"><span data-stu-id="ac44b-107">Gets the next object that implements <see cref="T:System.Fabric.IOperation" /> from the underlying <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="ac44b-108">Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.Fabric.IOperation" />.</span><span class="sxs-lookup"><span data-stu-id="ac44b-108">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Fabric.IOperation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>