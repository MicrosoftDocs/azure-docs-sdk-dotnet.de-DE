<Type Name="TopicDescription" FullName="Microsoft.ServiceBus.Messaging.TopicDescription">
  <TypeSignature Language="C#" Value="public sealed class TopicDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TopicDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TopicDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type TopicDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="TopicDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="c9864-101">Eine Beschreibung des Themas darstellt.</span><span class="sxs-lookup"><span data-stu-id="c9864-101">Represents a description of the topic.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.TopicDescription : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="new Microsoft.ServiceBus.Messaging.TopicDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="c9864-102">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</span><span class="sxs-lookup"><span data-stu-id="c9864-102">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="c9864-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> Klasse mit dem angegebenen relativen Pfad.</span><span class="sxs-lookup"><span data-stu-id="c9864-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> class with the specified relative path.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-104">Ruft die Zeit und Datum, an dem zuletzt eine Nachricht an das Thema gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="c9864-104">Gets the time and date at which a message was last sent to the topic.</span></span></summary>
        <value><span data-ttu-id="c9864-105">Die Uhrzeit und Datum, an dem zuletzt eine Nachricht an das Thema gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="c9864-105">The time and date at which a message was last sent to the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-106">Ruft die Autorisierungsregeln für die Beschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="c9864-106">Gets the authorization rules for the description.</span></span></summary>
        <value><span data-ttu-id="c9864-107">Die Autorisierungsregeln für die Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="c9864-107">The authorization rules for the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-108">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> leerlaufintervalls nach dem Thema automatisch gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c9864-108">Gets or sets the <see cref="T:System.TimeSpan" /> idle interval after which the topic is automatically deleted.</span></span> <span data-ttu-id="c9864-109">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="c9864-109">The minimum duration is 5 minutes.</span></span></summary>
        <value><span data-ttu-id="c9864-110">Das automatische Löschen im Leerlauf Zeitspanne für das Thema.</span><span class="sxs-lookup"><span data-stu-id="c9864-110">The auto delete on idle time span for the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-111">Ruft den Status der Verfügbarkeit von dieser Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="c9864-111">Gets the status of the availability of this instance.</span></span></summary>
        <value><span data-ttu-id="c9864-112">Der Status der Verfügbarkeit von dieser Instanz.</span><span class="sxs-lookup"><span data-stu-id="c9864-112">The status of the availability of this instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-113">Ruft die Uhrzeit und Datum, an das Thema erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="c9864-113">Gets the time and date when the topic was created.</span></span></summary>
        <value><span data-ttu-id="c9864-114">Die Uhrzeit und Datum, an das Thema erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="c9864-114">The time and date when the topic was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-115">Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert für ein Thema.</span><span class="sxs-lookup"><span data-stu-id="c9864-115">Gets or sets the default message time to live value for a topic.</span></span> <span data-ttu-id="c9864-116">Hierbei handelt es sich um den Zeitraum, nach dem Ablauf die Nachricht beginnend ab dem Zeitpunkt der Nachricht an den Servicebus gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="c9864-116">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="c9864-117">Dies ist die Standardeinstellung Wert wird verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> für eine Nachricht selbst nicht festgelegt ist. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c9864-117">This is the default value used when <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> is not set on a message itself.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="c9864-118">Abonnenten werden können abgelaufene Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="c9864-118">Subscribers will be unable to receive expired messages.</span></span></summary>
        <value><span data-ttu-id="c9864-119">Die Nachricht Standardzeit Gültigkeitsdauer für ein Thema.</span><span class="sxs-lookup"><span data-stu-id="c9864-119">The default message time to live for a topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-120">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="c9864-120">Gets or sets the <see cref="T:System.TimeSpan" /> structure that defines the duration of the duplicate detection history.</span></span></summary>
        <value><span data-ttu-id="c9864-121">Die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="c9864-121">The <see cref="T:System.TimeSpan" /> structure that defines the duration of the duplicate detection history.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-122">Ruft ab oder legt einen Wert, der angibt, ob serverseitige Batchvorgänge aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="c9864-122">Gets or sets a value that indicates whether server-side batched operations are enabled.</span></span></summary>
        <value><span data-ttu-id="c9864-123">"true", wenn der Batch-Vorgänge aktiviert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-123">true if the batched operations are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-124">Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="c9864-124">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="c9864-125">Ein expressthema speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="c9864-125">An express topic holds a message in memory temporarily before writing it to persistent storage.</span></span></summary>
        <value><span data-ttu-id="c9864-126">"true", wenn die Express-Entitäten aktiviert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-126">true if the Express Entities are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFilteringMessagesBeforePublishing">
      <MemberSignature Language="C#" Value="public bool EnableFilteringMessagesBeforePublishing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFilteringMessagesBeforePublishing As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableFilteringMessagesBeforePublishing : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-127">Ruft ab oder legt fest, ob Nachrichten vor der Veröffentlichung gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c9864-127">Gets or sets whether messages should be filtered before publishing.</span></span></summary>
        <value><span data-ttu-id="c9864-128">"true", wenn die nachrichtenfilterung vor der Veröffentlichung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-128">true if message filtering is enabled before publishing; otherwise, false.</span></span></value>
        <remarks> <span data-ttu-id="c9864-129">Dieses Feature wird empfohlen, nur für Entwicklungs- und Testzwecken verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c9864-129">This feature is recommended to be used only for development and testing purposes.</span></span>  
            <span data-ttu-id="c9864-130">Wenn an das Thema neue Regeln oder Filter hinzugefügt werden, kann z. B. diese Funktion verwendet werden, stellen Sie sicher, dass der neue Filter-Ausdruck wie erwartet funktioniert.</span><span class="sxs-lookup"><span data-stu-id="c9864-130">For example, when  new Rules or Filters are being added to the topic, this feature can be used to verify that the new filter expression is working as expected.</span></span> <span data-ttu-id="c9864-131">Sobald getestet und einwandfrei funktioniert, sollte die Funktion in der produktionsumgebung deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="c9864-131">Once tested and working fine, the feature should be turned off in production.</span></span> </remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException"><span data-ttu-id="c9864-132">Wird ausgelöst, wenn die Abonnements nicht übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c9864-132">Thrown if the subscriptions do not match.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-133">Ruft ab oder legt fest, ob So aktivieren Sie das Thema, um mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="c9864-133">Gets or sets whether to enable the topic to be partitioned across multiple message brokers.</span></span> <span data-ttu-id="c9864-134">Ein expressthema speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="c9864-134">An express topic holds a message in memory temporarily before writing it to persistent storage.</span></span></summary>
        <value><span data-ttu-id="c9864-135">True, aktivieren Sie das Thema, um mehrere nachrichtenbroker partitioniert werden soll. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-135">true to enable the topic to be partitioned across multiple message brokers; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-136">Ruft ab, ob anonymer Zugriff zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="c9864-136">Gets whether anonymous access is allowed.</span></span></summary>
        <value><span data-ttu-id="c9864-137">"true", wenn anonymer Zugriff zulässig ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-137">true if anonymous access is allowed; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-138">Ruft ab oder legt die maximale Größe des Themas in Megabyte an, die Größe des Arbeitsspeichers, die für das Thema zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="c9864-138">Gets or sets the maximum size of the topic in megabytes, which is the size of memory allocated for the topic.</span></span></summary>
        <value><span data-ttu-id="c9864-139">Die maximale Größe in Megabyte.</span><span class="sxs-lookup"><span data-stu-id="c9864-139">The maximum size in megabytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-140">Ruft Nachrichtendetails zum Thema ab.</span><span class="sxs-lookup"><span data-stu-id="c9864-140">Gets message details about the topic.</span></span></summary>
        <value><span data-ttu-id="c9864-141">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> , enthält die Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten an andere Warteschlangen, Abonnements oder Themen zu übertragen, und übertragen Sie die Anzahl der Nachrichten an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="c9864-141">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> that contains the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
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
              <span data-ttu-id="c9864-142">Der Zeitpunkt der live-Standardwert</span><span class="sxs-lookup"><span data-stu-id="c9864-142">The message time to live default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-143">Ruft den Pfad des Themas.</span><span class="sxs-lookup"><span data-stu-id="c9864-143">Gets the path of the topic.</span></span></summary>
        <value><span data-ttu-id="c9864-144">Der Pfad des Themas.</span><span class="sxs-lookup"><span data-stu-id="c9864-144">The path of the topic.</span></span></value>
        <remarks>
              <span data-ttu-id="c9864-145">Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span><span class="sxs-lookup"><span data-stu-id="c9864-145">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-146">Ruft ab oder legt den Wert, der angibt, ob ein Thema Duplizierung Erkennung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="c9864-146">Gets or sets the value that indicates whether a topic requires duplication detection.</span></span></summary>
        <value><span data-ttu-id="c9864-147">"true", wenn ein Thema Duplizierung Erkennung erfordert; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9864-147">true if a topic requires duplication detection; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-148">Ruft die Größe des Themas in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="c9864-148">Gets the size of the topic in bytes.</span></span></summary>
        <value><span data-ttu-id="c9864-149">Die Größe des Themas in Bytes.</span><span class="sxs-lookup"><span data-stu-id="c9864-149">The size of the topic in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-150">Ruft ab oder legt den aktuellen Status des Themas (aktiviert oder deaktiviert) fest.</span><span class="sxs-lookup"><span data-stu-id="c9864-150">Gets or sets the current status of the topic (enabled or disabled).</span></span> <span data-ttu-id="c9864-151">Wenn eine Entität deaktiviert ist, kann keine diese Entität Nachrichten senden oder empfangen.</span><span class="sxs-lookup"><span data-stu-id="c9864-151">When an entity is disabled, that entity cannot send or receive messages.</span></span></summary>
        <value><span data-ttu-id="c9864-152">Der Status des Themas.</span><span class="sxs-lookup"><span data-stu-id="c9864-152">The status of the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public int SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : int" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-153">Klicken Sie dann Anzahl der Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="c9864-153">Gets then number of subscriptions.</span></span></summary>
        <value><span data-ttu-id="c9864-154">Eine <see cref="T:System.Int32" /> , die die Anzahl der Abonnements darstellt.</span><span class="sxs-lookup"><span data-stu-id="c9864-154">An <see cref="T:System.Int32" /> that represents the number of subscriptions.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-155">Ruft ab oder legt die Reihenfolge der Methode Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="c9864-155">Gets or sets the support ordering method.</span></span></summary>
        <value><span data-ttu-id="c9864-156">Die Unterstützung, die Reihenfolge der Methode.</span><span class="sxs-lookup"><span data-stu-id="c9864-156">The support ordering method.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-157">Ruft die Uhrzeit und Datum, an das Thema wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="c9864-157">Gets the time and date when the topic was updated.</span></span></summary>
        <value><span data-ttu-id="c9864-158">Die Uhrzeit und Datum, an das Thema wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="c9864-158">The time and date when the topic was updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c9864-159">Abrufen oder Festlegen der dieser Beschreibung zugeordnete Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="c9864-159">Gets or sets the user metadata associated with the description.</span></span></summary>
        <value><span data-ttu-id="c9864-160">Die dieser Beschreibung zugeordnete Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="c9864-160">The user metadata associated with the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>