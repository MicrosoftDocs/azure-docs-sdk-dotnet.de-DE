<Type Name="IStatelessServiceInstance" FullName="System.Fabric.IStatelessServiceInstance">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceInstance" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceInstance" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceInstance" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceInstance" />
  <TypeSignature Language="F#" Value="type IStatelessServiceInstance = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Definiert das Verhalten, die den Lebenszyklus einer statusfreien Dienstinstanz, z. B. starten, Initialisierung und Herunterfahren bestimmt. </para>
      <remarks>
            Zustandslose Diensttypen müssen diese Schnittstelle implementieren. Die <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">zuverlässige zustandslosen Diensts</see> implementiert diese Schnittstelle und Instanz Lifecycle intern behandelt.
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatelessServiceInstance.Abort " />
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
          <para> Wird dieser Instanz durch Aufruf der synchronen Methode nicht ordnungsgemäß beendet. </para>
        </summary>
        <remarks>
          <para>Beispiele für geordnete und ungeordnete Abbrüche Beendigung sind Netzwerkprobleme, wodurch Service Fabric-Prozess heruntergefahren und die Verwendung von <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> Bericht eine <see cref="F:System.Fabric.FaultType.Permanent" /> Fehler. Wenn die Dienstinstanz diese Methode empfängt, sollten sie sofort freigeben und bereinigen Sie alle Verweise und zurückgeben.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatelessServiceInstance.CloseAsync cancellationToken" />
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
          <para>Schließt dieser Dienstinstanz ordnungsgemäß, wenn die Dienstinstanz heruntergefahren wird.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatelessServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatelessServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Initialize(System.Fabric.StatelessServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatelessServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatelessServiceInitializationParameters -&gt; unit" Usage="iStatelessServiceInstance.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatelessServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><see cref="T:System.Fabric.StatelessServiceInitializationParameters" /> für diesen Dienst.</para>
        </param>
        <summary>
          <para> Initialisiert eine neue Dienstinstanz.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Fabric.IStatelessServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(class System.Fabric.IStatelessServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.IStatelessServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatelessServiceInstance.OpenAsync (partition, cancellationToken)" />
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
        <Parameter Name="partition" Type="System.Fabric.IStatelessServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partition">
          <para>
                Die <see cref="T:System.Fabric.IStatelessServicePartition" /> , die dieser Instanz zugeordnet ist</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Wird eine initialisierten-Dienstinstanz geöffnet, sodass es von Clients kontaktiert werden kann.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> vom Typ <see cref="T:System.String" />.</para>
        </returns>
        <remarks>
          <para>Öffnen eine Instanz zustandslosen Diensts gibt an, dass der Dienst jetzt aufgelöst werden kann und durch den Dienst für Clients sichtbar ist. Die Zeichenfolge, die zurückgegeben wird, ist die Adresse dieser Dienstinstanz. Die Adresse der Dienstname über naming Service Fabric zugeordnet und für Clients, die den Dienst über beheben zurückgegeben <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>