<Type Name="IReliableCollection&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableCollection&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableCollection`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableCollection(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableCollection&lt;'T&gt; = interface&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">Der Typ der Elemente in der Auflistung.</typeparam>
    <summary>
      <para>Definiert Methoden zum Bearbeiten von zuverlässigen Sammlungen.</para>
    </summary>
    <remarks>
      <para>Weitere Informationen über zuverlässige Sammlungen kann angezeigt werden <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">hier</see>.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.ClearAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ClearAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iReliableCollection.ClearAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Entfernt alle Statusangaben aus der <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />, einschließlich repliziert und Zustand beibehalten.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>Wird ausgelöst, wenn der Versuch zum Ausführen dieses Vorgangs auf einem <cref name="IReliableCollection{T}" /> , die sich nicht in der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Gibt an, dass dieser Vorgang innerhalb des angegebenen Timeouts abgeschlossen werden konnte.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCountAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetCountAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetCountAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.GetCountAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCountAsync (tx As ITransaction) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetCountAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iReliableCollection.GetCountAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx">
            Die Transaktion, die diesen Vorgang zu verknüpfen. Beispiele für Transaktionen <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">hier</see>.
            </param>
        <summary>
          <para>Ruft die Anzahl der Elemente ab, die in <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> enthalten sind.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang, der angibt, der Anzahl der Elemente darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
          <para>Gibt an, dass die IReliableCollection Lesevorgänge im Moment nicht bedienen.
            Diese Ausnahme kann ausgelöst werden, in allen <see cref="T:System.Fabric.ReplicaRole" />s.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle ist der Verlust der <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.
            Ein Grund, die sie möglicherweise, in ausgelöst der <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle ist, dass zuverlässige sammlungsstatus noch nicht konsistent ist.</para>
        </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">Die Transaktion wurde vom System intern fehlgeschlagen. Wiederholen Sie den Vorgang einer neuen Transaktion</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn ein Methodenaufruf für aktuellen Zustands des Objekts ungültig ist.
            Beispielsweise verwendeten Transaktion bereits beendet wird: ein Commit oder ein vom Benutzer abgebrochen.
            Wenn diese Ausnahme ausgelöst wird, ist es sehr wahrscheinlich, dass ein Fehler in der Code für die Verwendung von Transaktionen vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>Wird ausgelöst, wenn der Versuch zum Ausführen dieses Vorgangs auf einem <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> , die sich nicht in der <see cref="F:System.Fabric.ReplicaRole.Primary" /> Rolle.
            In einigen Fällen Lesevorgänge, z. B. ein kann von sekundären Replikaten abhängig von der Implementierung von der verwendeten IReliableCollection ausgeführt werden.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>