<Type Name="SessionClient" FullName="Microsoft.Azure.ServiceBus.SessionClient">
  <TypeSignature Language="C#" Value="public sealed class SessionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionClient&#xA;Inherits ClientEntity&#xA;Implements ISessionClient" />
  <TypeSignature Language="F#" Value="type SessionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISessionClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.ISessionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="5d342-101">Ein Client für die Sitzung kann verwendet werden, um Sitzungsobjekte übernehmen, die Interaktion mit der alle Nachrichten mit der gleichen SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d342-101">A session client can be used to accept session objects which can be used to interact with all messages with the same sessionId.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="5d342-102">Sie können eine beliebige Sitzung oder einer bestimmten Sitzung übernehmen (identifiziert durch <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> mithilfe eines Sitzungsclients.</span><span class="sxs-lookup"><span data-stu-id="5d342-102">You can accept any session or a given session (identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> using a session client.</span></span>
             <span data-ttu-id="5d342-103">Nachdem Sie eine Sitzung akzeptiert haben, können Sie es als ein <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> der nur Nachrichten, die mit derselben Sitzungs-Id empfängt. Finden Sie unter <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> für die Verwendung von Sitzungsobjekt.</span><span class="sxs-lookup"><span data-stu-id="5d342-103">Once you accept a session, you can use it as a <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> which receives only messages having the same session id. See <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> for usage of session object.</span></span>
             <span data-ttu-id="5d342-104">Dabei wird AMQP-Protokolls, um mit dem Dienst kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="5d342-104">This uses AMQP protocol to communicate with the service.</span></span>
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <example>
             <span data-ttu-id="5d342-105">So erstellen eine neue SessionClient</span><span class="sxs-lookup"><span data-stu-id="5d342-105">To create a new SessionClient</span></span>
             <code>
             ISessionClient sessionClient = new SessionClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="5d342-106">Ein Sitzungsobjekt für einen bestimmten SessionId empfangen</span><span class="sxs-lookup"><span data-stu-id="5d342-106">To receive a session object for a given sessionId</span></span>
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
            
             <span data-ttu-id="5d342-107">Eine beliebige Sitzung empfangen.</span><span class="sxs-lookup"><span data-stu-id="5d342-107">To receive any session</span></span>
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder"><span data-ttu-id="5d342-108">Die <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> Verbindungs-Entitätsdetails müssen.</span><span class="sxs-lookup"><span data-stu-id="5d342-108">The <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having entity level connection details.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="5d342-109">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-109">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="5d342-110">Der Standardwert ist PeekLock-Modus.</span><span class="sxs-lookup"><span data-stu-id="5d342-110">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="5d342-111">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-111">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with ServiceBus.</span></span> <span data-ttu-id="5d342-112">Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="5d342-112">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="5d342-113">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> , die die Obergrenze von Nachrichten, die das Sitzungsobjekt wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt.</span><span class="sxs-lookup"><span data-stu-id="5d342-113">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> that specifies the upper limit of messages the session object will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="5d342-114">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="5d342-114">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-115">Erstellt eine neue SessionClient aus einem<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span><span class="sxs-lookup"><span data-stu-id="5d342-115">Creates a new SessionClient from a <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span></span></summary>
        <remarks><span data-ttu-id="5d342-116">Erstellt eine neue Verbindung mit der Entität, die für alle Sitzungen Objekte verwendet wird mit diesem Client akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="5d342-116">Creates a new connection to the entity, which is used for all the sessions objects accepted using this client.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="5d342-117">Namespace-Verbindungszeichenfolge für die Kommunikation mit Service Bus verwendet.</span><span class="sxs-lookup"><span data-stu-id="5d342-117">Namespace connection string used to communicate with Service Bus.</span></span> <span data-ttu-id="5d342-118">Darf keine Entitätsdetails enthalten.</span><span class="sxs-lookup"><span data-stu-id="5d342-118">Must not contain entity details.</span></span></param>
        <param name="entityPath"><span data-ttu-id="5d342-119">Der Pfad der Entität für dieser Empfänger.</span><span class="sxs-lookup"><span data-stu-id="5d342-119">The path of the entity for this receiver.</span></span> <span data-ttu-id="5d342-120">Für Warteschlangen dies den Namen, aber für Abonnements wird dies den vollständigen Pfad sein.</span><span class="sxs-lookup"><span data-stu-id="5d342-120">For Queues this will be the name, but for Subscriptions this will be the full path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="5d342-121">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-121">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="5d342-122">Der Standardwert ist PeekLock-Modus.</span><span class="sxs-lookup"><span data-stu-id="5d342-122">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="5d342-123">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-123">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with ServiceBus.</span></span> <span data-ttu-id="5d342-124">Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="5d342-124">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="5d342-125">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> , die die Obergrenze von Nachrichten, die das Sitzungsobjekt wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt.</span><span class="sxs-lookup"><span data-stu-id="5d342-125">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> that specifies the upper limit of messages the session object will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="5d342-126">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="5d342-126">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-127">Erstellt eine neue SessionClient aus einer angegebenen Zeichenfolge und Entität Verbindungspfad an.</span><span class="sxs-lookup"><span data-stu-id="5d342-127">Creates a new SessionClient from a specified connection string and entity path.</span></span>
            </summary>
        <remarks><span data-ttu-id="5d342-128">Erstellt eine neue Verbindung mit der Entität, die für alle Sitzungen Objekte verwendet wird mit diesem Client akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="5d342-128">Creates a new connection to the entity, which is used for all the sessions objects accepted using this client.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d342-129">Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d342-129">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="5d342-130">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="5d342-130">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="5d342-131">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="5d342-131">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="5d342-132">Die SessionId in allen Nachrichten vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d342-132">The sessionId present in all its messages.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-133">Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d342-133">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="5d342-134">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="5d342-134">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="5d342-135">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="5d342-135">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="5d342-136">Zeitspanne für den Aufruf warten soll, um die nächste Sitzung abzurufen.</span><span class="sxs-lookup"><span data-stu-id="5d342-136">Amount of time for which the call should wait to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-137">Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d342-137">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="5d342-138">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="5d342-138">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="5d342-139">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="5d342-139">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;AcceptMessageSessionAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="5d342-140">Die SessionId in allen Nachrichten vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="5d342-140">The sessionId present in all its messages.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="5d342-141">Zeitspanne für den Aufruf warten soll, um die nächste Sitzung abzurufen.</span><span class="sxs-lookup"><span data-stu-id="5d342-141">Amount of time for which the call should wait to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-142">Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5d342-142">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="5d342-143">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="5d342-143">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="5d342-144">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="5d342-144">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d342-145">Ruft den Pfad der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="5d342-145">Gets the path of the entity.</span></span> <span data-ttu-id="5d342-146">Dies ist entweder der Name der Warteschlange oder den vollständigen Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="5d342-146">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="sessionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;OnClosingAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d342-147">Dauer, die nach der einzelnen Vorgänge Timeout erzwungen werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-147">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d342-148">Ruft eine Liste der derzeit registrierten Plug-Ins ab.</span><span class="sxs-lookup"><span data-stu-id="5d342-148">Gets a list of currently registered plugins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="sessionClient.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin"><span data-ttu-id="5d342-149">Die zu registrierende <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span><span class="sxs-lookup"><span data-stu-id="5d342-149">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-150">Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit dieser Empfänger verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5d342-150">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="sessionClient.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName"><span data-ttu-id="5d342-151">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> des Plug-Ins zum aufgehoben werden.</span><span class="sxs-lookup"><span data-stu-id="5d342-151">The <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> of the plugin to be unregistered.</span></span></param>
        <summary>
            <span data-ttu-id="5d342-152">Hebt die Registrierung einer <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span><span class="sxs-lookup"><span data-stu-id="5d342-152">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>