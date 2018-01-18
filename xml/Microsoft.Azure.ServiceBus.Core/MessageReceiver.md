<Type Name="MessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.MessageReceiver">
  <TypeSignature Language="C#" Value="public class MessageReceiver : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageReceiver extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageReceiver&#xA;Inherits ClientEntity&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="31d13-101">Die MessageReceiver kann zum Empfangen von Nachrichten aus Warteschlangen und Abonnements, und bestätigen sie verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-101">The MessageReceiver can be used to receive messages from Queues and Subscriptions and acknowledge them.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="31d13-102">Die MessageReceiver bietet erweiterte Funktionalität, die nicht in der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> oder <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-102">The MessageReceiver provides advanced functionality that is not found in the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> or <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span></span> <span data-ttu-id="31d13-103">Z. B. <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, dem können Sie zum Empfangen von Nachrichten bei Bedarf, erfordert jedoch auch manuell mithilfe von Sperren erneuern <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-103">For instance, <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, which allows you to receive messages on demand, but also requires you to manually renew locks using <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span></span>
             <span data-ttu-id="31d13-104">AMQP-Protokolls verwendet für die Kommunikation mit dem Dienst.</span><span class="sxs-lookup"><span data-stu-id="31d13-104">It uses AMQP protocol to communicate with service.</span></span>
             </remarks>
    <example>
             <span data-ttu-id="31d13-105">Erstellen Sie eine neue MessageReceiver zum Empfangen einer Nachricht aus einem Abonnement</span><span class="sxs-lookup"><span data-stu-id="31d13-105">Create a new MessageReceiver to receive a message from a Subscription</span></span>
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="31d13-106">Eine Meldung aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="31d13-106">Receive a message from the Subscription.</span></span>
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
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
        <param name="connectionStringBuilder"><span data-ttu-id="31d13-107">Die <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> Verbindungs-Entitätsdetails müssen.</span><span class="sxs-lookup"><span data-stu-id="31d13-107">The <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having entity level connection details.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="31d13-108">Die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-108">The <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="31d13-109">Der Standardwert ist PeekLock-Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-109">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="31d13-110">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-110">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="31d13-111">Wird standardmäßig auf <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /> festgelegt.</span><span class="sxs-lookup"><span data-stu-id="31d13-111">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" />.</span></span></param>
        <param name="prefetchCount"><span data-ttu-id="31d13-112">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> , die die Obergrenze von Nachrichten, die dieser Empfänger wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt.</span><span class="sxs-lookup"><span data-stu-id="31d13-112">The <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> that specifies the upper limit of messages this receiver will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="31d13-113">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="31d13-113">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-114">Erstellt eine neue MessageReceiver aus einem <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-114">Creates a new MessageReceiver from a <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks><span data-ttu-id="31d13-115">Erstellt eine neue Verbindung mit der Entität, die während des ersten Vorgangs geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="31d13-115">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
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
        <param name="connectionString"><span data-ttu-id="31d13-116">Namespace-Verbindungszeichenfolge für die Kommunikation mit Service Bus verwendet.</span><span class="sxs-lookup"><span data-stu-id="31d13-116">Namespace connection string used to communicate with Service Bus.</span></span> <span data-ttu-id="31d13-117">Darf keine Entitätsdetails enthalten.</span><span class="sxs-lookup"><span data-stu-id="31d13-117">Must not contain Entity details.</span></span></param>
        <param name="entityPath"><span data-ttu-id="31d13-118">Der Pfad der Entität für dieser Empfänger.</span><span class="sxs-lookup"><span data-stu-id="31d13-118">The path of the entity for this receiver.</span></span> <span data-ttu-id="31d13-119">Für Warteschlangen dies den Namen, aber für Abonnements wird dies den Pfad sein.</span><span class="sxs-lookup"><span data-stu-id="31d13-119">For Queues this will be the name, but for Subscriptions this will be the path.</span></span>
            <span data-ttu-id="31d13-120">Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />, um diesen Pfad zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="31d13-120">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />, to help create this path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="31d13-121">Die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-121">The <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="31d13-122">Der Standardwert ist PeekLock-Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-122">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="31d13-123">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-123">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="31d13-124">Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="31d13-124">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="31d13-125">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> , die die Obergrenze von Nachrichten, die dieser Empfänger wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt.</span><span class="sxs-lookup"><span data-stu-id="31d13-125">The <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> that specifies the upper limit of messages this receiver will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="31d13-126">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="31d13-126">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-127">Erstellt eine neue MessageReceiver aus einer angegebenen Zeichenfolge und Entität Verbindungspfad an.</span><span class="sxs-lookup"><span data-stu-id="31d13-127">Creates a new MessageReceiver from a specified connection string and entity path.</span></span>
            </summary>
        <remarks><span data-ttu-id="31d13-128">Erstellt eine neue Verbindung mit der Entität, die während des ersten Vorgangs geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="31d13-128">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;AbandonAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-129">Das Sperrtoken der entsprechenden Nachricht zu verwerfen.</span><span class="sxs-lookup"><span data-stu-id="31d13-129">The lock token of the corresponding message to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="31d13-130">Die Eigenschaften der Nachricht zu ändern, während die Nachricht aufzugeben.</span><span class="sxs-lookup"><span data-stu-id="31d13-130">The properties of the message to modify while abandoning the message.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-131">Verwirft eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einem Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="31d13-131">Abandons a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a lock token.</span></span> <span data-ttu-id="31d13-132">Dadurch wird die Nachricht erneut für die Verarbeitung zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="31d13-132">This will make the message available again for processing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="31d13-133">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-133">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-134">Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-134">Abandoning a message will increase the delivery count on the message.</span></span>
            <span data-ttu-id="31d13-135">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-135">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;CompleteAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="31d13-136">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> mit den Token sperren die entsprechenden Nachrichten abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="31d13-136">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the lock tokens of the corresponding messages to complete.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-137">Schließt eine Reihe von <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einer Liste von Token der Sperre.</span><span class="sxs-lookup"><span data-stu-id="31d13-137">Completes a series of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a list of lock tokens.</span></span> <span data-ttu-id="31d13-138">Hierdurch wird die Nachricht vom Dienst gelöscht.</span><span class="sxs-lookup"><span data-stu-id="31d13-138">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-139">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-139">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-140">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-140">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-141">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-141">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)</InterfaceMember>
      </Implements>
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-142">Das Sperrtoken der entsprechenden Nachricht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="31d13-142">The lock token of the corresponding message to complete.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-143">Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="31d13-143">Completes a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using its lock token.</span></span> <span data-ttu-id="31d13-144">Hierdurch wird die Nachricht vom Dienst gelöscht.</span><span class="sxs-lookup"><span data-stu-id="31d13-144">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-145">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-145">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-146">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-146">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-147">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-147">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-148">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="31d13-148">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="31d13-149">Die Eigenschaften der Nachricht zu ändern, wenn zum untergeordneten Warteschlange verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-149">The properties of the message to modify while moving to sub-queue.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-150">Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.</span><span class="sxs-lookup"><span data-stu-id="31d13-150">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="31d13-151">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-151">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-152">Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.</span><span class="sxs-lookup"><span data-stu-id="31d13-152">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="31d13-153">Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.</span><span class="sxs-lookup"><span data-stu-id="31d13-153">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="31d13-154">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-154">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-155">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="31d13-155">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="31d13-156">Der Grund für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-156">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="31d13-157">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-157">The error description for deadlettering the message.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-158">Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.</span><span class="sxs-lookup"><span data-stu-id="31d13-158">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="31d13-159">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-159">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-160">Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.</span><span class="sxs-lookup"><span data-stu-id="31d13-160">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="31d13-161">Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.</span><span class="sxs-lookup"><span data-stu-id="31d13-161">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="31d13-162">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-162">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeferAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-163">Das Sperrtoken des der <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-163">The lock token of the <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="31d13-164">Die Eigenschaften der Nachricht zu ändern, während die Nachricht verzögern.</span><span class="sxs-lookup"><span data-stu-id="31d13-164">The properties of the message to modify while deferring the message.</span></span></param>
        <summary><span data-ttu-id="31d13-165">Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</span><span class="sxs-lookup"><span data-stu-id="31d13-165">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="31d13-166">Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-166">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="31d13-167">Um diese Meldung erneut in der Zukunft Sie benötigen zum Speichern der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> und empfangen mit <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-167">In order to receive this message again in the future, you will need to save the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> and receive it using <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span></span>
            <span data-ttu-id="31d13-168">Verzögern von Nachrichten wirkt sich nicht der Nachricht Ablauf, was bedeutet, dass die verzögerte Nachrichten weiterhin ablaufen können.</span><span class="sxs-lookup"><span data-stu-id="31d13-168">Deferring messages does not impact message's expiration, meaning that deferred messages can still expire.</span></span>
            <span data-ttu-id="31d13-169">Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.</span><span class="sxs-lookup"><span data-stu-id="31d13-169">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31d13-170">Ruft die Sequenznummer der letzten eingesehenen Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-170">Gets the sequence number of the last peeked message.</span></span></summary>
        <value><span data-ttu-id="31d13-171">Die Sequenznummer der letzten eingesehenen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-171">The sequence number of the last peeked message.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="OnAbandonAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnAbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnAbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnAbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnAbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnAbandonAsync (lockToken, propertiesToModify)" />
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
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnClosingAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns><span data-ttu-id="31d13-172">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-172">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCompleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnCompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnCompleteAsync lockTokens" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"></param>
        <summary />
        <returns><span data-ttu-id="31d13-173">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-173">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetterAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null, string deadLetterReason = null, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null, Optional deadLetterReason As String = null, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeadLetterAsync (lockToken, propertiesToModify, deadLetterReason, deadLetterErrorDescription)" />
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
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeferAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeferAsync (lockToken, propertiesToModify)" />
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
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageHandler">
      <MemberSignature Language="C#" Value="protected virtual void OnMessageHandler (Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnMessageHandler(class Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnMessageHandler(Microsoft.Azure.ServiceBus.MessageHandlerOptions,System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnMessageHandler (registerHandlerOptions As MessageHandlerOptions, callback As Func(Of Message, CancellationToken, Task))" />
      <MemberSignature Language="F#" Value="abstract member OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.OnMessageHandler (registerHandlerOptions, callback)" />
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
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="registerHandlerOptions">To be added.</param>
        <param name="callback">To be added.</param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeekAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync (long fromSequenceNumber, int messageCount = 1);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnPeekAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnPeekAsync (fromSequenceNumber As Long, Optional messageCount As Integer = 1) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnPeekAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnPeekAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns><span data-ttu-id="31d13-174">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-174">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveAsync (maxMessageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveAsync (maxMessageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="serverWaitTime"></param>
        <summary />
        <returns><span data-ttu-id="31d13-175">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-175">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync (long[] sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync(int64[] sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveDeferredMessageAsync(System.Int64[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveDeferredMessageAsync (sequenceNumbers As Long()) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveDeferredMessageAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Int64[]" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLockAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;DateTime&gt; OnRenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; OnRenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnRenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnRenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.OnRenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnRenewLockAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns><span data-ttu-id="31d13-176">Der Asynchronour-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-176">The asynchronour operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
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
            <span data-ttu-id="31d13-177">Dauer, die nach der einzelnen Vorgänge Timeout erzwungen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-177">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public virtual string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path</InterfaceMember>
      </Implements>
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
        <summary><span data-ttu-id="31d13-178">Der Pfad der Entität für dieser Empfänger.</span><span class="sxs-lookup"><span data-stu-id="31d13-178">The path of the entity for this receiver.</span></span> <span data-ttu-id="31d13-179">Für Warteschlangen dies den Namen, aber für Abonnements wird dies den Pfad sein.</span><span class="sxs-lookup"><span data-stu-id="31d13-179">For Queues this will be the name, but for Subscriptions this will be the path.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31d13-180">Ruft die nächste active Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-180">Fetches the next active message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-181">Die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="31d13-181">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="31d13-182">Gibt null zurück, wenn nichts einsehen.</span><span class="sxs-lookup"><span data-stu-id="31d13-182">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-183">Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="31d13-183">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="31d13-184">Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-184">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="31d13-185">Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.</span><span class="sxs-lookup"><span data-stu-id="31d13-185">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="31d13-186">Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)</span><span class="sxs-lookup"><span data-stu-id="31d13-186">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="31d13-187">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="31d13-187">The number of messages.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-188">Ruft den nächsten Batch aktiver Nachrichten ohne Ändern des Zustands der Empfänger oder die Quelle der Meldung ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-188">Fetches the next batch of active messages without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-189">Liste der <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="31d13-189">List of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="31d13-190">Gibt null zurück, wenn nichts einsehen.</span><span class="sxs-lookup"><span data-stu-id="31d13-190">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-191">Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="31d13-191">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="31d13-192">Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-192">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="31d13-193">Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.</span><span class="sxs-lookup"><span data-stu-id="31d13-193">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="31d13-194">Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)</span><span class="sxs-lookup"><span data-stu-id="31d13-194">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="31d13-195">Die Sequenznummer ab dem die Nachricht zu lesen.</span><span class="sxs-lookup"><span data-stu-id="31d13-195">The sequence number from where to read the message.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-196">Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.</span><span class="sxs-lookup"><span data-stu-id="31d13-196">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-197">Den asynchronen Vorgang, die gibt die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="31d13-197">The asynchronous operation that returns the <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="31d13-198">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-198">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="31d13-199">Die Anzahl der abzurufenden Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="31d13-199">The number of messages to retrieve.</span></span></param>
        <summary><span data-ttu-id="31d13-200">Liest einen Nachrichtenbatch an.</span><span class="sxs-lookup"><span data-stu-id="31d13-200">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="31d13-201">Ein Nachrichtenbatch eingesehen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-201">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31d13-202">Prefetch beschleunigt den Nachrichtenfluss durch ins Leben gerufen, eine Nachricht, die für den lokalen Abruf unmittelbar verfügbar sein, wenn und vor der Anwendung, für eine aufgefordert Verwendung empfangen.</span><span class="sxs-lookup"><span data-stu-id="31d13-202">Prefetch speeds up the message flow by aiming to have a message readily available for local retrieval when and before the application asks for one using Receive.</span></span>
            <span data-ttu-id="31d13-203">Einen Wert ungleich Null festlegen, vorab PrefetchCount Anzahl der Nachrichten abruft.</span><span class="sxs-lookup"><span data-stu-id="31d13-203">Setting a non-zero value prefetches PrefetchCount number of messages.</span></span>
            <span data-ttu-id="31d13-204">Festlegen des Werts auf 0 (null) wird Prefetch deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="31d13-204">Setting the value to zero turns prefetch off.</span></span>
            <span data-ttu-id="31d13-205">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="31d13-205">Defaults to 0.</span></span>
            </summary>
        <value><span data-ttu-id="31d13-206">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="31d13-206">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="31d13-207">Wenn Sie Prefetch aktiviert ist, wird der Empfänger – abrufen Nachrichten mehr anzeigt, maximal der Größe PrefetchCount als was die Anwendung sofort anfordert.</span><span class="sxs-lookup"><span data-stu-id="31d13-207">When Prefetch is enabled, the receiver will quietly acquire more messages, up to the PrefetchCount limit, than what the application immediately asks for.</span></span> <span data-ttu-id="31d13-208">Ein einzelner Aufruf der ursprünglichen Receive/ReceiveAsync wird daher eine Nachricht abrufen, für sofortigen Verbrauch, die so bald wie verfügbaren zurückgegeben werden, und der Client zum Abrufen von weiterer Nachrichten zum Ausfüllen des Prefetch-Puffers im Hintergrund fortgesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-208">A single initial Receive/ReceiveAsync call will therefore acquire a message for immediate consumption that will be returned as soon as available, and the client will proceed to acquire further messages to fill the prefetch buffer in the background.</span></span>
            </para>
          <para>
            <span data-ttu-id="31d13-209">Während der Nachrichten im Puffer Prefetch verfügbar sind, alle nachfolgenden ReceiveAsync-Aufrufe werden sofort aus dem Puffer erfüllt, und wie Speicherplatz verfügbar ist, wird der Puffer im Hintergrund aufgefüllt. Keine Nachrichten für die Übermittlung verfügbar sind, wird der Empfangsvorgang und dann warten, oder blockieren wie erwartet ausgleichen den Puffer.</span><span class="sxs-lookup"><span data-stu-id="31d13-209">While messages are available in the prefetch buffer, any subsequent ReceiveAsync calls will be immediately satisfied from the buffer, and the buffer is replenished in the background as space becomes available.If there are no messages available for delivery, the receive operation will drain the buffer and then wait or block as expected.</span></span>
            </para>
          <para><span data-ttu-id="31d13-210">Prefetch funktioniert auch gleichwertig mit der <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> APIs.</span><span class="sxs-lookup"><span data-stu-id="31d13-210">Prefetch also works equivalently with the <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> APIs.</span></span></para>
          <para><span data-ttu-id="31d13-211">Updates für diesen Wert wirksam, auf die nächste empfangsaufruf an den Dienst.</span><span class="sxs-lookup"><span data-stu-id="31d13-211">Updates to this value take effect on the next receive call to the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31d13-212">Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-212">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-213">Die empfangene Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-213">The message received.</span></span> <span data-ttu-id="31d13-214">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-214">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="31d13-215">Timeout nach der Dauer des Vorgangs<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="31d13-215">Operation will time out after duration of <see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="31d13-216">Die maximale Anzahl von Nachrichten, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-216">The maximum number of messages that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-217">Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-217">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-218">Liste der Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="31d13-218">List of messages received.</span></span> <span data-ttu-id="31d13-219">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-219">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="31d13-220">Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</span><span class="sxs-lookup"><span data-stu-id="31d13-220">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="31d13-221">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="31d13-221">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-222">Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-222">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-223">Die empfangene Nachricht.</span><span class="sxs-lookup"><span data-stu-id="31d13-223">The message received.</span></span> <span data-ttu-id="31d13-224">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-224">Returns null if no message is found.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-225">Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss).</span><span class="sxs-lookup"><span data-stu-id="31d13-225">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="31d13-226">Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-226">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="31d13-227">Die maximale Anzahl von Nachrichten, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-227">The maximum number of messages that will be received.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="31d13-228">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="31d13-228">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-229">Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="31d13-229">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-230">Liste der Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="31d13-230">List of messages received.</span></span> <span data-ttu-id="31d13-231">Gibt null zurück, wenn keine Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-231">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="31d13-232">Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</span><span class="sxs-lookup"><span data-stu-id="31d13-232">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span>
            <span data-ttu-id="31d13-233">Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss).</span><span class="sxs-lookup"><span data-stu-id="31d13-233">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="31d13-234">Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-234">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="31d13-235">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , enthält die Sequenznummern empfangen.</span><span class="sxs-lookup"><span data-stu-id="31d13-235">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the sequence numbers to receive.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-236">Empfängt eine <see cref="T:System.Collections.Generic.IList`1" /> verzögerte Nachrichten identifizierten <paramref name="sequenceNumbers" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-236">Receives a <see cref="T:System.Collections.Generic.IList`1" /> of deferred messages identified by <paramref name="sequenceNumbers" />.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-237">Nachrichten, die Sequenznummer identifizierte werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="31d13-237">Messages identified by sequence number are returned.</span></span> <span data-ttu-id="31d13-238">Gibt null zurück, wenn keine Nachrichten gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-238">Returns null if no messages are found.</span></span>
            <span data-ttu-id="31d13-239">Löst aus, wenn die Nachrichten, nicht verzögert wurde.</span><span class="sxs-lookup"><span data-stu-id="31d13-239">Throws if the messages have not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="31d13-240">Die Sequenznummer der Nachricht, die empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-240">The sequence number of the message that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-241">Empfängt eine bestimmte verzögerte Nachricht erkennbar <paramref name="sequenceNumber" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-241">Receives a specific deferred message identified by <paramref name="sequenceNumber" />.</span></span>
            </summary>
        <returns><span data-ttu-id="31d13-242">Nachricht erkennbar Sequenznummer <paramref name="sequenceNumber" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-242">Message identified by sequence number <paramref name="sequenceNumber" />.</span></span> <span data-ttu-id="31d13-243">Gibt null zurück, wenn keine solche Nachricht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-243">Returns null if no such message is found.</span></span>
            <span data-ttu-id="31d13-244">Löst aus, wenn die Nachricht nicht verzögert wurde.</span><span class="sxs-lookup"><span data-stu-id="31d13-244">Throws if the message has not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31d13-245">Ruft die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> des aktuellen Empfängers.</span><span class="sxs-lookup"><span data-stu-id="31d13-245">Gets the <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> of the current receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31d13-246">Ruft eine Liste der derzeit registrierten Plug-Ins ab.</span><span class="sxs-lookup"><span data-stu-id="31d13-246">Gets a list of currently registered plugins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="messageHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="31d13-247">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="31d13-247">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="messageHandlerOptions"><span data-ttu-id="31d13-248">Die <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> Optionen zum Konfigurieren der Einstellungen der Datapump verwendet.</span><span class="sxs-lookup"><span data-stu-id="31d13-248">The <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> options used to configure the settings of the pump.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-249">Empfangen von Nachrichten dauerhaft aus der Entität.</span><span class="sxs-lookup"><span data-stu-id="31d13-249">Receive messages continuously from the entity.</span></span> <span data-ttu-id="31d13-250">Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="31d13-250">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="31d13-251">Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-251">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="31d13-252">Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</span><span class="sxs-lookup"><span data-stu-id="31d13-252">Enable prefetch to speed up the receive rate.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="31d13-253">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="31d13-253">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="31d13-254">Ein <see cref="T:System.Func`2" /> wird, um Ausnahmen zu benachrichtigen.</span><span class="sxs-lookup"><span data-stu-id="31d13-254">A <see cref="T:System.Func`2" /> that is used to notify exceptions.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-255">Empfangen von Nachrichten dauerhaft aus der Entität.</span><span class="sxs-lookup"><span data-stu-id="31d13-255">Receive messages continuously from the entity.</span></span> <span data-ttu-id="31d13-256">Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.</span><span class="sxs-lookup"><span data-stu-id="31d13-256">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="31d13-257">Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="31d13-257">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="messageReceiver.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
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
        <param name="serviceBusPlugin"><span data-ttu-id="31d13-258">Die <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> registrieren</span><span class="sxs-lookup"><span data-stu-id="31d13-258">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register</span></span></param>
        <summary>
            <span data-ttu-id="31d13-259">Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit dieser Empfänger verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="31d13-259">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="31d13-260">Erneuert die Sperre für die Nachricht durch das Sperrtoken angegeben.</span><span class="sxs-lookup"><span data-stu-id="31d13-260">Renews the lock on the message specified by the lock token.</span></span> <span data-ttu-id="31d13-261">Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-261">The lock will be renewed based on the setting specified on the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="31d13-262">Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).</span><span class="sxs-lookup"><span data-stu-id="31d13-262">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="31d13-263">Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-263">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="31d13-264">Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="31d13-264">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="31d13-265">Der Nachricht zugeordnete Sperrtoken.</span><span class="sxs-lookup"><span data-stu-id="31d13-265">Lock token associated with the message.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-266">Erneuert die Sperre für die Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="31d13-266">Renews the lock on the message.</span></span> <span data-ttu-id="31d13-267">Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-267">The lock will be renewed based on the setting specified on the queue.</span></span>
            <span data-ttu-id="31d13-268"><returns>Neue Sperre token Ablaufdatum und die Uhrzeit in UTC-Format.</returns></span><span class="sxs-lookup"><span data-stu-id="31d13-268"><returns>New lock token expiry date and time in UTC format.</returns></span></span></summary>
        <returns><span data-ttu-id="31d13-269">Der asynchrone Vorgang.</span><span class="sxs-lookup"><span data-stu-id="31d13-269">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="31d13-270">Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).</span><span class="sxs-lookup"><span data-stu-id="31d13-270">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="31d13-271">Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-271">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="31d13-272">Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="31d13-272">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="messageReceiver.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
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
        <param name="serviceBusPluginName"><span data-ttu-id="31d13-273">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> des Plug-Ins zum aufgehoben werden.</span><span class="sxs-lookup"><span data-stu-id="31d13-273">The <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> of the plugin to be unregistered.</span></span></param>
        <summary>
            <span data-ttu-id="31d13-274">Hebt die Registrierung einer <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span><span class="sxs-lookup"><span data-stu-id="31d13-274">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>