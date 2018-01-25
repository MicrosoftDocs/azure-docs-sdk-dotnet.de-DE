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
            <span data-ttu-id="8ce39-101">Stellt einen Host für die Verarbeitung von Ereignisdaten für Event Hubs dar.</span><span class="sxs-lookup"><span data-stu-id="8ce39-101">Represents a host for processing Event Hubs event data.</span></span>
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
        <param name="eventHubPath"><span data-ttu-id="8ce39-102">Der Name des den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-102">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="8ce39-103">Der Name der in einem Event Hub-consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="8ce39-103">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="8ce39-104">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</span><span class="sxs-lookup"><span data-stu-id="8ce39-104">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="8ce39-105">Verbindungszeichenfolge für Azure Storage-Konto für die Leases und Prüfpunkte verwendet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-105">Connection string to Azure Storage account used for leases and checkpointing.</span></span></param>
        <param name="leaseContainerName"><span data-ttu-id="8ce39-106">Azure Storage-Containername für die Verwendung in integrierten Lease und Prüfpunkt-Manager.</span><span class="sxs-lookup"><span data-stu-id="8ce39-106">Azure Storage container name for use by built-in lease and checkpoint manager.</span></span></param>
        <summary>
             <span data-ttu-id="8ce39-107">Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-107">Create a new host to process events from an Event Hub.</span></span>
             
             <span data-ttu-id="8ce39-108"><para>Da Event Hubs für Szenarien mit horizontaler Skalierung, hohem Datenverkehrsaufkommen häufig verwendet werden, in der Regel wird nur ein einziger Host pro Prozess, und die Prozesse werden auf unterschiedlichen Computern ausgeführt werden. Jedoch wird es unterstützt mehrere Hosts auf einem Computer oder sogar in einem Prozess ausgeführt, wenn der Durchsatz nicht relevant ist.</para></span><span class="sxs-lookup"><span data-stu-id="8ce39-108"><para>Since Event Hubs are frequently used for scale-out, high-traffic scenarios, generally there will be only one host per process, and the processes will be run on separate machines. However, it is supported to run multiple hosts on one machine, or even within one process, if throughput is not a concern.</para></span></span>
             
             <span data-ttu-id="8ce39-109">Diese Überladung des Konstruktors verwendet den standardmäßig integrierten Lease und Prüfpunkt-Manager.</span><span class="sxs-lookup"><span data-stu-id="8ce39-109">This overload of the constructor uses the default, built-in lease and checkpoint managers.</span></span> <span data-ttu-id="8ce39-110">Azure Storage-Kontos, das durch den StorageConnectionString-Parameter angegeben, wird von den integrierten-Managern Datensatz Leases und Prüfpunkte verwendet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-110">The Azure Storage account specified by the storageConnectionString parameter is used by the built-in managers to record leases and checkpoints.</span></span>
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
        <param name="hostName"><span data-ttu-id="8ce39-111">Der Name des Hosts Prozessor.</span><span class="sxs-lookup"><span data-stu-id="8ce39-111">Name of the processor host.</span></span> <span data-ttu-id="8ce39-112">MUSS EINDEUTIG SEIN.</span><span class="sxs-lookup"><span data-stu-id="8ce39-112">MUST BE UNIQUE.</span></span> <span data-ttu-id="8ce39-113">Empfohlen Sie einschließlich einer Guid zum Sicherstellen der Eindeutigkeit wird dringend.</span><span class="sxs-lookup"><span data-stu-id="8ce39-113">Strongly recommend including a Guid to ensure uniqueness.</span></span></param>
        <param name="eventHubPath"><span data-ttu-id="8ce39-114">Der Name des den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-114">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="8ce39-115">Der Name der in einem Event Hub-consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="8ce39-115">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="8ce39-116">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</span><span class="sxs-lookup"><span data-stu-id="8ce39-116">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="8ce39-117">Objekt zur Implementierung von ICheckpointManager der Prüfung der Partition verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-117">Object implementing ICheckpointManager which handles partition checkpointing.</span></span></param>
        <param name="leaseManager"><span data-ttu-id="8ce39-118">Objekt zur Implementierung von ILeaseManager der Leasedauer für Partitionen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-118">Object implementing ILeaseManager which handles leases for partitions.</span></span></param>
        <summary>
            <span data-ttu-id="8ce39-119">Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-119">Create a new host to process events from an Event Hub.</span></span>
            
            <span data-ttu-id="8ce39-120"><para>Diese Überladung des Konstruktors ermöglicht maximale Flexibilität. Dieser ermöglicht des Aufrufers, den Namen des Hosts Prozessor ebenfalls angeben. Die Überladung ermöglicht zudem dem Aufrufer Geben Sie ihre eigenen Lease und Prüfpunkt-Manager, um die integrierte basierend auf Azure-Speicher zu ersetzen.</para></span><span class="sxs-lookup"><span data-stu-id="8ce39-120"><para>This overload of the constructor allows maximum flexibility. This one allows the caller to specify the name of the processor host as well. The overload also allows the caller to provide their own lease and checkpoint managers to replace the built-in ones based on Azure Storage.</para></span></span></summary>
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
        <param name="hostName"><span data-ttu-id="8ce39-121">Ein Name für diese ereignisprozessorhost.</span><span class="sxs-lookup"><span data-stu-id="8ce39-121">A name for this event processor host.</span></span> <span data-ttu-id="8ce39-122">Siehe Hinweise Methode.</span><span class="sxs-lookup"><span data-stu-id="8ce39-122">See method notes.</span></span></param>
        <param name="eventHubPath"><span data-ttu-id="8ce39-123">Der Name des den Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-123">The name of the EventHub.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="8ce39-124">Der Name der in einem Event Hub-consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="8ce39-124">The name of the consumer group within the Event Hub.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="8ce39-125">Die Verbindungszeichenfolge für den Event Hub empfangen aus.</span><span class="sxs-lookup"><span data-stu-id="8ce39-125">Connection string for the Event Hub to receive from.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="8ce39-126">Verbindungszeichenfolge für Azure Storage-Konto für die Leases und Prüfpunkte verwendet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-126">Connection string to Azure Storage account used for leases and checkpointing.</span></span></param>
        <param name="leaseContainerName"><span data-ttu-id="8ce39-127">Azure Storage-Containername für die Verwendung in integrierten Lease und Prüfpunkt-Manager.</span><span class="sxs-lookup"><span data-stu-id="8ce39-127">Azure Storage container name for use by built-in lease and checkpoint manager.</span></span></param>
        <param name="storageBlobPrefix"><span data-ttu-id="8ce39-128">Das Präfix beim Benennen von Blobs im Speichercontainer verwendet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-128">Prefix used when naming blobs within the storage container.</span></span></param>
        <summary>
            <span data-ttu-id="8ce39-129">Erstellen Sie einen neuen Host zur Verarbeitung von Ereignissen von einem Event Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-129">Create a new host to process events from an Event Hub.</span></span>
            
            <span data-ttu-id="8ce39-130"><para>Diese Überladung des Konstruktors verwendet den standardmäßig integrierten Lease und Prüfpunkt-Manager.</para></span><span class="sxs-lookup"><span data-stu-id="8ce39-130"><para>This overload of the constructor uses the default, built-in lease and checkpoint managers.</para></span></span></summary>
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
            <span data-ttu-id="8ce39-131">Ruft der Consumer Gruppennamen ab.</span><span class="sxs-lookup"><span data-stu-id="8ce39-131">Gets the consumer group name.</span></span>
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
            <span data-ttu-id="8ce39-132">Ruft den Pfad der Ereignis-Hub.</span><span class="sxs-lookup"><span data-stu-id="8ce39-132">Gets the event hub path.</span></span>
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
            <span data-ttu-id="8ce39-133">Prozessor-Hostname zurück.</span><span class="sxs-lookup"><span data-stu-id="8ce39-133">Returns processor host name.</span></span>
            <span data-ttu-id="8ce39-134">Wenn Sie der Namen des Hosts automatisch generiert wurde, ist dies die einzige Möglichkeit zum Abrufen.</span><span class="sxs-lookup"><span data-stu-id="8ce39-134">If the processor host name was automatically generated, this is the only way to get it.</span></span>
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
        <summary><span data-ttu-id="8ce39-135">Ruft ab oder legt ihn fest der <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> Instanz verwendet werden, indem die <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="8ce39-135">Gets or sets the <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> instance used by the <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> object.</span></span></summary>
        <value><span data-ttu-id="8ce39-136">Die <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />-Instanz.</span><span class="sxs-lookup"><span data-stu-id="8ce39-136">The <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> instance.</span></span></value>
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
        <typeparam name="T"><span data-ttu-id="8ce39-137">Die Implementierung einer bestimmten Anwendung <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="8ce39-137">Implementation of your application specific <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></typeparam>
        <summary>
            <span data-ttu-id="8ce39-138">Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Implementierung mit dem Host mit <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span><span class="sxs-lookup"><span data-stu-id="8ce39-138">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> implementation with the host using <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span></span>  
            <span data-ttu-id="8ce39-139">Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.</span><span class="sxs-lookup"><span data-stu-id="8ce39-139">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="8ce39-140">Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-140">A task to indicate EventProcessorHost instance is started.</span></span></returns>
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
        <typeparam name="T"><span data-ttu-id="8ce39-141">Die Implementierung einer bestimmten Anwendung <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="8ce39-141">Implementation of your application specific <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></typeparam>
        <param name="processorOptions">
          <span data-ttu-id="8ce39-142"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />um zu steuern verschiedene Aspekte der Meldungsverteilschleife erstellt, wenn Sie den Besitz für eine bestimmte Partition der EventHub abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="8ce39-142"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" /> to control various aspects of message pump created when ownership is acquired for a particular partition of EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="8ce39-143">Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> Implementierung mit dem Host mit <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span><span class="sxs-lookup"><span data-stu-id="8ce39-143">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> implementation with the host using <see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />.</span></span>  
            <span data-ttu-id="8ce39-144">Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.</span><span class="sxs-lookup"><span data-stu-id="8ce39-144">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="8ce39-145">Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-145">A task to indicate EventProcessorHost instance is started.</span></span></returns>
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
        <param name="factory"><span data-ttu-id="8ce39-146">Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung.</span><span class="sxs-lookup"><span data-stu-id="8ce39-146">Instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation.</span></span></param>
        <summary>
            <span data-ttu-id="8ce39-147">Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung mit dem Host dient zum Erstellen einer Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> beim Besitz einer Partition dauert.</span><span class="sxs-lookup"><span data-stu-id="8ce39-147">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation with the host which is used to create an instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> when it takes ownership of a partition.</span></span>  <span data-ttu-id="8ce39-148">Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.</span><span class="sxs-lookup"><span data-stu-id="8ce39-148">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="8ce39-149">Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-149">A task to indicate EventProcessorHost instance is started.</span></span></returns>
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
        <param name="factory"><span data-ttu-id="8ce39-150">Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung.</span><span class="sxs-lookup"><span data-stu-id="8ce39-150">Instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation.</span></span></param>
        <param name="processorOptions">
          <span data-ttu-id="8ce39-151"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />um zu steuern verschiedene Aspekte der Meldungsverteilschleife erstellt, wenn Sie den Besitz für eine bestimmte Partition der EventHub abgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="8ce39-151"><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" /> to control various aspects of message pump created when ownership is acquired for a particular partition of EventHub.</span></span></param>
        <summary>
            <span data-ttu-id="8ce39-152">Hierdurch wird registriert, <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> Implementierung mit dem Host dient zum Erstellen einer Instanz des <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> beim Besitz einer Partition dauert.</span><span class="sxs-lookup"><span data-stu-id="8ce39-152">This registers <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" /> implementation with the host which is used to create an instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> when it takes ownership of a partition.</span></span>  <span data-ttu-id="8ce39-153">Dies startet den Host außerdem bewirkt, dass es auf Einbeziehung in die Partition Verteilungsprozess starten.</span><span class="sxs-lookup"><span data-stu-id="8ce39-153">This also starts the host and causes it to start participating in the partition distribution process.</span></span>
            </summary>
        <returns><span data-ttu-id="8ce39-154">Eine Aufgabe an, dass EventProcessorHost-Instanz wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="8ce39-154">A task to indicate EventProcessorHost instance is started.</span></span></returns>
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
            <span data-ttu-id="8ce39-155">Beenden Sie die Verarbeitung von Ereignissen.</span><span class="sxs-lookup"><span data-stu-id="8ce39-155">Stop processing events.</span></span>  <span data-ttu-id="8ce39-156">Gibt keinen zurück, bis das Herunterfahren abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="8ce39-156">Does not return until the shutdown is complete.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>