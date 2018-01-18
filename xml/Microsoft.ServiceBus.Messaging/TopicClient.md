<Type Name="TopicClient" FullName="Microsoft.ServiceBus.Messaging.TopicClient">
  <TypeSignature Language="C#" Value="public abstract class TopicClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TopicClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TopicClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type TopicClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="5be35-101">Eine Premium-Klasse, die zur Verwendung für den Zugriff auf eine <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> laufzeitvorgänge ausführen.</span><span class="sxs-lookup"><span data-stu-id="5be35-101">An anchor class used to access a <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> to perform run-time operations.</span></span></summary>
    <remarks>To be added.</remarks>
    <altmember cref="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
    <example>
      <code>
             <span data-ttu-id="5be35-102">Erstellen von Einstellungen für die MessagingFactory (für Rutime Vorgänge) MessagingFactorySettings FactorySettings neue MessagingFactorySettings() = {NetMessagingTransportSettings = neue NetMessagingTransportSettings(), Anmeldeinformationen = TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName, IssuerKey)};</span><span class="sxs-lookup"><span data-stu-id="5be35-102">// Create settings for the MessagingFactory (for rutime operations) MessagingFactorySettings factorySettings = new MessagingFactorySettings() { NetMessagingTransportSettings = new NetMessagingTransportSettings(), Credential = TransportClientCredentialBase.CreateSharedSecretCredential(IssuerName, IssuerKey), };</span></span>
             
             <span data-ttu-id="5be35-103">Erstellen der Factory MessagingFactory MessagingFactory = MessagingFactory.Create (MyServiceBusNamespace, FactorySettings);</span><span class="sxs-lookup"><span data-stu-id="5be35-103">// Create the MessagingFactory MessagingFactory factory = MessagingFactory.Create(myServiceBusNamespace, factorySettings);</span></span>
                
                <span data-ttu-id="5be35-104">/ / Senden von Nachrichten an ein Thema / / \*\*\*</span><span class="sxs-lookup"><span data-stu-id="5be35-104">//******************************************************************************** //                          Sending messages to a Topic //********************************************************************************</span></span>
             
            <span data-ttu-id="5be35-105">Erstellen von Thema Client TopicClient MyTopicClient = Factory. CreateTopicClient(myTopic);</span><span class="sxs-lookup"><span data-stu-id="5be35-105">// Create topic client TopicClient myTopicClient = factory.CreateTopicClient(myTopic);</span></span>
             
             <span data-ttu-id="5be35-106">Erstellen Sie einen Sender //MessageSender MyMessageSender = myTopicClient.CreateSender(SendMode.Default);</span><span class="sxs-lookup"><span data-stu-id="5be35-106">// Create a sender //MessageSender myMessageSender = myTopicClient.CreateSender(SendMode.Default);</span></span>
             
            <span data-ttu-id="5be35-107">Senden von Nachrichten Liste &lt;Objekt&gt; Probleme = neue Liste &lt;Objekt&gt;(); Foreach (Var Problem Punkte) {myMessageSender.Send (neue BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="5be35-107">// Send messages List &lt;object&gt; Issues = new List &lt;object&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="topicClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="5be35-108">Bei der Planung einer Nachricht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5be35-108">Returned on scheduling a message.</span></span></param>
        <summary>
            <span data-ttu-id="5be35-109">Bricht eine geplante Nachricht</span><span class="sxs-lookup"><span data-stu-id="5be35-109">Cancels a scheduled message</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="5be35-110">Der Pfad.</span><span class="sxs-lookup"><span data-stu-id="5be35-110">The path.</span></span></param>
        <summary><span data-ttu-id="5be35-111">Erstellt eine neue Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-111">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></summary>
        <returns><span data-ttu-id="5be35-112">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-112">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-113">Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen.</span><span class="sxs-lookup"><span data-stu-id="5be35-113">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="5be35-114">Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben.</span><span class="sxs-lookup"><span data-stu-id="5be35-114">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="5be35-115">Das Format des Abschnitts lautet wie folgt:</span><span class="sxs-lookup"><span data-stu-id="5be35-115">The format of the section is as follows:</span></span>
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="5be35-116">Vollständig qualifizierten Domänennamen für Sercvice Bus.</span><span class="sxs-lookup"><span data-stu-id="5be35-116">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="5be35-117">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="5be35-117">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="5be35-118">Der Pfad zum Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-118">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="5be35-119">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-119">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="5be35-120">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="5be35-120">The client assertion certificate credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="5be35-121"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="5be35-121"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="5be35-122">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="5be35-122">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="5be35-123">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="5be35-123">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="5be35-124">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-124">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="5be35-125">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="5be35-125">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="5be35-126">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="5be35-126">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="5be35-127">Der Pfad zum Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-127">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="5be35-128">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-128">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="5be35-129">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="5be35-129">The app credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="5be35-130"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="5be35-130"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="5be35-131">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="5be35-131">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="5be35-132">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="5be35-132">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="5be35-133">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-133">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="5be35-134">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="5be35-134">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="5be35-135">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="5be35-135">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="5be35-136">Der Pfad zum Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-136">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="5be35-137">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-137">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="5be35-138">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-138">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="5be35-139">Die Kennwort-Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5be35-139">The user password credential.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="5be35-140"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="5be35-140"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="5be35-141">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="5be35-141">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="5be35-142">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="5be35-142">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="5be35-143">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-143">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="5be35-144">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="5be35-144">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="5be35-145">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="5be35-145">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="5be35-146">Der Pfad zum Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-146">The path to the topic.</span></span></param>
        <param name="authContext"><span data-ttu-id="5be35-147">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-147">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="5be35-148">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="5be35-148">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="5be35-149">Die RedrectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="5be35-149">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="5be35-150">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="5be35-150">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="5be35-151">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="5be35-151">User Identifier</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="5be35-152"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="5be35-152"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="5be35-153">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="5be35-153">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="5be35-154">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="5be35-154">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="5be35-155">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-155">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="5be35-156">Die zu verwendende Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5be35-156">The connection string to use.</span></span></param>
        <summary><span data-ttu-id="5be35-157">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5be35-157">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="5be35-158">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />zurück.</span><span class="sxs-lookup"><span data-stu-id="5be35-158">Returns <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-159">Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="5be35-159">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="5be35-160">Die zu verwendende Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="5be35-160">The connection string to use.</span></span></param>
        <param name="path"><span data-ttu-id="5be35-161">Der Pfad.</span><span class="sxs-lookup"><span data-stu-id="5be35-161">The path.</span></span></param>
        <summary><span data-ttu-id="5be35-162">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe der angegebenen Verbindungszeichenfolge und den Pfad zu dem Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-162">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> using the specified connection string and path to the topic.</span></span> <span data-ttu-id="5be35-163">Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="5be35-163">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="5be35-164">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-164">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-165">Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</span><span class="sxs-lookup"><span data-stu-id="5be35-165">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5be35-166">Wird ausgelöst, wenn das Format der Parameter falsch ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-166">Thrown when the format of the parameters is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity (endpointAddress, path, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="5be35-167">Vollständig qualifizierten Domänennamen für Service Bus.</span><span class="sxs-lookup"><span data-stu-id="5be35-167">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="5be35-168">Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="5be35-168">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="5be35-169">Der Pfad zum Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-169">The path to the topic.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="5be35-170"><see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</span><span class="sxs-lookup"><span data-stu-id="5be35-170"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="5be35-171">Messaging-Transporttyp.</span><span class="sxs-lookup"><span data-stu-id="5be35-171">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="5be35-172">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="5be35-172">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="5be35-173">Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-173">The created <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (topicPath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="5be35-174">Der Themenname.</span><span class="sxs-lookup"><span data-stu-id="5be35-174">The topic path.</span></span></param>
        <summary><span data-ttu-id="5be35-175">Eine Hilfsprogrammmethode, die einen vollständigen Pfad bildet, der an die Dead Letter-Warteschlange im Thema Übertragung Thema verweist, erhält der Themenname Pfad und Abonnements.</span><span class="sxs-lookup"><span data-stu-id="5be35-175">A utility method that, given the topic path and subscription name, forms a full path that points to the dead letter queue of the topic's transfer topic.</span></span></summary>
        <returns><span data-ttu-id="5be35-176">Gibt eine <see cref="T:System.String" /> , einen vollständigen Pfad, der an die Dead Letter-Warteschlange des Themas Übertragung im angegebenen Thema zeigt darstellt.</span><span class="sxs-lookup"><span data-stu-id="5be35-176">Returns a <see cref="T:System.String" /> representing a full path that points to the dead letter queue of the transfer topic of the specified topic.</span></span> <span data-ttu-id="5be35-177">Dieser Pfad kann im Erstellen von remoteereignisempfängern oder URI-Informationen (z. B. einen REST-URI) verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5be35-177">This path can be used in receiver creation or in URI formation (such as a REST URI).</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSubQueue">
      <MemberSignature Language="C#" Value="protected bool IsSubQueue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSubQueue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property IsSubQueue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSubQueue : bool" Usage="Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5be35-178">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger einer Nachricht aus einer Unterwarteschlange erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="5be35-178">Gets or sets a value that indicates whether the message receiver is created from a subqueue.</span></span></summary>
        <value><span data-ttu-id="5be35-179">"true", wenn der Empfänger einer Nachricht aus einer Unterwarteschlange erstellt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5be35-179">true if the message receiver is created from a subqueue; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5be35-180">Ruft ab oder legt die messaging-Factory, die verwendet wurde, bei der Erstellung dieser <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5be35-180">Gets or sets the messaging factory that was used in creating this <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> object.</span></span></summary>
        <value><span data-ttu-id="5be35-181">Der messaging-Factory, die verwendet wurde, bei der Erstellung dieser <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5be35-181">The messaging factory that was used in creating this <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="topicClient.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5be35-182">Führt die Aktion abbrechen.</span><span class="sxs-lookup"><span data-stu-id="5be35-182">Executes the abort action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="5be35-183">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="5be35-183">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="5be35-184">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5be35-184">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="5be35-185">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="5be35-185">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="5be35-186">Dieses Objekt wird übergeben, um die EndClose delegieren, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-186">This object is passed to the EndClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="5be35-187">Führt die Aktion "Schließen" beginnen.</span><span class="sxs-lookup"><span data-stu-id="5be35-187">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="5be35-188">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Schließvorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5be35-188">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginCreateSender (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="5be35-189">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="5be35-189">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="5be35-190">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5be35-190">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="5be35-191">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="5be35-191">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="5be35-192">Dieses Objekt wird zum Übergeben der <see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" /> Wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-192">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" /> when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="5be35-193">Führt die Begin Absender Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5be35-193">Executes the begin create sender action.</span></span></summary>
        <returns><span data-ttu-id="5be35-194">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="5be35-194">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="topicClient.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="5be35-195">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="5be35-195">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="5be35-196">Führt die Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="5be35-196">Executes the close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="topicClient.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="5be35-197">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Schließvorgang verweist.</span><span class="sxs-lookup"><span data-stu-id="5be35-197">An <see cref="T:System.IAsyncResult" /> that references the asynchronous Close operation.</span></span></param>
        <summary><span data-ttu-id="5be35-198">Führt die End-Aktion "Schließen".</span><span class="sxs-lookup"><span data-stu-id="5be35-198">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="topicClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="5be35-199">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</span><span class="sxs-lookup"><span data-stu-id="5be35-199">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="5be35-200">Führt das Ende Absender Aktion zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5be35-200">Executes the end create sender action.</span></span></summary>
        <returns><span data-ttu-id="5be35-201">Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5be35-201">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5be35-202">Ruft ab oder legt den vollständigen Pfadnamen der Datei.</span><span class="sxs-lookup"><span data-stu-id="5be35-202">Gets or sets the full pathname of the file.</span></span></summary>
        <value><span data-ttu-id="5be35-203">Der vollständige Pfadname der Datei.</span><span class="sxs-lookup"><span data-stu-id="5be35-203">The full pathname of the file.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary> <span data-ttu-id="5be35-204">Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-204">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="5be35-205">Zurückgeben der eingesehenen "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="5be35-205">return the peeked BrokeredMessage.</span></span> <span data-ttu-id="5be35-206">Null wird zurückgegeben, wenn der Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-206">A null is return if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-207">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5be35-207">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"> <span data-ttu-id="5be35-208">Die Sequenznummer der Nachricht zum Starten von einsehen.</span><span class="sxs-lookup"><span data-stu-id="5be35-208">The sequence number of message to start peeking from.</span></span> </param>
        <summary> <span data-ttu-id="5be35-209">Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-209">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="5be35-210">Zurückgeben der eingesehenen "brokeredmessage".</span><span class="sxs-lookup"><span data-stu-id="5be35-210">return the peeked BrokeredMessage.</span></span> <span data-ttu-id="5be35-211">Null wird zurückgegeben, wenn der Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-211">A null is return if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-212">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5be35-212">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"> <span data-ttu-id="5be35-213">Die maximale Anzahl von Nachrichten einsehen.</span><span class="sxs-lookup"><span data-stu-id="5be35-213">The maximum number of messages to peek.</span></span> </param>
        <summary> <span data-ttu-id="5be35-214">Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema.</span><span class="sxs-lookup"><span data-stu-id="5be35-214">Peeks a BrokeredMessage from current queue/topic.</span></span> </summary>
        <returns> <span data-ttu-id="5be35-215">eine Liste der eingesehenen BrokeredMessages zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="5be35-215">return a list of peeked BrokeredMessages.</span></span> <span data-ttu-id="5be35-216">Eine leere Liste wird zurückgegeben, wenn Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-216">An empty list is returned if peek operation cannot obtain the message within <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></returns>
        <remarks><span data-ttu-id="5be35-217">Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5be35-217">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="topicClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="5be35-218">Nachricht geplant werden</span><span class="sxs-lookup"><span data-stu-id="5be35-218">Message to be scheduled</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="5be35-219">Zeitpunkt der in die Warteschlange einreihen</span><span class="sxs-lookup"><span data-stu-id="5be35-219">Time of enqueue</span></span></param>
        <summary>
            <span data-ttu-id="5be35-220">Sendet eine Nachricht geplante</span><span class="sxs-lookup"><span data-stu-id="5be35-220">Sends a scheduled message</span></span>
            </summary>
        <returns><span data-ttu-id="5be35-221">Die Sequenznummer, die für den Abbruch erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-221">Sequence number that is needed for cancelling.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="topicClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="5be35-222">die zu sendende Meldung.</span><span class="sxs-lookup"><span data-stu-id="5be35-222">The message to send.</span></span></param>
        <summary><span data-ttu-id="5be35-223">Sendet eine Nachricht über die <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-223">Sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="5be35-224">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-224">Thrown when operation times out. Timeout period is initialized through the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5be35-225">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="5be35-225">Thrown when the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="5be35-226">Wird ausgelöst, wenn die <paramref name="message" /> wurde bereits gesendet wurden, durch eine <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> oder <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> noch einmal.</span><span class="sxs-lookup"><span data-stu-id="5be35-226">Thrown if the <paramref name="message" /> has already been sent by a <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> or <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> once already.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="5be35-227">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="5be35-227">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="5be35-228">Wird ausgelöst, wenn ein e/a oder Sicherheit Fehler vorliegt.</span><span class="sxs-lookup"><span data-stu-id="5be35-228">Thrown if there is an I/O or security error.</span></span></exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException"><span data-ttu-id="5be35-229">Wird ausgelöst, wenn bei der Serialisierung oder Deserialisierung ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="5be35-229">Thrown when an error occurs during serialization or deserialization.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="5be35-230">Wird ausgelöst, wenn das Thema nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5be35-230">Thrown if the topic does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="5be35-231">Wird ausgelöst, wenn ein Messagingfehler.</span><span class="sxs-lookup"><span data-stu-id="5be35-231">Thrown if there is a messaging error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="5be35-232">die zu sendende Meldung.</span><span class="sxs-lookup"><span data-stu-id="5be35-232">The message to send.</span></span></param>
        <summary><span data-ttu-id="5be35-233">Sendet asynchron eine Meldung mit der <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span><span class="sxs-lookup"><span data-stu-id="5be35-233">Asynchronously sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</span></span></summary>
        <returns><span data-ttu-id="5be35-234">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5be35-234">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="topicClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="5be35-235">Der zu sendenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="5be35-235">The messages to send.</span></span></param>
        <summary><span data-ttu-id="5be35-236">Sendet eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="5be35-236">Sends a set of brokered messages (for batch processing).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="5be35-237">Der zu sendenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="5be35-237">The messages to send.</span></span></param>
        <summary><span data-ttu-id="5be35-238">Sendet asynchron eine Reihe von brokernachrichten (für die Batchverarbeitung).</span><span class="sxs-lookup"><span data-stu-id="5be35-238">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="5be35-239">Das asynchrone Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5be35-239">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>