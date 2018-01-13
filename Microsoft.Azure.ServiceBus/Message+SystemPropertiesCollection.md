<Type Name="Message+SystemPropertiesCollection" FullName="Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class Message.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit Message/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type Message.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="538c4-101">Eine Auflistung verwendet, um Eigenschaften zu speichern, die vom Service Bus-Dienst festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="538c4-101">A collection used to store properties which are set by the Service Bus service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SystemPropertiesCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
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
            <span data-ttu-id="538c4-102">Ruft den Namen der Warteschlange oder einem Abonnement ab, diese Nachricht in die Warteschlange eingereiht, war, bevor es als unzustellbar gekennzeichnet war.</span><span class="sxs-lookup"><span data-stu-id="538c4-102">Gets the name of the queue or subscription that this message was enqueued on, before it was deadlettered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
                Only set in messages that have been dead-lettered and subsequently auto-forwarded from the dead-letter queue 
                <span data-ttu-id="538c4-103">zu einer anderen Entität.</span><span class="sxs-lookup"><span data-stu-id="538c4-103">to another entity.</span></span> <span data-ttu-id="538c4-104">Gibt die Entität an, in der die Nachricht unzustellbar war.</span><span class="sxs-lookup"><span data-stu-id="538c4-104">Indicates the entity in which the message was dead-lettered.</span></span> <span data-ttu-id="538c4-105">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-105">This property is read-only.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="538c4-106">Abrufen der aktuellen Übermittlungsanzahl an.</span><span class="sxs-lookup"><span data-stu-id="538c4-106">Get the current delivery count.</span></span>
            </summary>
        <value><span data-ttu-id="538c4-107">Dieser Wert beginnt mit 1.</span><span class="sxs-lookup"><span data-stu-id="538c4-107">This value starts at 1.</span></span></value>
        <remarks>
               <span data-ttu-id="538c4-108">Anzahl der Zustellversuche dieser Nachricht.</span><span class="sxs-lookup"><span data-stu-id="538c4-108">Number of deliveries that have been attempted for this message.</span></span> <span data-ttu-id="538c4-109">Die Anzahl wird erhöht, wenn eine Nachrichtensperre abläuft oder die Nachricht vom Empfänger explizit abgewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="538c4-109">The count is incremented when a message lock expires, or the message is explicitly abandoned by the receiver.</span></span> <span data-ttu-id="538c4-110">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-110">This property is read-only.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
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
        <summary><span data-ttu-id="538c4-111">Ruft ab oder legt die ursprüngliche Sequenznummer der Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="538c4-111">Gets or sets the original sequence number of the message.</span></span></summary>
        <value><span data-ttu-id="538c4-112">Die in die Warteschlange eingereihten Sequenznummer der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="538c4-112">The enqueued sequence number of the message.</span></span></value>
        <remarks>
            <span data-ttu-id="538c4-113">Bei Nachrichten, die automatisch weitergeleitet wurden, entspricht diese Eigenschaft der Sequenznummer, die der Nachricht zum Zeitpunkt ihrer ursprünglichen Übermittlung zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="538c4-113">For messages that have been auto-forwarded, this property reflects the sequence number that had first been assigned to the message at its original point of submission.</span></span> <span data-ttu-id="538c4-114">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-114">This property is read-only.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="538c4-115">Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="538c4-115">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="538c4-116">Die in die Warteschlange einzureihen Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="538c4-116">The enqueue time in UTC.</span></span> </value>
        <remarks>
               <span data-ttu-id="538c4-117">Der UTC-Moment, in dem die Nachricht angenommen und in der Entität gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="538c4-117">The UTC instant at which the message has been accepted and stored in the entity.</span></span> <span data-ttu-id="538c4-118">Dieser Wert kann als autoritative und neutrale Eingangszeitangabe verwendet werden, wenn der Empfänger der Uhr des Absenders nicht vertrauen möchte.</span><span class="sxs-lookup"><span data-stu-id="538c4-118">This value can be used as an authoritative and neutral arrival time indicator when the receiver does not want to trust the sender's clock.</span></span> <span data-ttu-id="538c4-119">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-119">This property is read-only.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLockTokenSet">
      <MemberSignature Language="C#" Value="public bool IsLockTokenSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLockTokenSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLockTokenSet As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLockTokenSet : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="538c4-120">Gibt an, ob eine Sperrtoken, legen Sie für die aktuelle Nachricht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="538c4-120">Specifies whether or not there is a lock token set on the current message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="538c4-121">Ein Sperrtoken werden nur angegeben, wenn die Nachricht empfangen wurde<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></span><span class="sxs-lookup"><span data-stu-id="538c4-121">A lock token will only be specified if the message was received using <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReceived">
      <MemberSignature Language="C#" Value="public bool IsReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReceived As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReceived : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="538c4-122">Gibt an, ob die Nachricht aus der Broker abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="538c4-122">Specifies if the message has been obtained from the broker.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="538c4-123">Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="538c4-123">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="538c4-124">Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="538c4-124">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>
                For messages retrieved under a lock (peek-lock receive mode, not pre-settled) this property reflects the UTC 
                <span data-ttu-id="538c4-125">Zeitpunkt, bis zu dem die Nachricht verbleibt, im der Warteschlange/Abonnement gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="538c4-125">instant until which the message is held locked in the queue/subscription.</span></span> <span data-ttu-id="538c4-126">Nach Ablauf der Sperre der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" /> wird erhöht, und die Nachricht wird erneut zum Abrufen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="538c4-126">When the lock expires, the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" /> is incremented and the message is again available for retrieval.</span></span> <span data-ttu-id="538c4-127">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-127">This property is read-only.</span></span>
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
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
            <span data-ttu-id="538c4-128">Ruft die Sperre für die aktuelle Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="538c4-128">Gets the lock token for the current message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
              <span data-ttu-id="538c4-129">Das Sperrtoken ist ein Verweis auf die Sperre, die vom Broker in gehalten wird <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="538c4-129">The lock token is a reference to the lock that is being held by the broker in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode.</span></span> <span data-ttu-id="538c4-130">Sperren werden verwendet, um Nachrichten explizit ausgleichen, wie beschrieben in der <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">Produktdokumentation ausführlicher</a>.</span><span class="sxs-lookup"><span data-stu-id="538c4-130">Locks are used to explicitly settle messages as explained in the <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">product documentation in more detail</a>.</span></span>
              <span data-ttu-id="538c4-131">Das Token kann auch verwendet werden, um die Sperre endgültig durch anheften der <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">Deferral API</a> und bei, die die Nachricht aus der regulären Delivery Status Datenfluss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="538c4-131">The token can also be used to pin the lock permanently through the <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">Deferral API</a> and, with that, take the message out of the regular delivery state flow.</span></span> <span data-ttu-id="538c4-132">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-132">This property is read-only.</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
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
        <summary><span data-ttu-id="538c4-133">Ruft die eindeutige Nummer, die eine Nachricht vom Service Bus zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="538c4-133">Gets the unique number assigned to a message by Service Bus.</span></span></summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="538c4-134">Die Sequenznummer ist eine eindeutige ganze 64-Bit-Zahl, die einer Nachricht zugeordnet wird, sobald sie vom Broker akzeptiert und gespeichert wird, und fungiert als ihr tatsächlicher Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="538c4-134">The sequence number is a unique 64-bit integer assigned to a message as it is accepted and stored by the broker and functions as its true identifier.</span></span> <span data-ttu-id="538c4-135">Bei partitionierte Entitäten stellen die obersten 16 Bits den Partitionsbezeichner dar.</span><span class="sxs-lookup"><span data-stu-id="538c4-135">For partitioned entities, the topmost 16 bits reflect the partition identifier.</span></span> <span data-ttu-id="538c4-136">Sequenznummern erhöhen monoton.</span><span class="sxs-lookup"><span data-stu-id="538c4-136">Sequence numbers monotonically increase.</span></span> <span data-ttu-id="538c4-137">Sie werden auf 0 zurückgesetzt, sobald der 48-64-Bit-Bereich ausgeschöpft ist.</span><span class="sxs-lookup"><span data-stu-id="538c4-137">They roll over to 0 when the 48-64 bit range is exhausted.</span></span> <span data-ttu-id="538c4-138">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="538c4-138">This property is read-only.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>