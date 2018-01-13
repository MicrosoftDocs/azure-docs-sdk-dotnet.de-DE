<Type Name="EventProcessorHost" FullName="Microsoft.Azure.EventHubs.Processor.EventProcessorHost">
  <TypeSignature Language="C#" Value="public sealed class EventProcessorHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventProcessorHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventProcessorHost" />
  <TypeSignature Language="F#" Value="type EventProcessorHost = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Host für die Verarbeitung von Ereignisdaten für Event Hubs dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Name des den Event Hub.</param>
        <param name="consumerGroupName">Der Name der in einem Event Hub-consumergruppe.</param>
        <param name="eventHubConnectionString">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</param>
        <param name="storageConnectionString">Verbindungszeichenfolge für Azure Storage-Konto für die Leases und Prüfpunkte verwendet.</param>
        <param name="leaseContainerName">Azure Storage-Containername für die Verwendung in integrierten Lease und Prüfpunkt-Manager.</param>
        <summary>
             Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.
             
             <para>Da Event Hubs für Szenarien mit horizontaler Skalierung, hohem Datenverkehrsaufkommen häufig verwendet werden, in der Regel wird nur ein einziger Host pro Prozess, und die Prozesse werden auf unterschiedlichen Computern ausgeführt werden. Jedoch wird es unterstützt mehrere Hosts auf einem Computer oder sogar in einem Prozess ausgeführt, wenn der Durchsatz nicht relevant ist.</para>
             
             Diese Überladung des Konstruktors verwendet den standardmäßig integrierten Lease und Prüfpunkt-Manager. Azure Storage-Kontos, das durch den StorageConnectionString-Parameter angegeben, wird von den integrierten-Managern Datensatz Leases und Prüfpunkte verwendet.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, class Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, class Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.EventHubs.Processor.ICheckpointManager,Microsoft.Azure.EventHubs.Processor.ILeaseManager)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, checkpointManager As ICheckpointManager, leaseManager As ILeaseManager)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * Microsoft.Azure.EventHubs.Processor.ICheckpointManager * Microsoft.Azure.EventHubs.Processor.ILeaseManager -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, checkpointManager, leaseManager)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="checkpointManager" Type="Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
        <Parameter Name="leaseManager" Type="Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
      </Parameters>
      <Docs>
        <param name="hostName">Der Name des Hosts Prozessor. MUSS EINDEUTIG SEIN. Empfohlen Sie einschließlich einer Guid zum Sicherstellen der Eindeutigkeit wird dringend.</param>
        <param name="eventHubPath">Der Name des den Event Hub.</param>
        <param name="consumerGroupName">Der Name der in einem Event Hub-consumergruppe.</param>
        <param name="eventHubConnectionString">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</param>
        <param name="checkpointManager">Objekt zur Implementierung von ICheckpointManager der Prüfung der Partition verarbeitet.</param>
        <param name="leaseManager">Objekt zur Implementierung von ILeaseManager der Leasedauer für Partitionen verarbeitet.</param>
        <summary>
            Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.
            
            <para>Diese Überladung des Konstruktors ermöglicht maximale Flexibilität. Dieser ermöglicht des Aufrufers, den Namen des Hosts Prozessor ebenfalls angeben. Die Überladung ermöglicht zudem dem Aufrufer Geben Sie ihre eigenen Lease und Prüfpunkt-Manager, um die integrierte basierend auf Azure-Speicher zu ersetzen.</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String, Optional storageBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName, storageBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="storageBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">Ein Name für diese ereignisprozessorhost. Siehe Hinweise Methode.</param>
        <param name="eventHubPath">Der Name des den Event Hub.</param>
        <param name="consumerGroupName">Der Name der in einem Event Hub-consumergruppe.</param>
        <param name="eventHubConnectionString">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</param>
        <param name="storageConnectionString">Verbindungszeichenfolge für Azure Storage-Konto für die Leases und Prüfpunkte verwendet.</param>
        <param name="leaseContainerName">Azure Storage-Containername für die Verwendung in integrierten Lease und Prüfpunkt-Manager.</param>
        <param name="storageBlobPrefix">Das Präfix beim Benennen von Blobs im Speichercontainer verwendet.</param>
        <summary>
            Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.
            
            <para>Diese Überladung des Konstruktors verwendet den standardmäßig integrierten Lease und Prüfpunkt-Manager.</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Consumer Gruppennamen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Pfad der Ereignis-Hub.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Prozessor-Hostname zurück.
            Wenn Sie der Namen des Hosts automatisch generiert wurde, ist dies die einzige Möglichkeit zum Abrufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionManagerOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionManagerOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.PartitionManagerOptions : Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt ihn fest der <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> Instanz verwendet werden, indem die <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Objekt.</summary>
        <value>Die <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />-Instanz.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; () where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">Die Implementierung einer bestimmten Anwendung <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</typeparam>
        <summary>
            Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Implementierung mit dem Host mit <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.  
            Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.
            </summary>
        <returns>Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; (Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;(class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1(Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) (processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync processorOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">Die Implementierung einer bestimmten Anwendung <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</typeparam>
        <param name="processorOptions">
          <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />um zu steuern verschiedene Aspekte der Meldungsverteilschleife erstellt, wenn Sie den Besitz für eine bestimmte Partition der EventHub abgerufen wird.</param>
        <summary>
            Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Implementierung mit dem Host mit <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.  
            Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.
            </summary>
        <returns>Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="factory">Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung.</param>
        <summary>
            Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung mit dem Host dient zum Erstellen einer Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> beim Besitz einer Partition dauert.  Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.
            </summary>
        <returns>Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory,Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory, processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory * Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync (factory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;RegisterEventProcessorFactoryAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung.</param>
        <param name="processorOptions">
          <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />um zu steuern verschiedene Aspekte der Meldungsverteilschleife erstellt, wenn Sie den Besitz für eine bestimmte Partition der EventHub abgerufen wird.</param>
        <summary>
            Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung mit dem Host dient zum Erstellen einer Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> beim Besitz einer Partition dauert.  Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.
            </summary>
        <returns>Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterEventProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterEventProcessorAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterEventProcessorAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.UnregisterEventProcessorAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterEventProcessorAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.UnregisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;UnregisterEventProcessorAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beenden Sie die Verarbeitung von Ereignissen.  Gibt keinen zurück, bis das Herunterfahren abgeschlossen ist.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>