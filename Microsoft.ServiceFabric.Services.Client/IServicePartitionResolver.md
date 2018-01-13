<Type Name="IServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver">
  <TypeSignature Language="C#" Value="public interface IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type IServicePartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            Definiert die Schnittstelle für die Partition-Konfliktlöser.
            Dienst-Auflösung versteht man die Gruppe von Endpunkten für die Replikate in einer Partition nachschlagen. Ein Partition-Konfliktlöser implementiert die Logik zur Auflösung des Diensts.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</param>
        <param name="resolveTimeoutPerTry">Versuchen Sie, das Timeout pro auflösen.</param>
        <param name="maxRetryBackoffInterval">
            Das Intervall, und wiederholen Sie dann die Auflösung nach einem Fehler aufgrund einer Ausnahme mit möglichem Wiederholungsversuch Backoff.
            </param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
          <para>
            Löst erneut eine zuvor aufgelöste Partition des angegebenen Diensts mit den angegebenen Back-off/wiederholen-Einstellungen auf Fehler mit möglichem Wiederholungsversuch auf. Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.
            </para>
        </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , Auflösungsvorgang ausstehende Dienst darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">Der Name der Dienstinstanz zu beheben.</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz. Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.
            </para>
        </param>
        <param name="resolveTimeoutPerTry">Versuchen Sie, das Timeout pro auflösen.</param>
        <param name="maxRetryBackoffInterval">
            Das Intervall, und wiederholen Sie dann die Auflösung nach einem Fehler aufgrund einer Ausnahme mit möglichem Wiederholungsversuch Backoff.
            </param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
            Löst eine Partition des angegebenen Diensts mit den angegebenen Back-off/wiederholen-Einstellungen auf Fehler mit möglichem Wiederholungsversuch auf.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , die die ausstehenden Auflösung Dienstvorgang darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>