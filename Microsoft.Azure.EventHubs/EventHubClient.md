<Type Name="EventHubClient" FullName="Microsoft.Azure.EventHubs.EventHubClient">
  <TypeSignature Language="C#" Value="public abstract class EventHubClient : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EventHubClient extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EventHubClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubClient = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2a6ec-101">Verankern Sie die Klasse – alle EventHub Client Vorgänge beginnen Sie hier.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-101">Anchor class - all EventHub client operations start here.</span></span>
            <span data-ttu-id="2a6ec-102">Siehe <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-102">See <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override sealed System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;CloseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a6ec-103">Schließt und zugeordnete Ressourcen frei <see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-103">Closes and releases resources associated with <see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.Azure.EventHubs.ITokenProvider,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.Azure.EventHubs.ITokenProvider * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, tokenProvider, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.EventHubs.ITokenProvider" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2a6ec-104">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-104">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2a6ec-105">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2a6ec-105">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2a6ec-106">Event Hub-Pfad</span><span class="sxs-lookup"><span data-stu-id="2a6ec-106">Event Hub path</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="2a6ec-107">Tokenanbieter, der Sicherheitstoken für die Autorisierung zu generieren, wird.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-107">Token provider which will generate security tokens for authorization.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2a6ec-108">Timeout des Vorgangs für Event Hubs-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-108">Operation timeout for Event Hubs operations.</span></span></param>
        <param name="transportType"><span data-ttu-id="2a6ec-109">Der Transporttyp für Verbindung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-109">Transport type on connection.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-110">Erstellt eine neue Instanz des Event Hubs-Clients, die mit den angegebenen Endpunkt, der Entität Pfad und der Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-110">Creates a new instance of the Event Hubs client using the specified endpoint, entity path, and token provider.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2a6ec-111">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-111">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2a6ec-112">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2a6ec-112">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2a6ec-113">Event Hub-Pfad</span><span class="sxs-lookup"><span data-stu-id="2a6ec-113">Event Hub path</span></span></param>
        <param name="authContext"><span data-ttu-id="2a6ec-114">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-114">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="2a6ec-115">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-115">The client assertion certificate credential.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2a6ec-116">Timeout des Vorgangs für Event Hubs-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-116">Operation timeout for Event Hubs operations.</span></span></param>
        <param name="transportType"><span data-ttu-id="2a6ec-117">Der Transporttyp für Verbindung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-117">Transport type on connection.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-118">Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-118">Creates a new instance of the Event Hubs client using the specified endpoint, entity path, AAD authentication context.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2a6ec-119">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-119">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2a6ec-120">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2a6ec-120">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2a6ec-121">Event Hub-Pfad</span><span class="sxs-lookup"><span data-stu-id="2a6ec-121">Event Hub path</span></span></param>
        <param name="authContext"><span data-ttu-id="2a6ec-122">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-122">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="2a6ec-123">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-123">The app credential.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2a6ec-124">Timeout des Vorgangs für Event Hubs-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-124">Operation timeout for Event Hubs operations.</span></span></param>
        <param name="transportType"><span data-ttu-id="2a6ec-125">Der Transporttyp für Verbindung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-125">Transport type on connection.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-126">Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-126">Creates a new instance of the Event Hubs client using the specified endpoint, entity path, AAD authentication context.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2a6ec-127">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-127">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2a6ec-128">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2a6ec-128">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2a6ec-129">Event Hub-Pfad</span><span class="sxs-lookup"><span data-stu-id="2a6ec-129">Event Hub path</span></span></param>
        <param name="authContext"><span data-ttu-id="2a6ec-130">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-130">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="2a6ec-131">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-131">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="2a6ec-132">Die RedirectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-132">The redirectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="2a6ec-133">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="2a6ec-133">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="2a6ec-134">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="2a6ec-134">User Identifier</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2a6ec-135">Timeout des Vorgangs für Event Hubs-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-135">Operation timeout for Event Hubs operations.</span></span></param>
        <param name="transportType"><span data-ttu-id="2a6ec-136">Der Transporttyp für Verbindung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-136">Transport type on connection.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-137">Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-137">Creates a new instance of the Event Hubs client using the specified endpoint, entity path, AAD authentication context.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.Azure.EventHubs.EventDataBatch" Usage="eventHubClient.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2a6ec-138">Erstellt einen Batch, in denen Daten von Ereignisobjekten hinzugefügt werden können, für den späteren Aufruf von "SendAsync".</span><span class="sxs-lookup"><span data-stu-id="2a6ec-138">Creates a batch where event data objects can be added for later SendAsync call.</span></span></summary>
        <returns><span data-ttu-id="2a6ec-139">Gibt <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-139">Returns <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, DateTime startTime, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.DateTime,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * DateTime * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-140">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-140">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-141">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-141">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-142">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-142">All data received will be from this partition only.</span></span></param>
        <param name="startTime"><span data-ttu-id="2a6ec-143">das Datum-Uhrzeit instant, das Empfangsvorgänge erhalten Start Ereignisse aus.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-143">the date time instant that receive operations will start receive events from.</span></span> <span data-ttu-id="2a6ec-144">Empfangene Ereignisse verfügen über <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> nach diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-144">Events received will have <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> later than this instant.</span></span></param>
        <param name="epoch"><span data-ttu-id="2a6ec-145">ein eindeutiger Bezeichner (Epoche Wert), den der Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-145">a unique identifier (epoch value) that the service uses, to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="2a6ec-146">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-146">Options for a event hub receiver.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-147">Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-147">Create a Epoch based EventHub receiver with given partition id and start receiving from the beginning of the partition stream.</span></span>
            <span data-ttu-id="2a6ec-148">Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-148">The receiver is created for a specific EventHub Partition from the specific consumer group.</span></span>
            <span data-ttu-id="2a6ec-149"><para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-149"><para />It is important to pay attention to the following when creating epoch based receiver: <para />- Ownership enforcement: Once you created an epoch based receiver, you cannot create a non-epoch receiver to the same consumerGroup-Partition combo until all receivers to the combo are closed.</span></span>
            <span data-ttu-id="2a6ec-150"><para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-150"><para />- Ownership stealing: If a receiver with higher epoch value is created for a consumerGroup-Partition combo, any older epoch receiver to that combo will be force closed.</span></span>
            <span data-ttu-id="2a6ec-151"><para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-151"><para />- Any receiver closed due to lost of ownership to a consumerGroup-Partition combo will get ReceiverDisconnectedException for all operations from that receiver.</span></span>
            </summary>
        <returns><span data-ttu-id="2a6ec-152">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-152">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-153">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-153">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-154">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-154">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-155">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-155">All data received will be from this partition only.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="2a6ec-156">der Offset, starten Sie den Empfang von Ereignissen aus.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-156">the offset to start receiving the events from.</span></span> <span data-ttu-id="2a6ec-157">Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span><span class="sxs-lookup"><span data-stu-id="2a6ec-157">To receive from start of the stream use <see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span></span></param>
        <param name="epoch"><span data-ttu-id="2a6ec-158">ein eindeutiger Bezeichner (Epoche Wert), den den Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-158">an unique identifier (epoch value) that the service uses, to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="2a6ec-159">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-159">Options for a event hub receiver.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-160">Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-160">Create a Epoch based EventHub receiver with given partition id and start receiving from the beginning of the partition stream.</span></span>
            <span data-ttu-id="2a6ec-161">Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-161">The receiver is created for a specific EventHub Partition from the specific consumer group.</span></span>
            <span data-ttu-id="2a6ec-162"><para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-162"><para /> It is important to pay attention to the following when creating epoch based receiver: <para />- Ownership enforcement: Once you created an epoch based receiver, you cannot create a non-epoch receiver to the same consumerGroup-Partition combo until all receivers to the combo are closed.</span></span>
            <span data-ttu-id="2a6ec-163"><para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-163"><para />- Ownership stealing: If a receiver with higher epoch value is created for a consumerGroup-Partition combo, any older epoch receiver to that combo will be force closed.</span></span>
            <span data-ttu-id="2a6ec-164"><para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-164"><para />- Any receiver closed due to lost of ownership to a consumerGroup-Partition combo will get ReceiverDisconnectedException for all operations from that receiver.</span></span>
            </summary>
        <returns><span data-ttu-id="2a6ec-165">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-165">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Boolean,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * bool * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-166">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-166">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-167">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-167">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-168">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-168">All data received will be from this partition only.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="2a6ec-169">der Offset, starten Sie den Empfang von Ereignissen aus.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-169">the offset to start receiving the events from.</span></span> <span data-ttu-id="2a6ec-170">Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span><span class="sxs-lookup"><span data-stu-id="2a6ec-170">To receive from start of the stream use <see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="2a6ec-171">Bei "true", die StartingOffset als inklusive Offset - behandelt wird wird d. h. das erste Ereignis zurückgegeben, das den Anfangsoffset verfügt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-171">if set to true, the startingOffset is treated as an inclusive offset - meaning the first event returned is the one that has the starting offset.</span></span> <span data-ttu-id="2a6ec-172">Normalerweise die erste zurückgegebene Ereignis ist das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-172">Normally first event returned is the event after the starting offset.</span></span></param>
        <param name="epoch"><span data-ttu-id="2a6ec-173">ein eindeutiger Bezeichner (Epoche Wert), den den Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-173">an unique identifier (epoch value) that the service uses, to enforce partition/lease ownership.</span></span> </param>
        <param name="receiverOptions"><span data-ttu-id="2a6ec-174">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-174">Options for a event hub receiver.</span></span></param>
        <summary>
             <span data-ttu-id="2a6ec-175">Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-175">Create a Epoch based EventHub receiver with given partition id and start receiving from the beginning of the partition stream.</span></span>
             <span data-ttu-id="2a6ec-176">Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-176">The receiver is created for a specific EventHub Partition from the specific consumer group.</span></span>
             <span data-ttu-id="2a6ec-177"><para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-177"><para /> It is important to pay attention to the following when creating epoch based receiver: <para />- Ownership enforcement: Once you created an epoch based receiver, you cannot create a non-epoch receiver to the same consumerGroup-Partition combo until all receivers to the combo are closed.</span></span>
             <span data-ttu-id="2a6ec-178"><para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-178"><para />- Ownership stealing: If a receiver with higher epoch value is created for a consumerGroup-Partition combo, any older epoch receiver to that combo will be force closed.</span></span>
             <span data-ttu-id="2a6ec-179"><para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-179"><para />- Any receiver closed due to lost of ownership to a consumerGroup-Partition combo will get ReceiverDisconnectedException for all operations from that receiver.</span></span>
             </summary>
        <returns><span data-ttu-id="2a6ec-180">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-180">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"></param>
        <summary>
            <span data-ttu-id="2a6ec-181">Erstellt eine neue Instanz des Event Hubs-Clients, die mithilfe der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-181">Creates a new instance of the Event Hubs client using the specified connection string.</span></span> <span data-ttu-id="2a6ec-182">Sie können die EntityPath-Eigenschaft mit dem Namen des Event Hubs auffüllen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-182">You can populate the EntityPath property with the name of the Event Hub.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionSender">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreatePartitionSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionSender (partitionId As String) As PartitionSender" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionSender : string -&gt; Microsoft.Azure.EventHubs.PartitionSender" Usage="eventHubClient.CreatePartitionSender partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="2a6ec-183">PartitionId von EventHub zum Senden der <see cref="T:Microsoft.Azure.EventHubs.EventData" />des an.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-183">partitionId of EventHub to send the <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s to.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-184">Erstellen einer <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" /> die veröffentlichen können <see cref="T:Microsoft.Azure.EventHubs.EventData" />des direkt zu einer bestimmten Event Hub-Partition (Absender Typ Iii.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-184">Create a <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" /> which can publish <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s directly to a specific EventHub partition (sender type iii.</span></span> <span data-ttu-id="2a6ec-185">in der folgenden Liste).</span><span class="sxs-lookup"><span data-stu-id="2a6ec-185">in the below list).</span></span>
            <span data-ttu-id="2a6ec-186"><para />Es gibt 3 Muster/Möglichkeiten zum Senden an EventHubs: <para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-186"><para /> There are 3 patterns/ways to send to EventHubs: <para>i.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para><para>ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /></para><para>iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para></span></span></summary>
        <returns><span data-ttu-id="2a6ec-187">Die erstellte PartitionSender</span><span class="sxs-lookup"><span data-stu-id="2a6ec-187">The created PartitionSender</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionSender" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, DateTime startTime, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.DateTime,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * DateTime * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startTime, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-188">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-188">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-189">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-189">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-190">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-190">All data received will be from this partition only.</span></span></param>
        <param name="startTime"><span data-ttu-id="2a6ec-191">Ereignisse von empfangen werden der DateTime-Wert, der Zeitpunkt, das Empfangsvorgänge gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-191">the DateTime instant that receive operations will start receive events from.</span></span> <span data-ttu-id="2a6ec-192">Empfangene Ereignisse verfügen über <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> nach diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-192">Events received will have <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> later than this Instant.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="2a6ec-193">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-193">Options for a event hub receiver.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-194">Erstellen den EventHub-Empfänger für die angegebenen Partitions-Id und aus dem angegebenen Startoffset empfangen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-194">Create the EventHub receiver with given partition id and start receiving from the specified starting offset.</span></span>
            <span data-ttu-id="2a6ec-195">Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-195">The receiver is created for a specific EventHub Partition from the specific consumer group.</span></span>
            </summary>
        <returns><span data-ttu-id="2a6ec-196">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-196">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startingOffset, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startingOffset, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-197">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-197">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-198">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-198">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-199">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-199">All data received will be from this partition only.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="2a6ec-200">der Offset, starten Sie den Empfang von Ereignissen aus.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-200">the offset to start receiving the events from.</span></span> <span data-ttu-id="2a6ec-201">Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span><span class="sxs-lookup"><span data-stu-id="2a6ec-201">To receive from start of the stream use <see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span></span></param>
        <param name="receiverOptions"><span data-ttu-id="2a6ec-202">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-202">Options for a event hub receiver.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-203">Erstellen Sie einen Empfänger für eine bestimmte EventHub-Partition aus der bestimmte consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-203">Create a receiver for a specific EventHub partition from the specific consumer group.</span></span>
            <span data-ttu-id="2a6ec-204"><para />Hinweis: Es kann eine maximale Anzahl von Empfängern, die pro ConsumerGroup pro Partition parallel ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-204"><para /> NOTE: There can be a maximum number of receivers that can run in parallel per ConsumerGroup per Partition.</span></span> <span data-ttu-id="2a6ec-205">Das Limit wird vom Event Hub-Dienst erzwungen,-Aktueller Grenzwert ist 5 Empfänger parallel.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-205">The limit is enforced by the Event Hub service - current limit is 5 receivers in parallel.</span></span> <span data-ttu-id="2a6ec-206">Müssen mehrere Empfänger müssen das Lesen aus Offsets, die liegen weit auseinander auf die gleiche consumergruppe / Kombinationsfeld partitionieren erheblich auf die Leistung auswirken.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-206">Having multiple receivers reading from offsets that are far apart on the same consumer group / partition combo will have significant performance Impact.</span></span> 
            </summary>
        <returns><span data-ttu-id="2a6ec-207">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-207">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,System.Boolean,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * bool * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"><span data-ttu-id="2a6ec-208">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-208">the consumer group name that this receiver should be grouped under.</span></span></param>
        <param name="partitionId"><span data-ttu-id="2a6ec-209">Die Partition-Id, der der Empfänger zu gehört.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-209">the partition Id that the receiver belongs to.</span></span> <span data-ttu-id="2a6ec-210">Von dieser Partition nur werden alle Daten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-210">All data received will be from this partition only.</span></span></param>
        <param name="startOffset"><span data-ttu-id="2a6ec-211">der Offset, starten Sie den Empfang von Ereignissen aus.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-211">the offset to start receiving the events from.</span></span> <span data-ttu-id="2a6ec-212">So erhalten Sie vom Anfang von Streams verwendet wurde:<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span><span class="sxs-lookup"><span data-stu-id="2a6ec-212">To receive from start of the stream use: <see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="2a6ec-213">"true", die StartingOffset als inklusive Offset - behandelt, d. h. das erste Ereignis zurückgegeben wird, wenn die <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param></span><span class="sxs-lookup"><span data-stu-id="2a6ec-213">if set to true, the startingOffset is treated as an inclusive offset - meaning the first event returned is the <param name="receiverOptions">Options for a event hub receiver.</param></span></span>
            <span data-ttu-id="2a6ec-214">eine, die den Anfangsoffset hat.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-214">one that has the starting offset.</span></span> <span data-ttu-id="2a6ec-215">Normalerweise die erste zurückgegebene Ereignis ist das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-215">Normally first event returned is the event after the starting offset.</span></span></param>
        <param name="receiverOptions">To be added.</param>
        <summary>
            <span data-ttu-id="2a6ec-216">Erstellen den EventHub-Empfänger für die angegebenen Partitions-Id und aus dem angegebenen Startoffset empfangen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-216">Create the EventHub receiver with given partition id and start receiving from the specified starting offset.</span></span>
            <span data-ttu-id="2a6ec-217">Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-217">The receiver is created for a specific EventHub Partition from the specific consumer group.</span></span>
            </summary>
        <returns><span data-ttu-id="2a6ec-218">Die erstellte PartitionReceiver</span><span class="sxs-lookup"><span data-stu-id="2a6ec-218">The created PartitionReceiver</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity (Uri endpointAddress, string entityPath, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string entityPath, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity (endpointAddress, entityPath, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="2a6ec-219">Vollständig qualifizierten Domänennamen für Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-219">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="2a6ec-220">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="2a6ec-220">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="2a6ec-221">Event Hub-Pfad</span><span class="sxs-lookup"><span data-stu-id="2a6ec-221">Event Hub path</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="2a6ec-222">Timeout des Vorgangs für Event Hubs-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-222">Operation timeout for Event Hubs operations.</span></span></param>
        <param name="transportType"><span data-ttu-id="2a6ec-223">Der Transporttyp für Verbindung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-223">Transport type on connection.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-224">Erstellt eine neue Instanz des Event Hubs-Clients, die unter Verwendung des angegebenen Endpunkt, die Entität Pfad auf der Azure verwaltete Dienstidentität-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-224">Creates a new instance of the Event Hubs client using the specified endpoint, entity path on Azure Managed Service Identity authentication.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="2a6ec-225">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-225">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="2a6ec-226">"true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> mit <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-226">true if a client wants to access <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> using <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string" Usage="Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2a6ec-227">Ruft den Namen der EventHub ab.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-227">Gets the name of the EventHub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.GetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetPartitionRuntimeInformationAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="2a6ec-228">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-228">The partition ID.</span></span></param>
        <summary><span data-ttu-id="2a6ec-229">Ruft die Laufzeitinformationen für die angegebene Partition des Event Hubs ab.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-229">Retrieves runtime information for the specified partition of the Event Hub.</span></span></summary>
        <returns><span data-ttu-id="2a6ec-230">Gibt <see cref="T:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-230">Returns <see cref="T:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetRuntimeInformationAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a6ec-231">Ruft die EventHub-Laufzeitinformationen ab</span><span class="sxs-lookup"><span data-stu-id="2a6ec-231">Retrieves EventHub runtime information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCloseAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnCloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.OnCloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Nullable&lt;DateTime&gt; startTime, Nullable&lt;long&gt; epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int64&gt; epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCreateReceiver(System.String,System.String,System.String,System.Boolean,System.Nullable{System.DateTime},System.Nullable{System.Int64},Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateReceiver : string * string * string * bool * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.OnCreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="epoch" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"></param>
        <param name="partitionId"></param>
        <param name="startOffset"></param>
        <param name="offsetInclusive"></param>
        <param name="startTime"></param>
        <param name="epoch"></param>
        <param name="receiverOptions"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.OnGetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.OnGetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRetryPolicyUpdate">
      <MemberSignature Language="C#" Value="protected override void OnRetryPolicyUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnRetryPolicyUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnRetryPolicyUpdate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnRetryPolicyUpdate ()" />
      <MemberSignature Language="F#" Value="override this.OnRetryPolicyUpdate : unit -&gt; unit" Usage="eventHubClient.OnRetryPolicyUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a6ec-232">Behandeln Sie hier richtlinienaktualisierungen versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-232">Handle retry policy updates here.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="2a6ec-233">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-233">the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to be sent.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-234">Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> an Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-234">Send <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to EventHub.</span></span> <span data-ttu-id="2a6ec-235">Die gesendeten EventData werden auf der nach dem Zufallsprinzip ausgewählte EventHubs Partition aufgenommen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-235">The sent EventData will land on any arbitrarily chosen EventHubs partition.</span></span>
            <span data-ttu-id="2a6ec-236"><para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit der Überladung SendBatch) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii.  <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diese Methode, wenn senden: <para>a) die <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> Vorgang hoch verfügbar sein und</para><para>b) die Daten gleichmäßig verteilt werden müssen alle Partitionen; Ausnahme wird, wenn eine Teilmenge der Partitionen nicht verfügbar sind</para> <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> sendet die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einem Dienst-Gateway, die wiederum die EventData in eines der EventHub-Partitionen leitet.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-236"><para>There are 3 ways to send to EventHubs, each exposed as a method (along with its sendBatch overload):</para><para>i.    <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para><para>ii.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /></para><para>iii.  <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para> Use this method to send if: <para>a) the <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> operation should be highly available and</para><para>b) the data needs to be evenly distributed among all partitions; exception being, when a subset of partitions are unavailable</para><see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> sends the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to a Service Gateway, which in-turn will forward the EventData to one of the EventHub's partitions.</span></span>
            <span data-ttu-id="2a6ec-237">Hier wird der Algorithmus für die nachrichtenweiterleitung: <para>ich.  Weiterleiten der EventDatas EventHub-Partitionen, indem gleichmäßig verteilt Daten über alle Partitionen (zum Beispiel: Roundrobin-Methode der EventDatas auf alle EventHub-Partitionen) </para> <para>Ii. Wenn eine der Partitionen EventHub für einen Moment nicht verfügbar ist, das Gateway-Dienst automatisch erkannt und leitet Sie an eine andere verfügbare Partition - Sendevorgang hoch verfügbar machen.</para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-237">Here's the message forwarding algorithm: <para>i.  Forward the EventDatas to EventHub partitions, by equally distributing the data among all partitions (ex: Round-robin the EventDatas to all EventHub partitions) </para><para>ii. If one of the EventHub partitions is unavailable for a moment, the Service Gateway will automatically detect it and forward the message to another available partition - making the send operation highly-available.</para></span></span></summary>
        <returns><span data-ttu-id="2a6ec-238">Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-238">A Task that completes when the send operations is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventDatas" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDatas"><span data-ttu-id="2a6ec-239">Ein Batch von Ereignissen an Event Hub senden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-239">A batch of events to send to EventHub</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-240">Senden ein Batches von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> an Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-240">Send a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to EventHub.</span></span> <span data-ttu-id="2a6ec-241">Die gesendeten EventData werden auf der nach dem Zufallsprinzip ausgewählte EventHub Partition aufgenommen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-241">The sent EventData will land on any arbitrarily chosen EventHub partition.</span></span>
            <span data-ttu-id="2a6ec-242">Dies ist die am häufigsten empfohlene Methode zum Senden an Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-242">This is the most recommended way to send to EventHub.</span></span>
            
            <span data-ttu-id="2a6ec-243"><para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, der verwendet wird, senden Sie einzelne <see cref="T:Microsoft.Azure.EventHubs.EventData" />. Verwenden Sie diese Überladung, wenn Sie einen Batch senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-243"><para>There are 3 ways to send to EventHubs, to understand this particular type of send refer to the overload <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, which is used to send single <see cref="T:Microsoft.Azure.EventHubs.EventData" />. Use this overload if you need to send a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</para></span></span>
            
            <span data-ttu-id="2a6ec-244">Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen, die an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden Sie mehrere <see cref="T:Microsoft.Azure.EventHubs.EventData" />des in einer Transaktion. Acheieve ACID-Eigenschaften der Gatewaydienst leitet alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des im Batch in einer einzelnen EventHub partitionieren.</para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-244">Sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s is useful in the following cases: <para>i.    Efficient send - sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximizes the overall throughput by optimally using the number of sessions created to EventHub's service.</para><para>ii.   Send multiple <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in a Transaction. To acheieve ACID properties, the Gateway Service will forward all <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in the batch to a single EventHub partition.</para></span></span></summary>
        <returns><span data-ttu-id="2a6ec-245">Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-245">A Task that completes when the send operations is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <example>
            <span data-ttu-id="2a6ec-246">Beispielcode:</span><span class="sxs-lookup"><span data-stu-id="2a6ec-246">Sample code:</span></span>
            <code>
            var client = EventHubClient.Create("__connectionString__");
            while (true)
            {
                var events = new List&lt;EventData&gt;();
                for (int count = 1; count &lt; 11; count++)
                {
                    var payload = new PayloadEvent(count);
                    byte[] payloadBytes = Encoding.UTF8.GetBytes(JsonConvert.SerializeObject(payload));
                    var sendEvent = new EventData(payloadBytes);
                    var applicationProperties = new Dictionary&lt;string, string&gt;();
                    applicationProperties["from"] = "csharpClient";
                    sendEvent.Properties = applicationProperties;
                    events.Add(sendEvent);
                }
                    
                await client.SendAsync(events);
                Console.WriteLine("Sent Batch... Size: {0}", events.Count);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventData, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="2a6ec-247">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-247">the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to be sent.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="2a6ec-248">der partitionkey-Werte werden Hashwert berechnet werden soll, um zu bestimmen, die PartitionId die EventData zu senden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-248">the partitionKey will be hashed to determine the partitionId to send the EventData to.</span></span> <span data-ttu-id="2a6ec-249">Für die empfangene Nachricht dies möglich, die am <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-249">On the Received message this can be accessed at <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</span></span></param>
        <summary>
             <span data-ttu-id="2a6ec-250">Sendet eine "<see cref="T:Microsoft.Azure.EventHubs.EventData" /> mit einem PartitionKey an Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-250">Sends an '<see cref="T:Microsoft.Azure.EventHubs.EventData" /> with a partitionKey to EventHub.</span></span> <span data-ttu-id="2a6ec-251">Alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des mit einem PartitionKey ist sichergestellt, dass auf die gleiche Partition aufgenommen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-251">All <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s with a partitionKey are guaranteed to land on the same partition.</span></span>
             <span data-ttu-id="2a6ec-252">Dieses Muster senden hervorheben Korrelation der Daten über die allgemeine Verfügbarkeit und die Latenz.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-252">This send pattern emphasize data correlation over general availability and latency.</span></span>
             <span data-ttu-id="2a6ec-253"><para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit seiner im Batchmodus Überladung) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diesen Typ des Sendeports ein, wenn: <para>eine) besteht der Bedarf für die Korrelation der Ereignisse, die auf der Grundlage Absender Instanz; Der Absender kann eine eindeutige ID zu generieren, und legen Sie es als PartitionKey - die für die empfangene Nachricht für die Korrelation verwendet werden können</para><para>b) der Client möchte Kontrolle über die Verteilung der Daten auf Partitionen zu übernehmen.</para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-253"><para>There are 3 ways to send to EventHubs, each exposed as a method (along with its batched overload):</para><para>i.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para><para>ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /></para><para>iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para> Use this type of send if: <para>a)  There is a need for correlation of events based on Sender instance; The sender can generate a UniqueId and set it as partitionKey - which on the received Message can be used for correlation</para><para>b) The client wants to take control of distribution of data across partitions.</para></span></span>
             <span data-ttu-id="2a6ec-254">Mehrere PartitionKeys könnte zu einer einzigen Partition zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-254">Multiple PartitionKeys could be mapped to one Partition.</span></span> <span data-ttu-id="2a6ec-255">EventHubs-Dienst verwendet einen proprietären Hash-Algorithmus eine PartitionId PartitionKey zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-255">EventHubs service uses a proprietary Hash algorithm to map the PartitionKey to a PartitionId.</span></span>
             <span data-ttu-id="2a6ec-256">Mit diesem Typ des Sendeports (senden, die mit einer bestimmten PartitionKey) konnte in einigen Fällen in Partitionen zurückgeben, was nicht gleichmäßig verteilt sind.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-256">Using this type of send (Sending using a specific partitionKey) could sometimes result in partitions which are not evenly distributed.</span></span> 
             </summary>
        <returns><span data-ttu-id="2a6ec-257">eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-257">A Task that completes when the send operation is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData), partitionKey As String) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventDatas, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;SendAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventDatas"><span data-ttu-id="2a6ec-258">der Batch von Ereignissen an Event Hub senden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-258">the batch of events to send to EventHub</span></span></param>
        <param name="partitionKey"><span data-ttu-id="2a6ec-259">der partitionkey-Werte werden Hashwert berechnet werden soll, um zu bestimmen, die PartitionId die EventData zu senden.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-259">the partitionKey will be hashed to determine the partitionId to send the EventData to.</span></span> <span data-ttu-id="2a6ec-260">Für die empfangene Nachricht dies möglich, die am <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-260">On the Received message this can be accessed at <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</span></span></param>
        <summary>
            <span data-ttu-id="2a6ec-261">Senden einer "Batch <see cref="T:Microsoft.Azure.EventHubs.EventData" /> mit demselben PartitionKey" an Event Hub.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-261">Send a 'batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> with the same partitionKey' to EventHub.</span></span> <span data-ttu-id="2a6ec-262">Alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des mit einem PartitionKey ist sichergestellt, dass auf die gleiche Partition aufgenommen.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-262">All <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s with a partitionKey are guaranteed to land on the same partition.</span></span>
            <span data-ttu-id="2a6ec-263">Mehrere PartitionKey werden zu einer einzigen Partition zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-263">Multiple PartitionKey's will be mapped to one Partition.</span></span>
            <span data-ttu-id="2a6ec-264"><para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />, die vom selben Typ des Sendeports und wird verwendet, um die einzelnen senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para>Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden mehrere Ereignisse in einer Transaktion. Dies ist der Grund, warum gesendet, alle Ereignisse in einem Batch muss denselben PartitionKey (sodass sie nur zu einer Partition gesendet werden).</para></span><span class="sxs-lookup"><span data-stu-id="2a6ec-264"><para> There are 3 ways to send to EventHubs, to understand this particular type of send refer to the overload <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />, which is the same type of send and is used to send single <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para> Sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s is useful in the following cases: <para>i.    Efficient send - sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximizes the overall throughput by optimally using the number of sessions created to EventHubs service.</para><para>ii.   Sending multiple events in One Transaction. This is the reason why all events sent in a batch needs to have same partitionKey (so that they are sent to one partition only).</para></span></span></summary>
        <returns><span data-ttu-id="2a6ec-265">eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2a6ec-265">A Task that completes when the send operation is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>