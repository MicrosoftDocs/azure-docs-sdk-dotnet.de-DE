<Type Name="ISubscriptionClient" FullName="Microsoft.Azure.ServiceBus.ISubscriptionClient">
  <TypeSignature Language="C#" Value="public interface ISubscriptionClient : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscriptionClient implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscriptionClient&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type ISubscriptionClient = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IReceiverClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="b7d4f-101">SubscriptionClient kann für alle grundlegenden Interaktionen mit einem Service Bus-Abonnement verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-101">SubscriptionClient can be used for all basic interactions with a Service Bus Subscription.</span></span>
             </summary>
    <remarks><span data-ttu-id="b7d4f-102">Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> für erweiterten Satz von Funktionen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <example>
             <span data-ttu-id="b7d4f-103">Erstellen Sie eine neue SubscriptionClient</span><span class="sxs-lookup"><span data-stu-id="b7d4f-103">Create a new SubscriptionClient</span></span>
             <code>
             ISubscriptionClient subscriptionClient = new SubscriptionClient(
                 namespaceConnectionString,
                 topicName,
                 subscriptionName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="b7d4f-104">Registrieren Sie einen Message-Handler, die aufgerufen wird, jedes Mal, wenn eine Nachricht empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-104">Register a message handler which will be invoked every time a message is received.</span></span>
             <code>
             subscriptionClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the subscriptionClient is opened in ReceiveMode.PeekLock mode.
                        await subscriptionClient.CompleteAsync(message.SystemProperties.LockToken);
                    },
                    async (exceptionEvent) =&gt;
                    {
                        // Process the exception
                        Console.WriteLine("Exception = " + exceptionEvent.Exception);
                        return Task.CompletedTask;
                    });
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="b7d4f-105">Eine Beschreibung der Regel, die die Regel hinzuzufügende bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-105">The rule description that provides the rule to add.</span></span></param>
        <summary>
            <span data-ttu-id="b7d4f-106">Fügt eine Regel auf das aktuelle Abonnement zum Filtern der Nachrichten im Thema zum Abonnement erreicht.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-106">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="b7d4f-107">Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-107">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b7d4f-108">Sie können Regeln für das Abonnement hinzufügen, die Filter entscheiden wird, welche Nachrichten aus dem Thema kann das Abonnement erreichen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-108">You can add rules to the subscription that will decide filter which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="b7d4f-109">Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-109">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="b7d4f-110">Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-110">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="b7d4f-111">Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-111">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="b7d4f-112">d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-112">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">To be added.</param>
        <param name="filter"><span data-ttu-id="b7d4f-113">Der Filterausdruck für den Nachrichten berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-113">The filter expression against which messages will be matched.</span></span></param>
        <summary>
            <span data-ttu-id="b7d4f-114">Fügt eine Regel auf das aktuelle Abonnement zum Filtern der Nachrichten im Thema zum Abonnement erreicht.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-114">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="b7d4f-115">Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-115">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="b7d4f-116">Sie können Regeln für das Abonnement hinzufügen, die Filter entscheiden wird, welche Nachrichten aus dem Thema kann das Abonnement erreichen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-116">You can add rules to the subscription that will decide filter which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="b7d4f-117">Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-117">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="b7d4f-118">Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-118">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="b7d4f-119">Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-119">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="b7d4f-120">d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-120">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="iSubscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b7d4f-121">Rufen Sie aller Regeln, die dem Abonnement zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-121">Get all rules associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="b7d4f-122">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-122">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="b7d4f-123"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="b7d4f-123"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="sessionHandlerOptions"><span data-ttu-id="b7d4f-124">Optionen zum Konfigurieren der Einstellungen der Datapump Sitzung verwendet.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-124">Options used to configure the settings of the session pump.</span></span></param>
        <summary>
            <span data-ttu-id="b7d4f-125">Empfangen Sie sitzungsnachrichten fortlaufend aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-125">Receive session messages continuously from the subscription.</span></span> <span data-ttu-id="b7d4f-126">Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-126">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="b7d4f-127">Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-127">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks><span data-ttu-id="b7d4f-128">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-128">Enable prefetch to speed up the receive rate.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="b7d4f-129">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-129">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="b7d4f-130"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="b7d4f-130"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="b7d4f-131">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-131">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="b7d4f-132"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-132"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="b7d4f-133">Empfangen Sie sitzungsnachrichten fortlaufend aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-133">Receive session messages continuously from the subscription.</span></span> <span data-ttu-id="b7d4f-134">Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-134">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="b7d4f-135">Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-135">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks><span data-ttu-id="b7d4f-136">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-136">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="b7d4f-137">Verwendung <see cref="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-137">Use <see cref="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="b7d4f-138">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-138">The name of the rule.</span></span></param>
        <summary>
            <span data-ttu-id="b7d4f-139">Entfernt die Regel für das Abonnement identifizierten <paramref name="ruleName" />.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-139">Removes the rule on the subscription identified by <paramref name="ruleName" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b7d4f-140">Eine Taskinstanz, die den asynchronen Entfernungsvorgang für die Regel darstellt.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-140">A task instance that represents the asynchronous remove rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7d4f-141">Ruft den Namen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-141">Gets the name of subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7d4f-142">Ruft den Pfad des Themas für dieses Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="b7d4f-142">Gets the path of the topic, for this subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>