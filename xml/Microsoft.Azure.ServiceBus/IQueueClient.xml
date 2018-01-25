<Type Name="IQueueClient" FullName="Microsoft.Azure.ServiceBus.IQueueClient">
  <TypeSignature Language="C#" Value="public interface IQueueClient : Microsoft.Azure.ServiceBus.Core.IReceiverClient, Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueueClient implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueueClient&#xA;Implements IReceiverClient, ISenderClient" />
  <TypeSignature Language="F#" Value="type IQueueClient = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity&#xA;    interface ISenderClient" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.ISenderClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="753b6-101">QueueClient kann für alle grundlegenden Interaktionen mit Service Bus-Warteschlange verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="753b6-101">QueueClient can be used for all basic interactions with a Service Bus Queue.</span></span>
             </summary>
    <remarks><span data-ttu-id="753b6-102">Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" /> oder <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> für erweiterten Satz von Funktionen.</span><span class="sxs-lookup"><span data-stu-id="753b6-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" /> or <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <example>
             <span data-ttu-id="753b6-103">Erstellen Sie eine neue QueueClient</span><span class="sxs-lookup"><span data-stu-id="753b6-103">Create a new QueueClient</span></span>
             <code>
             IQueueClient queueClient = new QueueClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="753b6-104">Senden einer Nachricht an die Warteschlange:</span><span class="sxs-lookup"><span data-stu-id="753b6-104">Send a message to the queue:</span></span>
             <code>
             byte[] data = GetData();
             await queueClient.SendAsync(data);
             </code>
            
             <span data-ttu-id="753b6-105">Registrieren Sie einen Message-Handler, die aufgerufen wird, jedes Mal, wenn eine Nachricht empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="753b6-105">Register a message handler which will be invoked every time a message is received.</span></span>
             <code>
             queueClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the queueClient is opened in ReceiveMode.PeekLock mode.
                        await queueClient.CompleteAsync(message.SystemProperties.LockToken);
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
    <Member MemberName="QueueName">
      <MemberSignature Language="C#" Value="public string QueueName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueueName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IQueueClient.QueueName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueName As String" />
      <MemberSignature Language="F#" Value="member this.QueueName : string" Usage="Microsoft.Azure.ServiceBus.IQueueClient.QueueName" />
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
            <span data-ttu-id="753b6-106">Ruft den Namen der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="753b6-106">Gets the name of the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="iQueueClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
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
        <param name="handler"><span data-ttu-id="753b6-107">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="753b6-107">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="753b6-108"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="753b6-108"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="sessionHandlerOptions"><span data-ttu-id="753b6-109">Optionen zum Konfigurieren der Einstellungen der Datapump Sitzung verwendet.</span><span class="sxs-lookup"><span data-stu-id="753b6-109">Options used to configure the settings of the session pump.</span></span></param>
        <summary>
            <span data-ttu-id="753b6-110">Empfangen Sie sitzungsnachrichten fortlaufend aus der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="753b6-110">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="753b6-111">Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="753b6-111">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="753b6-112">Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch den warteschlangenclient auf erwartet.</span><span class="sxs-lookup"><span data-stu-id="753b6-112">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the queue client.</span></span>
            </summary>
        <remarks><span data-ttu-id="753b6-113">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="753b6-113">Enable prefetch to speed up the receive rate.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iQueueClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
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
        <param name="handler"><span data-ttu-id="753b6-114">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="753b6-114">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="753b6-115"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="753b6-115"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="753b6-116">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="753b6-116">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="753b6-117"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="753b6-117"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="753b6-118">Empfangen Sie sitzungsnachrichten fortlaufend aus der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="753b6-118">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="753b6-119">Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="753b6-119">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="753b6-120">Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch den warteschlangenclient auf erwartet.</span><span class="sxs-lookup"><span data-stu-id="753b6-120">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the queue client.</span></span>
            </summary>
        <remarks><span data-ttu-id="753b6-121">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="753b6-121">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="753b6-122">Verwendung <see cref="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</span><span class="sxs-lookup"><span data-stu-id="753b6-122">Use <see cref="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>