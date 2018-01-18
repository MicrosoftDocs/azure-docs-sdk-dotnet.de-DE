<Type Name="QueueDescription" FullName="Microsoft.ServiceBus.Messaging.QueueDescription">
  <TypeSignature Language="C#" Value="public sealed class QueueDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type QueueDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="QueueDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="4b720-101">Stellt die Metadatenbeschreibung der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-101">Represents the metadata description of the queue.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QueueDescription : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="new Microsoft.ServiceBus.Messaging.QueueDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="4b720-102">Der Pfad der Warteschlange relativ zur Basisadresse Namespace.</span><span class="sxs-lookup"><span data-stu-id="4b720-102">Path of the queue relative to the namespace base address.</span></span></param>
        <summary><span data-ttu-id="4b720-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> Klasse mit dem angegebenen relativen Pfad.</span><span class="sxs-lookup"><span data-stu-id="4b720-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> class with the specified relative path.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-104">Ruft das letzte Mal eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-104">Gets the last time a message was sent, or the last time there was a receive request to this queue.</span></span></summary>
        <value><span data-ttu-id="4b720-105">Das letzte Mal eine Receive-Anforderung an diese Warteschlange wurde, oder das letzte Mal eine Nachricht gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="4b720-105">The last time a message was sent, or the last time there was a receive request to this queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-106">Ruft das <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ab.</span><span class="sxs-lookup"><span data-stu-id="4b720-106">Gets the <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span></span></summary>
        <value><span data-ttu-id="4b720-107">Die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span><span class="sxs-lookup"><span data-stu-id="4b720-107">The <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-108">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> leerlaufintervalls nach dem die Warteschlange automatisch gelöscht.</span><span class="sxs-lookup"><span data-stu-id="4b720-108">Gets or sets the <see cref="T:System.TimeSpan" /> idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="4b720-109">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="4b720-109">The minimum duration is 5 minutes.</span></span></summary>
        <value><span data-ttu-id="4b720-110">Das automatische Löschen im Leerlauf Zeitspanne für die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-110">The auto delete on idle time span for the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-111">Ruft den Verfügbarkeitsstatus für die Entität für die Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="4b720-111">Gets the entity availability status for the queue.</span></span></summary>
        <value><span data-ttu-id="4b720-112">Der Status der Entität Verfügbarkeit für die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-112">The entity availability status for the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-113">Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.</span><span class="sxs-lookup"><span data-stu-id="4b720-113">Gets the exact time the message was created.</span></span></summary>
        <value><span data-ttu-id="4b720-114">Der Zeitpunkt, an die Nachricht erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="4b720-114">The time the message was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-115">Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="4b720-115">Gets or sets the default message time to live value.</span></span> <span data-ttu-id="4b720-116">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft.</span><span class="sxs-lookup"><span data-stu-id="4b720-116">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="4b720-117">Dies ist die Standardeinstellung Wert wird verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> für eine Nachricht selbst nicht festgelegt ist. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="4b720-117">This is the default value used when <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> is not set on a message itself.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="4b720-118">Abonnenten werden können abgelaufene Nachrichten empfangen. Eine Nachricht kann einen niedrigeren TimeToLive-Wert als die hier angegebene aufweisen, aber standardmäßig TimeToLive festgelegt ist, um <see cref="F:System.TimeSpan.MaxValue" />.</span><span class="sxs-lookup"><span data-stu-id="4b720-118">Subscribers will be unable to receive expired messages.A message can have a lower TimeToLive value than that specified here, but by default TimeToLive is set to <see cref="F:System.TimeSpan.MaxValue" />.</span></span> <span data-ttu-id="4b720-119">Aus diesem Grund wird diese Eigenschaft die Standardzeit TTL-Wert auf Nachrichten angewendet.</span><span class="sxs-lookup"><span data-stu-id="4b720-119">Therefore, this property becomes the default time to live value applied to messages.</span></span></summary>
        <value><span data-ttu-id="4b720-120">Die Nachricht Standardzeit TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="4b720-120">The default message time to live value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-121">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="4b720-121">Gets or sets the <see cref="T:System.TimeSpan" /> structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="4b720-122">Der Standardwert ist 10 Minuten.</span><span class="sxs-lookup"><span data-stu-id="4b720-122">The default value is 10 minutes.</span></span></summary>
        <value><span data-ttu-id="4b720-123">Die <see cref="T:System.TimeSpan" /> -Struktur, die Zeitfenster für Verlauf der duplikaterkennung Duplizierung darstellt.</span><span class="sxs-lookup"><span data-stu-id="4b720-123">The <see cref="T:System.TimeSpan" /> structure that represents the time windows for duplication detection history.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-124">Ruft ab oder legt einen Wert, der angibt, ob serverseitige Batchvorgänge aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="4b720-124">Gets or sets a value that indicates whether server-side batched operations are enabled.</span></span></summary>
        <value><span data-ttu-id="4b720-125">"true", wenn der Batch-Vorgänge aktiviert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-125">true if the batched operations are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-126">Ruft ab oder legt einen Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="4b720-126">Gets or sets a value that indicates whether this queue has dead letter support when a message expires.</span></span></summary>
        <value><span data-ttu-id="4b720-127">True, wenn die Warteschlange für unzustellbare Support bei Ablauf einer Nachricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-127">true if the queue has a dead letter support when a message expires; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-128">Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="4b720-128">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="4b720-129">Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="4b720-129">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span></summary>
        <value><span data-ttu-id="4b720-130">"true", wenn die Express-Entitäten aktiviert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-130">true if Express Entities are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-131">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange, die mehrere nachrichtenbroker partitioniert werden aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="4b720-131">Gets or sets a value that indicates whether the queue to be partitioned across multiple message brokers is enabled.</span></span> </summary>
        <value><span data-ttu-id="4b720-132">"true", wenn die Warteschlange, die mehrere nachrichtenbroker partitioniert werden aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-132">true if the queue to be partitioned across multiple message brokers is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-133">Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="4b720-133">Gets or sets the path to the recipient to which the dead lettered message is forwarded.</span></span></summary>
        <value><span data-ttu-id="4b720-134">Der Pfad für den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="4b720-134">The path to the recipient to which the dead lettered message is forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-135">Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="4b720-135">Gets or sets the path to the recipient to which the message is forwarded.</span></span></summary>
        <value><span data-ttu-id="4b720-136">Der Pfad für den Empfänger, an dem die Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="4b720-136">The path to the recipient to which the message is forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-137">Ruft ab oder legt einen Wert, der angibt, ob die Nachricht anonym ist zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="4b720-137">Gets or sets a value that indicates whether the message is anonymous accessible.</span></span></summary>
        <value><span data-ttu-id="4b720-138">"true", wenn die Nachricht anonym ist zugegriffen werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-138">true if the message is anonymous accessible; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-139">Ruft ab oder legt die Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="4b720-139">Gets or sets the duration of a peek lock; that is, the amount of time that the message is locked for other receivers.</span></span> <span data-ttu-id="4b720-140">Der Höchstwert für <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> beträgt fünf Minuten; der Standardwert beträgt 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="4b720-140">The maximum value for <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> is 5 minutes; the default value is 1 minute.</span></span></summary>
        <value><span data-ttu-id="4b720-141">Die Dauer der Sperre.</span><span class="sxs-lookup"><span data-stu-id="4b720-141">The duration of the lock.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-142">Ruft ab oder legt die Anzahl maximaler Zustellungen.</span><span class="sxs-lookup"><span data-stu-id="4b720-142">Gets or sets the maximum delivery count.</span></span> <span data-ttu-id="4b720-143">Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="4b720-143">A message is automatically deadlettered after this number of deliveries.</span></span></summary>
        <value><span data-ttu-id="4b720-144">Die Anzahl der maximale Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="4b720-144">The number of maximum deliveries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-145">Ruft ab oder legt die maximale Größe der Warteschlange in Megabyte an, die Größe des Arbeitsspeichers für die Warteschlange ist.</span><span class="sxs-lookup"><span data-stu-id="4b720-145">Gets or sets the maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span></summary>
        <value><span data-ttu-id="4b720-146">Die maximale Größe der Warteschlange in Megabyte.</span><span class="sxs-lookup"><span data-stu-id="4b720-146">The maximum size of the queue in megabytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-147">Ruft die Anzahl der Nachrichten in der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="4b720-147">Gets the number of messages in the queue.</span></span></summary>
        <value><span data-ttu-id="4b720-148">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="4b720-148">The number of messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-149">Ruft die Details für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-149">Gets message details for a queue.</span></span></summary>
        <value><span data-ttu-id="4b720-150">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> mit der Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten, die auf andere Warteschlangen, Abonnements oder Themen übertragen. anschließend übertragen Sie die Anzahl der Nachrichten an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-150">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> with the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
              <span data-ttu-id="4b720-151">Der Zeitpunkt der live Standardwert in bytes</span><span class="sxs-lookup"><span data-stu-id="4b720-151">The message time to live default value in bytes</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-152">Ruft ab oder legt den Namen der Warteschlange fest.</span><span class="sxs-lookup"><span data-stu-id="4b720-152">Gets or sets the name of the queue.</span></span></summary>
        <value><span data-ttu-id="4b720-153">Der Name der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-153">The name of the queue.</span></span></value>
        <remarks>
              <span data-ttu-id="4b720-154">Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span><span class="sxs-lookup"><span data-stu-id="4b720-154">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-155">Ruft ab oder legt den Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="4b720-155">Gets or sets the value indicating if this queue requires duplicate detection.</span></span></summary>
        <value><span data-ttu-id="4b720-156">True, wenn diese Warteschlange muss die Erkennung von Duplikaten; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-156">true if this queue requires duplicate detection; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-157">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange das Konzept der Sitzung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4b720-157">Gets or sets a value that indicates whether the queue supports the concept of session.</span></span></summary>
        <value><span data-ttu-id="4b720-158">"true", wenn der empfängeranwendung nur aus der Warteschlange über erhalten kann eine <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false, wenn eine Warteschlange empfangen kann mit <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span><span class="sxs-lookup"><span data-stu-id="4b720-158">true if the receiver application can only receive from the queue through a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false if a queue cannot receive using <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-159">Ruft die Größe der Warteschlange in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="4b720-159">Gets the size of the queue in bytes.</span></span></summary>
        <value><span data-ttu-id="4b720-160">Die Größe der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-160">The size of the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-161">Ruft ab oder legt den aktuellen Status der Warteschlange (aktiviert oder deaktiviert) fest.</span><span class="sxs-lookup"><span data-stu-id="4b720-161">Gets or sets the current status of the queue (enabled or disabled).</span></span> <span data-ttu-id="4b720-162">Wenn eine Entität deaktiviert ist, kann keine diese Entität Nachrichten senden oder empfangen.</span><span class="sxs-lookup"><span data-stu-id="4b720-162">When an entity is disabled, that entity cannot send or receive messages.</span></span></summary>
        <value><span data-ttu-id="4b720-163">Der aktuelle Status der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4b720-163">The current status of the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-164">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange Sortierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4b720-164">Gets or sets a value that indicates whether the queue supports ordering.</span></span></summary>
        <value><span data-ttu-id="4b720-165">"true", wenn die Warteschlange unterstützt Sortierung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="4b720-165">true if the queue supports ordering; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-166">Ruft die genaue Uhrzeit, zu der die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="4b720-166">Gets the exact time the message has been updated.</span></span></summary>
        <value><span data-ttu-id="4b720-167">Der Zeitpunkt, zu die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="4b720-167">The time the message has been updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4b720-168">Ruft ab oder legt die Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="4b720-168">Gets or sets the user metadata.</span></span></summary>
        <value><span data-ttu-id="4b720-169">Die Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="4b720-169">The user metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>