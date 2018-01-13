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
      <para>Definiert das Verhalten, die den Lebenszyklus eines Replikats, z. B. starten, Initialisierung, rollenänderungen und Herunterfahren bestimmt. </para>
    </summary>
    <remarks>
      <para>
                Zustandsbehaftete Diensttypen müssen diese Schnittstelle implementieren. Die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">zuverlässige Stateful Service</see> implementiert diese Schnittstelle und Replikat-Lebenszyklus intern behandelt. </para>
      <para>
                Die Logik der einen zustandsbehafteten Diensttyp enthält, die auf primären Replikaten aufgerufen wird und Verhalten, die auf sekundären Replikaten aufgerufen wird.</para>
      <para>
                Wenn dienstautor vornehmen möchte mithilfe des bereitgestellten <see cref="T:System.Fabric.FabricReplicator" />, und klicken Sie dann der Dienst, auch implementieren muss <see cref="T:System.Fabric.IStateProvider" /> verwenden Sie die Implementierung der <see cref="T:System.Fabric.IStateReplicator" /> , die vom bereitgestellt <see cref="T:System.Fabric.FabricReplicator" />.</para>
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
          <para>Nicht ordnungsgemäß beendet die dienstreplikats.</para>
        </summary>
        <remarks>
          <para>Netzwerk-Probleme, wodurch Service Fabric-Prozess heruntergefahren und die Verwendung von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Bericht eine <see cref="F:System.Fabric.FaultType.Permanent" /> Fehler finden Sie Beispiele für geordnete und ungeordnete Abbrüche beenden. Wenn diese Methode aufgerufen wird, sollten die dienstreplikats sofort freigeben und bereinigen Sie alle Verweise und zurückgeben.</para>
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
          <para>Die aktualisierte <see cref="T:System.Fabric.ReplicaRole" /> , die dieses Replikat zum übergehen soll.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ändert die Rolle des Replikats Service in eines der <see cref="T:System.Fabric.ReplicaRole" />. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.String" />, der Dienst neue Adresse für die Verbindung, die über die Benennung von Service Fabric-Replikat zugeordnet werden soll.</para>
        </returns>
        <remarks>
          <para>Die neue Rolle wird als Parameter angegeben. Wenn die Dienst-Übergänge in die neue Rolle, verfügt der Dienst eine Möglichkeit, ihre aktuellen abhöradresse zu aktualisieren.
            Die abhöradresse ist die Adresse, in dem Clients eine Verbindung herstellen, und die über zurückgegeben, der <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API. Dies ermöglicht dem Dienst wird ein primäres Replikat, Anspruch nur einige Ressourcen wie z. B. Ports aus, bei der Kommunikation von Clients erwartet wird.</para>
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
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Schließt die dienstreplikats ordnungsgemäß, wenn er heruntergefahren wird.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
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
          <para>Die <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> für dieses Replikat.</para>
        </param>
        <summary>
          <para>Initialisiert eine neu erstellte dienstreplikats an.</para>
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
          <para>Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</para>
        </param>
        <param name="partition">
          <para>Die <see cref="T:System.Fabric.IStatefulServicePartition" /> Informationen für dieses Replikat.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Wird ein initialisierter dienstreplikats geöffnet, sodass zusätzliche Aktionen ausgeführt werden können.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> &lt; <see cref="T:System.Fabric.IReplicator" /> &gt;, <see cref="T:System.Fabric.IReplicator" /> , das von der zustandsbehaftete Dienst verwendet wird. Verwenden Sie die Service Fabric-Implementierung in <see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />, sollte das Replikat Zurückgeben einer <see cref="T:System.Fabric.FabricReplicator" /> abgerufener <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>