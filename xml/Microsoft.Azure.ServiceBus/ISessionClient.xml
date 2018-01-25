<Type Name="ISessionClient" FullName="Microsoft.Azure.ServiceBus.ISessionClient">
  <TypeSignature Language="C#" Value="public interface ISessionClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISessionClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISessionClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type ISessionClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IClientEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="714d3-101">Beschreibt einen Client für die Sitzung an.</span><span class="sxs-lookup"><span data-stu-id="714d3-101">Describes a Session client.</span></span> <span data-ttu-id="714d3-102">Ein Client für die Sitzung kann verwendet werden, um Sitzungsobjekte übernehmen, die Interaktion mit der alle Nachrichten mit der gleichen SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="714d3-102">A session client can be used to accept session objects which can be used to interact with all messages with the same sessionId.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="714d3-103">Sie können eine beliebige Sitzung oder einer bestimmten Sitzung übernehmen (identifiziert durch <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> mithilfe eines Sitzungsclients.</span><span class="sxs-lookup"><span data-stu-id="714d3-103">You can accept any session or a given session (identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> using a session client.</span></span>
             <span data-ttu-id="714d3-104">Nachdem Sie eine Sitzung akzeptiert haben, können Sie es als ein <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> der nur Nachrichten, die mit derselben Sitzungs-Id empfängt. Finden Sie unter <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> für die Verwendung von Sitzungsobjekt.</span><span class="sxs-lookup"><span data-stu-id="714d3-104">Once you accept a session, you can use it as a <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> which receives only messages having the same session id. See <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> for usage of session object.</span></span>
             <span data-ttu-id="714d3-105"><example>So erstellen eine neue SessionClient</span><span class="sxs-lookup"><span data-stu-id="714d3-105"><example> To create a new SessionClient</span></span>
             <code>
             ISessionClient sessionClient = new SessionClient(
             namespaceConnectionString,
             queueName,
                 ReceiveMode.PeekLock);
                 </code>
                 
             <span data-ttu-id="714d3-106">Ein Sitzungsobjekt für einen bestimmten SessionId empfangen</span><span class="sxs-lookup"><span data-stu-id="714d3-106">To receive a session object for a given sessionId</span></span>
            <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
             
             <span data-ttu-id="714d3-107">Eine beliebige Sitzung empfangen.</span><span class="sxs-lookup"><span data-stu-id="714d3-107">To receive any session</span></span>
            <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SessionClient" />
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="714d3-108">Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="714d3-108">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="714d3-109">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="714d3-109">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="714d3-110">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="714d3-110">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
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
        <param name="sessionId"><span data-ttu-id="714d3-111">Die SessionId in allen Nachrichten vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="714d3-111">The sessionId present in all its messages.</span></span></param>
        <summary>
            <span data-ttu-id="714d3-112">Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="714d3-112">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="714d3-113">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="714d3-113">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="714d3-114">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="714d3-114">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
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
        <param name="serverWaitTime"><span data-ttu-id="714d3-115">Zeitdauer für die der Aufruf für warten soll, um die nächste Sitzung abzurufen.</span><span class="sxs-lookup"><span data-stu-id="714d3-115">Amount of time for which the call should wait for to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="714d3-116">Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="714d3-116">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="714d3-117">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="714d3-117">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="714d3-118">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="714d3-118">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
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
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="714d3-119">Die SessionId in allen Nachrichten vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="714d3-119">The sessionId present in all its messages.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="714d3-120">Zeitdauer für die der Aufruf für warten soll, um die nächste Sitzung abzurufen.</span><span class="sxs-lookup"><span data-stu-id="714d3-120">Amount of time for which the call should wait for to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="714d3-121">Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="714d3-121">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="714d3-122">Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="714d3-122">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="714d3-123">Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</span><span class="sxs-lookup"><span data-stu-id="714d3-123">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="714d3-124">Ruft den Pfad der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="714d3-124">Gets the path of the entity.</span></span> <span data-ttu-id="714d3-125">Dies ist entweder der Name der Warteschlange oder den vollständigen Pfad des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="714d3-125">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>