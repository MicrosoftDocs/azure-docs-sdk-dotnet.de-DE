<Type Name="CommunicationClientFactoryBase&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public abstract class CommunicationClientFactoryBase&lt;TCommunicationClient&gt; : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CommunicationClientFactoryBase`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CommunicationClientFactoryBase(Of TCommunicationClient)&#xA;Implements ICommunicationClientFactory(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = class&#xA;    interface ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="1e32b-101">Kommunikation-Clienttyp</span><span class="sxs-lookup"><span data-stu-id="1e32b-101">The type of communication client</span></span></typeparam>
    <summary>
            <span data-ttu-id="1e32b-102">Stellt die grundlegende Implementierung der ICommunicationClientFactory zum Erstellen von Kommunikation von Clients zum Kommunizieren mit Service Fabric-Dienste verwendet.</span><span class="sxs-lookup"><span data-stu-id="1e32b-102">Provides the base implementation of ICommunicationClientFactory for creating communication clients to talk to service fabric services.</span></span> <span data-ttu-id="1e32b-103">Erweitern Sie die CommunicationClientFactoryBase-Klasse, um die Kommunikation von Clients benutzerdefinierte transportimplementierungen erstellen.</span><span class="sxs-lookup"><span data-stu-id="1e32b-103">Extend the CommunicationClientFactoryBase class to create communication clients for custom transport implementations.</span></span> <span data-ttu-id="1e32b-104">Diese Klasse verwaltet einen Cache der Kommunikation zwischen Clients und versucht, die Clients für Anforderungen an den gleichen Dienstendpunkt wiederverwenden.</span><span class="sxs-lookup"><span data-stu-id="1e32b-104">This class maintains a cache of communication clients and attempts to reuse the clients for requests to the same service endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CommunicationClientFactoryBase (Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver = null, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers = null, string traceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver servicePartitionResolver, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; exceptionHandlers, string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.#ctor(Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver,System.Collections.Generic.IEnumerable{Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler},System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (Optional servicePartitionResolver As IServicePartitionResolver = null, Optional exceptionHandlers As IEnumerable(Of IExceptionHandler) = null, Optional traceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver * seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; * string -&gt; Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt; (servicePartitionResolver, exceptionHandlers, traceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="servicePartitionResolver" Type="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
        <Parameter Name="exceptionHandlers" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" />
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePartitionResolver"><span data-ttu-id="1e32b-105">Optionale ServicePartitionResolver</span><span class="sxs-lookup"><span data-stu-id="1e32b-105">Optional ServicePartitionResolver</span></span></param>
        <param name="exceptionHandlers"><span data-ttu-id="1e32b-106">Optionale benutzerdefinierte Ausnahmehandler für die Ausnahmen, die auf dem Client zum Dienst Kommunikationskanal</span><span class="sxs-lookup"><span data-stu-id="1e32b-106">Optional Custom exception handlers for the exceptions on the Client to Service communication channel</span></span></param>
        <param name="traceId"><span data-ttu-id="1e32b-107">Bezeichner für die Verwendung in Diagnose ablaufverfolgungen dieser Komponente</span><span class="sxs-lookup"><span data-stu-id="1e32b-107">Identifier to use in diagnostics traces from this component</span></span> </param>
        <summary>
            <span data-ttu-id="1e32b-108">Initialisiert eine neue Instanz der Factory Client Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="1e32b-108">Initializes a new instance of the communication client factory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortClient">
      <MemberSignature Language="C#" Value="protected abstract void AbortClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AbortClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.AbortClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AbortClient (client As TCommunicationClient)" />
      <MemberSignature Language="F#" Value="abstract member AbortClient : 'CommunicationClient -&gt; unit" Usage="communicationClientFactoryBase.AbortClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="1e32b-109">Kommunikationsclient</span><span class="sxs-lookup"><span data-stu-id="1e32b-109">Communication client</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-110">Bricht die angegebene client</span><span class="sxs-lookup"><span data-stu-id="1e32b-110">Aborts the given client</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientConnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientConnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientConnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e32b-111">Ereignishandler, die ausgelöst wird, wenn die Kommunikation-Client eine Verbindung zum Dienstendpunkt herstellt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-111">Event handler that is fired when the Communication client connects to the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt; ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs`1&lt;!TCommunicationClient&gt;&gt; ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler(Of CommunicationClientEventArgs(Of TCommunicationClient)) " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " Usage="member this.ClientDisconnected : System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;'CommunicationClient&gt;&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ClientDisconnected</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientEventArgs&lt;TCommunicationClient&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e32b-112">Ereignishandler, die ausgelöst wird, wenn der Dienstendpunkt die Kommunikation vom Client getrennt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-112">Event handler that is fired when the Communication client disconnects from the service endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;TCommunicationClient&gt; CreateClientAsync (string endpoint, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; CreateClientAsync(string endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.CreateClientAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateClientAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.CreateClientAsync (endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="1e32b-113">Adresse des Listeners, in dem das Replikat lauscht</span><span class="sxs-lookup"><span data-stu-id="1e32b-113">listener address where the replica is listening</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e32b-114">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="1e32b-114">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-115">Erstellt einen Client Kommunikation für die angegebene Endpunktadresse.</span><span class="sxs-lookup"><span data-stu-id="1e32b-115">Creates a communication client for the given endpoint address.</span></span>
            </summary>
        <returns><span data-ttu-id="1e32b-116">Die Kommunikation zwischen Client, der erstellt wurde</span><span class="sxs-lookup"><span data-stu-id="1e32b-116">The communication client that was created</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionHandlers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt; ExceptionHandlers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ExceptionHandlers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionHandlers As IEnumerable(Of IExceptionHandler)" />
      <MemberSignature Language="F#" Value="member this.ExceptionHandlers : seq&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ExceptionHandlers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e32b-117">Ruft die benutzerdefinierten Ausnahmehandler zum Behandeln von Ausnahmen auf dem Client zum Dienst-Kommunikationskanal.</span><span class="sxs-lookup"><span data-stu-id="1e32b-117">Gets the custom exception handlers for handling exceptions on the client to service communication channel.</span></span>
            </summary>
        <value><span data-ttu-id="1e32b-118">Liste der Ausnahmehandler</span><span class="sxs-lookup"><span data-stu-id="1e32b-118">List of Exception handlers</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (System.Fabric.ResolvedServicePartition previousRsp, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplica, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : System.Fabric.ResolvedServicePartition * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (previousRsp, targetReplica, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Fabric.ResolvedServicePartition,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="targetReplica" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="1e32b-119">Vorherige ResolvedServicePartition-Wert</span><span class="sxs-lookup"><span data-stu-id="1e32b-119">Previous ResolvedServicePartition value</span></span></param>
        <param name="targetReplica"><span data-ttu-id="1e32b-120">Gibt an, welches Replikat in der Partition, die durch den Partitionsschlüssel identifiziert, die Clients muss eine Verbindung mit</span><span class="sxs-lookup"><span data-stu-id="1e32b-120">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="1e32b-121">Gibt an, welche Listener im Endpunkt des ausgewählten Replikats an, zu dem der Client eine eine Verbindung herstellen soll</span><span class="sxs-lookup"><span data-stu-id="1e32b-121">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="1e32b-122">Gibt die wiederholungsrichtlinie, die für Ausnahmen, die verwendet werden soll, die auftreten, wenn den Client zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="1e32b-122">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e32b-123">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="1e32b-123">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-124">Ruft ab oder der CommunicationClient für den angegebenen verfügbarkeitsgruppenlistener-Namen durch die Lösung basierend auf den angegebenen PreviousRsp erstellt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-124">Gets or Creates the CommunicationClient for the specified listener name by resolving based on the given previousRsp.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e32b-125">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-125">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="1e32b-126">Das Ergebnis der Aufgabe ist die CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) Objekt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-126">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TCommunicationClient&gt; GetClientAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TCommunicationClient&gt; GetClientAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector targetReplicaSelector, string listenerName, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;&#xA;override this.GetClientAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector * string * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="communicationClientFactoryBase.GetClientAsync (serviceUri, partitionKey, targetReplicaSelector, listenerName, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.GetClientAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector,System.String,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;GetClientAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="targetReplicaSelector" Type="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
        <Parameter Name="listenerName" Type="System.String" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="1e32b-127">URI des Diensts aufgelöst</span><span class="sxs-lookup"><span data-stu-id="1e32b-127">Uri of the service to resolve</span></span></param>
        <param name="partitionKey"><span data-ttu-id="1e32b-128">Schlüssel, die Partition zum Auflösen identifiziert</span><span class="sxs-lookup"><span data-stu-id="1e32b-128">Key that identifies the partition to resolve</span></span></param>
        <param name="targetReplicaSelector"><span data-ttu-id="1e32b-129">Gibt an, welches Replikat in der Partition, die durch den Partitionsschlüssel identifiziert, die Clients muss eine Verbindung mit</span><span class="sxs-lookup"><span data-stu-id="1e32b-129">Specifies which replica in the partition identified by the partition key, the client should connect to</span></span></param>
        <param name="listenerName"><span data-ttu-id="1e32b-130">Gibt an, welche Listener im Endpunkt des ausgewählten Replikats an, zu dem der Client eine eine Verbindung herstellen soll</span><span class="sxs-lookup"><span data-stu-id="1e32b-130">Specifies which listener in the endpoint of the chosen replica, to which the client should connect to</span></span></param>
        <param name="retrySettings"><span data-ttu-id="1e32b-131">Gibt die wiederholungsrichtlinie, die für Ausnahmen, die verwendet werden soll, die auftreten, wenn den Client zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="1e32b-131">Specifies the retry policy that should be used for exceptions that occur when creating the client.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e32b-132">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="1e32b-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-133">Löst eine Partition des angegebenen Dienstes, einen oder mehrere kommunikationsüberwachungen auf und gibt einen Client für die Kommunikation mit dem Endpunkt, der angegebene ListenerName entspricht.</span><span class="sxs-lookup"><span data-stu-id="1e32b-133">Resolves a partition of the specified service containing one or more communication listeners and returns a client to communicate to the endpoint corresponding to the given listenerName.</span></span> 
            
            <span data-ttu-id="1e32b-134">Der Endpunkt des Diensts besitzt das Format - {"Endpunkte": {"Listener1": "Endpoint1", "Listener2": "Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="1e32b-134">The endpoint of the service is of the form - {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e32b-135">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-135">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="1e32b-136">Das Ergebnis der Aufgabe ist die CommunicationClient (<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) Objekt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-136">The result of the Task is the CommunicationClient(<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />) object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportOperationExceptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync (TCommunicationClient client, Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt; ReportOperationExceptionAsync(!TCommunicationClient client, class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;&#xA;override this.ReportOperationExceptionAsync : 'CommunicationClient * Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;" Usage="communicationClientFactoryBase.ReportOperationExceptionAsync (client, exceptionInformation, retrySettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1.ReportOperationExceptionAsync(`0,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1/&lt;ReportOperationExceptionAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="1e32b-137">Kommunikationsclient</span><span class="sxs-lookup"><span data-stu-id="1e32b-137">Communication client</span></span></param>
        <param name="exceptionInformation"><span data-ttu-id="1e32b-138">Informationen über die Ausnahme, die bei der Kommunikation mit dem Dienst aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="1e32b-138">Information about the exception that occurred when communicating with the service.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="1e32b-139">Gibt die wiederholungsrichtlinie, die für die gemeldeten Ausnahmebehandlung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1e32b-139">Specifies the retry policy that should be used for handling the reported exception.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e32b-140">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="1e32b-140">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-141">Behandelt die Ausnahmen, die in der CommunicationClient auftreten, wenn eine Nachricht an den Dienst senden</span><span class="sxs-lookup"><span data-stu-id="1e32b-141">Handles the exceptions that occur in the CommunicationClient when sending a message to the Service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e32b-142">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1e32b-142">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="1e32b-143">Das Ergebnis des Vorgangs ist ein <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> -Objekt, das bestimmt, wie die wiederholungsrichtlinie für diese Ausnahme ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="1e32b-143">The result of the Task is a <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" /> object that determines how the retry policy for this exception.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceResolver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver ServiceResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ServiceResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceResolver As IServicePartitionResolver" />
      <MemberSignature Language="F#" Value="member this.ServiceResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e32b-144">Ruft die von der Factory Client zum Auflösen von den Dienstendpunkt verwendet ServicePartitionResolver ab.</span><span class="sxs-lookup"><span data-stu-id="1e32b-144">Gets the ServicePartitionResolver used by the client factory for resolving the service endpoint.</span></span>
            </summary>
        <value><span data-ttu-id="1e32b-145">ServicePartitionResolver</span><span class="sxs-lookup"><span data-stu-id="1e32b-145">ServicePartitionResolver</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="protected string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.TraceId" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TraceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e32b-146">Ruft den ablaufverfolgungsbezeichner für die Diagnose für diese Komponente ab.</span><span class="sxs-lookup"><span data-stu-id="1e32b-146">Gets the diagnostics trace identifier for this component.</span></span>
            </summary>
        <value><span data-ttu-id="1e32b-147">Ablaufverfolgungsbezeichner</span><span class="sxs-lookup"><span data-stu-id="1e32b-147">Trace identifier</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(!TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="client"><span data-ttu-id="1e32b-148">der Kommunikationsclient</span><span class="sxs-lookup"><span data-stu-id="1e32b-148">the communication client</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-149">Gibt "true" zurück, wenn der Client noch gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1e32b-149">Returns true if the client is still valid.</span></span> <span data-ttu-id="1e32b-150">Dienstorientierte verbindungstransporte können diese Methode verwenden, um anzugeben, dass der Client nicht mehr mit dem Dienst verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="1e32b-150">Connection oriented transports can use this method to indicate that the client is no longer connected to the service.</span></span>
            </summary>
        <returns><span data-ttu-id="1e32b-151">"true", wenn der Client gültig, andernfalls false ist</span><span class="sxs-lookup"><span data-stu-id="1e32b-151">true if the client is valid, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateClient">
      <MemberSignature Language="C#" Value="protected abstract bool ValidateClient (string endpoint, TCommunicationClient client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool ValidateClient(string endpoint, !TCommunicationClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.CommunicationClientFactoryBase`1.ValidateClient(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateClient (endpoint As String, client As TCommunicationClient) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ValidateClient : string * 'CommunicationClient -&gt; bool" Usage="communicationClientFactoryBase.ValidateClient (endpoint, client)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="client" Type="TCommunicationClient" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="1e32b-152">Gibt an, dass die erwarteten Endpunkt, den vorstellen den Client, verbunden ist</span><span class="sxs-lookup"><span data-stu-id="1e32b-152">Specifies the expected endpoint to which we think the client is connected to</span></span></param>
        <param name="client"><span data-ttu-id="1e32b-153">der Kommunikationsclient</span><span class="sxs-lookup"><span data-stu-id="1e32b-153">the communication client</span></span></param>
        <summary>
            <span data-ttu-id="1e32b-154">Gibt true zurück, wenn der Client noch gültig und mit den im Parameter angegebenen Endpunkt verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="1e32b-154">Returns true if the client is still valid and connected to the endpoint specified in the parameter.</span></span>
            </summary>
        <returns><span data-ttu-id="1e32b-155">"true", wenn der Client gültig, andernfalls false ist</span><span class="sxs-lookup"><span data-stu-id="1e32b-155">true if the client is valid, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>