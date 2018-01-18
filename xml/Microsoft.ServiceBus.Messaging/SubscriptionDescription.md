<Type Name="SubscriptionDescription" FullName="Microsoft.ServiceBus.Messaging.SubscriptionDescription">
  <TypeSignature Language="C#" Value="public sealed class SubscriptionDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SubscriptionDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SubscriptionDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type SubscriptionDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SubscriptionDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="93f5e-101">Stellt eine Beschreibung des Abonnements an.</span><span class="sxs-lookup"><span data-stu-id="93f5e-101">Represents a description of the subscription.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDescription (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (topicPath As String, subscriptionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SubscriptionDescription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="new Microsoft.ServiceBus.Messaging.SubscriptionDescription (topicPath, subscriptionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="93f5e-102">Der Themenname.</span><span class="sxs-lookup"><span data-stu-id="93f5e-102">The topic path.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="93f5e-103">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="93f5e-103">The subscription name.</span></span></param>
        <summary><span data-ttu-id="93f5e-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="93f5e-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-105">Ruft ab, es gibt eine empfangsanforderung für dieses Abonnement wurde, zuletzt.</span><span class="sxs-lookup"><span data-stu-id="93f5e-105">Gets the last time a there was a receive request to this subscription.</span></span></summary>
        <value><span data-ttu-id="93f5e-106">Zeitpunkt der letzten war es gibt eine empfangsanforderung für dieses Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="93f5e-106">The last time a there was a receive request to this subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-107">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> leerlaufintervalls nach dem das Abonnement automatisch gelöscht.</span><span class="sxs-lookup"><span data-stu-id="93f5e-107">Gets or sets the <see cref="T:System.TimeSpan" /> idle interval after which the subscription is automatically deleted.</span></span> <span data-ttu-id="93f5e-108">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="93f5e-108">The minimum duration is 5 minutes.</span></span></summary>
        <value><span data-ttu-id="93f5e-109">Das automatische Löschen im Leerlauf Zeitspanne für das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="93f5e-109">The auto delete on idle time span for the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-110">Ruft den Verfügbarkeitsstatus der Entität für das messaging.</span><span class="sxs-lookup"><span data-stu-id="93f5e-110">Gets the entity availability status for the messaging.</span></span></summary>
        <value><span data-ttu-id="93f5e-111">Der Status der Entität Verfügbarkeit für das messaging.</span><span class="sxs-lookup"><span data-stu-id="93f5e-111">The entity availability status for the messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-112">Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.</span><span class="sxs-lookup"><span data-stu-id="93f5e-112">Gets the exact time the message was created.</span></span></summary>
        <value><span data-ttu-id="93f5e-113">Der Zeitpunkt, an die Nachricht erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="93f5e-113">The time the message was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-114">Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="93f5e-114">Gets or sets the default message time to live value.</span></span> <span data-ttu-id="93f5e-115">Hierbei handelt es sich um den Zeitraum, nach dem Ablauf die Nachricht beginnend ab dem Zeitpunkt der Nachricht an den Servicebus gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="93f5e-115">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="93f5e-116">Dies ist die Standardeinstellung Wert wird verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> für eine Nachricht selbst nicht festgelegt ist. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="93f5e-116">This is the default value used when <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> is not set on a message itself.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="93f5e-117">Abonnenten werden können abgelaufene Nachrichten empfangen. Eine Nachricht kann einen niedrigeren TimeToLive-Wert als die hier angegebene aufweisen, aber standardmäßig TimeToLive festgelegt ist, um <see cref="F:System.TimeSpan.MaxValue" />.</span><span class="sxs-lookup"><span data-stu-id="93f5e-117">Subscribers will be unable to receive expired messages.A message can have a lower TimeToLive value than that specified here, but by default TimeToLive is set to <see cref="F:System.TimeSpan.MaxValue" />.</span></span> <span data-ttu-id="93f5e-118">Aus diesem Grund wird diese Eigenschaft die Standardzeit TTL-Wert auf Nachrichten angewendet.</span><span class="sxs-lookup"><span data-stu-id="93f5e-118">Therefore, this property becomes the default time to live value applied to messages.</span></span></summary>
        <value><span data-ttu-id="93f5e-119">Die Nachricht Standardzeit Gültigkeitsdauer für ein Abonnement.</span><span class="sxs-lookup"><span data-stu-id="93f5e-119">The default message time to live for a subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-120">Ruft ab oder legt einen Wert, der angibt, ob die Batch-Vorgänge aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="93f5e-120">Gets or sets a value that indicates whether the batched operations are enabled.</span></span></summary>
        <value><span data-ttu-id="93f5e-121">"true", wenn der Batch-Vorgänge aktiviert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="93f5e-121">true if the batched operations are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnFilterEvaluationExceptions">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnFilterEvaluationExceptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnFilterEvaluationExceptions As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnFilterEvaluationExceptions : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-122">Ruft ab oder legt den Wert, der angibt, wenn ein Abonnement dead Letter auf Ausnahmen unterstützt verfügt.</span><span class="sxs-lookup"><span data-stu-id="93f5e-122">Gets or sets the value that indicates if a subscription has dead letter support on Filter evaluation exceptions.</span></span></summary>
        <value><span data-ttu-id="93f5e-123">True, wenn ein Abonnement hat die dead Letter auf Ausnahmen zu unterstützen. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="93f5e-123">true if a subscription has dead letter support on Filter evaluation exceptions; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-124">Ruft ab oder legt den Wert, der angibt, wenn ein Abonnement unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="93f5e-124">Gets or sets the value that indicates if a subscription has dead letter support when a message expires.</span></span></summary>
        <value><span data-ttu-id="93f5e-125">"true" abläuft hat ein Abonnement unzustellbare-Support, wenn eine Nachricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="93f5e-125">true if a subscription has dead letter support when a message expires; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-126">Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachrichten weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="93f5e-126">Gets or sets the path to the recipient to which the dead lettered messages are forwarded.</span></span></summary>
        <value><span data-ttu-id="93f5e-127">Der Pfad für den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachrichten weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="93f5e-127">The path to the recipient to which the dead lettered messages are forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-128">Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="93f5e-128">Gets or sets the path to the recipient to which the message is forwarded.</span></span></summary>
        <value><span data-ttu-id="93f5e-129">Der Pfad für den Empfänger, an dem die Nachricht weitergeleitet wird.</span><span class="sxs-lookup"><span data-stu-id="93f5e-129">The path to the recipient to which the message is forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-130">Ruft ab oder legt die Sperre Dauer Zeitspanne für das Abonnement.</span><span class="sxs-lookup"><span data-stu-id="93f5e-130">Gets or sets the lock duration time span for the subscription.</span></span></summary>
        <value><span data-ttu-id="93f5e-131">Die Sperrdauer Zeitspanne für das Abonnement an.</span><span class="sxs-lookup"><span data-stu-id="93f5e-131">The lock duration time span for the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-132">Ruft ab oder legt die Anzahl der maximale Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="93f5e-132">Gets or sets the number of maximum deliveries.</span></span></summary>
        <value><span data-ttu-id="93f5e-133">Die Anzahl der maximale Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="93f5e-133">The number of maximum deliveries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-134">Ruft die Anzahl der Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="93f5e-134">Gets the number of messages.</span></span></summary>
        <value><span data-ttu-id="93f5e-135">Die Anzahl der Meldungen.</span><span class="sxs-lookup"><span data-stu-id="93f5e-135">The number of messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-136">Ruft die Meldungsdetails zum Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="93f5e-136">Gets message details about the subscription.</span></span></summary>
        <value><span data-ttu-id="93f5e-137">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> mit der Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten, die auf andere Warteschlangen, Abonnements oder Themen übertragen. anschließend übertragen Sie die Anzahl der Nachrichten an die Dead Letter-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="93f5e-137">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> with the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
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
              <span data-ttu-id="93f5e-138">Der Zeitpunkt der live-Standardwert</span><span class="sxs-lookup"><span data-stu-id="93f5e-138">The message time to live default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-139">Ruft den Namen der abonnementbeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="93f5e-139">Gets the name of the subscription description.</span></span></summary>
        <value><span data-ttu-id="93f5e-140">Der Name der abonnementbeschreibung.</span><span class="sxs-lookup"><span data-stu-id="93f5e-140">The name of the subscription description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-141">Ruft ab oder legt den Wert, der angibt, wenn ein Abonnement, das Konzept der Sitzung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="93f5e-141">Gets or sets the value indicating if a subscription supports the concept of session.</span></span></summary>
        <value><span data-ttu-id="93f5e-142">"true", wenn der empfängeranwendung nur aus der Warteschlange über erhalten kann eine <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false, wenn eine Warteschlange empfangen kann mit <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span><span class="sxs-lookup"><span data-stu-id="93f5e-142">true if the receiver application can only receive from the queue through a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false if a queue cannot receive using <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-143">Ruft ab oder legt den aktuellen Status des Abonnements (aktiviert oder deaktiviert) fest.</span><span class="sxs-lookup"><span data-stu-id="93f5e-143">Gets or sets the current status of the subscription (enabled or disabled).</span></span> <span data-ttu-id="93f5e-144">Wenn eine Entität deaktiviert ist, kann keine diese Entität Nachrichten senden oder empfangen.</span><span class="sxs-lookup"><span data-stu-id="93f5e-144">When an entity is disabled, that entity cannot send or receive messages.</span></span></summary>
        <value><span data-ttu-id="93f5e-145">Der aktuelle Status des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="93f5e-145">The current status of the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-146">Ruft den Pfad des Themas, zu der diese abonnementbeschreibung gehört.</span><span class="sxs-lookup"><span data-stu-id="93f5e-146">Gets the path of the topic that this subscription description belongs to.</span></span></summary>
        <value><span data-ttu-id="93f5e-147">Der Pfad des Themas, zu der diese abonnementbeschreibung gehört.</span><span class="sxs-lookup"><span data-stu-id="93f5e-147">The path of the topic that this subscription description belongs to.</span></span></value>
        <remarks>
              <span data-ttu-id="93f5e-148">Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span><span class="sxs-lookup"><span data-stu-id="93f5e-148">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-149">Ruft die genaue Uhrzeit, zu der die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="93f5e-149">Gets the exact time the message has been updated.</span></span></summary>
        <value><span data-ttu-id="93f5e-150">Der Zeitpunkt, zu die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="93f5e-150">The time the message has been updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="93f5e-151">Ruft ab oder legt die Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="93f5e-151">Gets or sets the user metadata.</span></span></summary>
        <value><span data-ttu-id="93f5e-152">Die Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="93f5e-152">The user metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>