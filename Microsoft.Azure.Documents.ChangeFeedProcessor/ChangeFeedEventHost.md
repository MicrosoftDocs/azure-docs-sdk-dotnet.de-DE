<Type Name="ChangeFeedEventHost" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost">
  <TypeSignature Language="C#" Value="public class ChangeFeedEventHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedEventHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedEventHost" />
  <TypeSignature Language="F#" Value="type ChangeFeedEventHost = class&#xA;    interface IPartitionObserver&lt;DocumentServiceLease&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einfache Host zum Verteilen von Änderung feed Ereignisse über Beobachter und somit diese Beobachter Skalierung.
            Sie verteilt die Last für ihre Instanzen und dynamische Skalierung ermöglicht:
              - Partitionen in partitionierte Sammlungen werden auf Instanzen/Beobachter verteilt.
              - Neue Instanz akzeptiert Leases aus vorhandenen Instanzen Verteilung gleich vornehmen.
              - Wenn eine Instanz nicht mehr aktiv ist, werden die Leasedauer auf verbleibenden Instanzen verteilt.
            Das ist für Szenario nützlich, wenn Partitionsanzahl hoch ist, sodass ein Host virtueller Computer nicht verarbeiten kann, dass viele feed Änderungsereignisse.
            Clientanwendung implementieren muss <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" /> und-prozessorimplementierung mit ChangeFeedEventHost registrieren.
            </summary>
    <remarks>
            Zusätzlichen Dokumentationsreihe verwendet für die Verwaltung von Leases für eine Partition.
            Jede EventProcessorHost-Instanz ausführt die folgenden zwei Aufgaben:
                1) Erneuern von Leases: Er verfolgt Leases, die gerade im Besitz des Hosts und behält kontinuierlich auf die Leases erneuern.
                2) Erwerben Leases: Jede Instanz fragt kontinuierlich alle Leases, um festzustellen, ob es gibt Leases, die er für das System in ausgeglichenen Zustand zu versetzen abrufen soll.
                </remarks>
    <example>
      <code language="c#"><![CDATA[
            class DocumentFeedObserver : IChangeFeedObserver
            {
                private static int s_totalDocs = 0;
                public Task OpenAsync(ChangeFeedObserverContext context)
                {
                    Console.WriteLine("Worker opened, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;  // Requires targeting .NET 4.6+.
                }
                public Task CloseAsync(ChangeFeedObserverContext context, ChangeFeedObserverCloseReason reason)
                {
                    Console.WriteLine("Worker closed, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;
                }
                public Task ProcessChangesAsync(ChangeFeedObserverContext context, IReadOnlyList<Document> docs)
                {
                    Console.WriteLine("Change feed: total {0} doc(s)", Interlocked.Add(ref s_totalDocs, docs.Count));
                    return Task.CompletedTask;
                }
            }
            static async Task StartChangeFeedHost()
            {
                string hostName = Guid.NewGuid().ToString();
                DocumentCollectionInfo documentCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "documents"
                };
                DocumentCollectionInfo leaseCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "leases"
                };
                Console.WriteLine("Main program: Creating ChangeFeedEventHost...");
                ChangeFeedEventHost host = new ChangeFeedEventHost(hostName, documentCollectionLocation, leaseCollectionLocation);
                await host.RegisterObserverAsync<DocumentFeedObserver>();
                Console.WriteLine("Main program: press Enter to stop...");
                Console.ReadLine();
                await host.UnregisterObserversAsync();
            }
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, documentCollectionLocation As DocumentCollectionInfo, auxCollectionLocation As DocumentCollectionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
      </Parameters>
      <Docs>
        <param name="hostName">Eindeutiger Name für diesen Host.</param>
        <param name="documentCollectionLocation">Gibt die Position der DocumentDB-Auflistung, um Änderungen für die Überwachung.</param>
        <param name="auxCollectionLocation">Gibt Speicherort für den Lastenausgleich der zusätzlichen Instanzen von <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, class Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.Client.ChangeFeedOptions,Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.Client.ChangeFeedOptions * Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation, changeFeedOptions, hostOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="changeFeedOptions" Type="Microsoft.Azure.Documents.Client.ChangeFeedOptions" />
        <Parameter Name="hostOptions" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
      </Parameters>
      <Docs>
        <param name="hostName">Eindeutiger Name für diesen Host.</param>
        <param name="documentCollectionLocation">Gibt die Position der DocumentDB-Auflistung, um Änderungen für die Überwachung.</param>
        <param name="auxCollectionLocation">Gibt Speicherort für den Lastenausgleich der zusätzlichen Instanzen von <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />.</param>
        <param name="changeFeedOptions">Optionen für die Übergabe an die Microsoft.AzureDocuments.DocumentClient.CreateChangeFeedQuery-API.</param>
        <param name="hostOptions">Zusätzliche Optionen zum Steuern der Lastenausgleich <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanzen.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEstimatedRemainingWork">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetEstimatedRemainingWork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetEstimatedRemainingWork() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.GetEstimatedRemainingWork" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEstimatedRemainingWork () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.GetEstimatedRemainingWork : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="changeFeedEventHost.GetEstimatedRemainingWork " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;GetEstimatedRemainingWork&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Asynchron überprüft die aktuelle vorhandene Leasedauer und berechnet eine Schätzung der verbleibenden Arbeit pro geleasten Partitionen.
            </summary>
        <returns>Eine Menge Schätzung der verbleibenden Dokumente verarbeitet werden</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Hostnamen, also einen eindeutigen Namen für die Instanz ab.</summary>
        <value>Der Hostname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverAsync&lt;T&gt; () where T : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObservernew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverAsync&lt;.ctor (class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverAsync(Of T As {IChangeFeedObserverNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver and 'T : (new : unit -&gt; 'T))" Usage="changeFeedEventHost.RegisterObserverAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverAsync&gt;d__23`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">Implementierung der anwendungsspezifischen Ereignis "Beobachter".</typeparam>
        <summary>Asynchron registriert die schnittstellenimplementierung "Beobachter" mit dem Host.
            Diese Methode startet den Host auch und ihn auf Einbeziehung in die Partition Verteilungsprozess start ermöglicht.</summary>
        <returns>Eine Aufgabe zeigt an, dass die <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> wurde gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverFactoryAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverFactoryAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverFactoryAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverFactoryAsync (factory As IChangeFeedObserverFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverFactoryAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.RegisterObserverFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverFactoryAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory" />
      </Parameters>
      <Docs>
        <param name="factory">Die Implementierung Ihrer anwendungsspezifischen Ereignis "Beobachter" Factory.</param>
        <summary>
            Asynchron registriert "Beobachter" Factory-Implementierung mit dem Host.
            Diese Methode startet den Host auch und ihn auf Einbeziehung in die Partition Verteilungsprozess start ermöglicht.
            </summary>
        <returns>Eine Aufgabe zeigt an, dass die <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> wurde gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterObserversAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterObserversAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterObserversAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.UnregisterObserversAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterObserversAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterObserversAsync : unit -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.UnregisterObserversAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;UnregisterObserversAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Fährt asynchron die Hostinstanz aus. Diese Methode verwaltet die Leasedauer für alle Partitionen, die derzeit aufrecht erhalten werden und jede Hostinstanz zum ordnungsgemäßen Herunterfahren durch Aufrufen der Methode mit Objekt ermöglicht.</summary>
        <returns>Eine Aufgabe, die die Hostinstanz wurde beendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>