<Type Name="BrokeredMessageProperty" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessageProperty : System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessageProperty extends System.Object implements class System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessageProperty&#xA;Implements IMessageProperty" />
  <TypeSignature Language="F#" Value="type BrokeredMessageProperty = class&#xA;    interface IMessageProperty" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IMessageProperty</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="2c57b-101">Stellt die Eigenschaftensammlung für einen <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="2c57b-101">Represents the property bag for a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessageProperty ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2c57b-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2c57b-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-103">Ruft ab oder legt den Typ des Inhalts fest.</span><span class="sxs-lookup"><span data-stu-id="2c57b-103">Gets or sets the type of the content.</span></span></summary>
        <value><span data-ttu-id="2c57b-104">Der Typ des Inhalts des Nachrichtentexts.</span><span class="sxs-lookup"><span data-stu-id="2c57b-104">The type of the content of the message body.</span></span> <span data-ttu-id="2c57b-105">Dies ist ein Content-Type-Bezeichner von Sender und Empfänger für anwendungsspezifische Logik verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="2c57b-105">This is a content type identifier utilized by the sender and receiver for application specific logic.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-106">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-106">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-107">Ruft ab oder legt den Bezeichner der Korrelation.</span><span class="sxs-lookup"><span data-stu-id="2c57b-107">Gets or sets the identifier of the correlation.</span></span></summary>
        <value><span data-ttu-id="2c57b-108">Die Korrelations-ID ein.</span><span class="sxs-lookup"><span data-stu-id="2c57b-108">The correlation identifier.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-109">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-109">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-110">Ruft die Anzahl der Lieferungen, die vorgenommen wurden, diese Nachricht zuzustellen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-110">Gets the number of deliveries that have been made to deliver this message.</span></span></summary>
        <value><span data-ttu-id="2c57b-111">Die Anzahl der Übermittlungen, die vorgenommen wurden, diese Nachricht zuzustellen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-111">The number of deliveries that have been made to deliver this message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-112">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-112">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2c57b-113">Wenn die Nachricht vom Service Bus nicht zugestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="2c57b-113">If the message has not been delivered by ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-114">Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="2c57b-114">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="2c57b-115">Die in die Warteschlange einzureihen Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="2c57b-115">The enqueue time in UTC.</span></span> <span data-ttu-id="2c57b-116">Dieser Wert stellt die tatsächliche Zeit des einreihen der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="2c57b-116">This value represents the actual time of enqueuing the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-117">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-117">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-118">Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="2c57b-118">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="2c57b-119">Die Nachricht Ablaufzeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="2c57b-119">The message expiration time in UTC.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-120">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-120">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-121">Ruft ab oder legt fest, ob die Persistenz für diese Eigenschaft zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-121">Gets or sets whether to force persistence on this property.</span></span></summary>
        <value><span data-ttu-id="2c57b-122">"true", um Persistenz für diese Eigenschaft zu erzwingen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="2c57b-122">true to force persistence on this property; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-123">Ruft ab oder legt die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="2c57b-123">Gets or sets the application specific label.</span></span></summary>
        <value><span data-ttu-id="2c57b-124">Die anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="2c57b-124">The application specific label.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-125">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-125">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-126">Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="2c57b-126">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="2c57b-127">Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</span><span class="sxs-lookup"><span data-stu-id="2c57b-127">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-128">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-128">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2c57b-129">Wenn die Nachricht aus der Service Bus nicht empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="2c57b-129">If the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-130">Ruft das Sperrtoken der Nachricht vom Servicebus zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-130">Gets the lock token assigned by Service Bus to the message.</span></span></summary>
        <value><span data-ttu-id="2c57b-131">Das Sperrtoken der Nachricht vom Servicebus zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="2c57b-131">The lock token assigned by Service Bus to the message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-132">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-132">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2c57b-133">Wenn die Nachricht aus der Service Bus nicht empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="2c57b-133">If the message was not received from the ServiceBus.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-134">Ruft die vermittelte Nachricht ab.</span><span class="sxs-lookup"><span data-stu-id="2c57b-134">Gets the brokered message.</span></span></summary>
        <value><span data-ttu-id="2c57b-135">Das Objekt für vermittelte Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="2c57b-135">The brokered message object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-136">Ruft ab oder legt den Bezeichner der Nachricht fest.</span><span class="sxs-lookup"><span data-stu-id="2c57b-136">Gets or sets the identifier of the message.</span></span></summary>
        <value><span data-ttu-id="2c57b-137">Der Meldungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="2c57b-137">The message identifier.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-138">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-138">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="2c57b-139">Wenn die Nachrichten-ID ist null oder mehr als 128 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="2c57b-139">If message identifier is null or exceeds 128 characters in length.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public static readonly string Name;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Name" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Name As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Name : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2c57b-140">Der Name, die zum Anwenden der Eigenschaftensammlung verwendet eine <see cref="T:System.ServiceModel.Channels.Message" /> beim Senden einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="2c57b-140">The name used for applying the property bag to a <see cref="T:System.ServiceModel.Channels.Message" /> when sending a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-141">Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer transaktionalen Nachricht an eine Warteschlange oder ein Thema, das nicht für Sitzungen aktivierte ist.</span><span class="sxs-lookup"><span data-stu-id="2c57b-141">Gets or sets a partition key for sending a transactional message to a queue or topic that is not session-aware.</span></span></summary>
        <value><span data-ttu-id="2c57b-142">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2c57b-142">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-143">Ruft die Eigenschaften für vermittelte Nachrichten ab.</span><span class="sxs-lookup"><span data-stu-id="2c57b-143">Gets the properties of the brokered message.</span></span></summary>
        <value><span data-ttu-id="2c57b-144">Die Eigenschaften für vermittelte Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="2c57b-144">The properties of the brokered message.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-145">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-145">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-146">Ruft ab oder legt die Adresse der Warteschlange, an die geantwortet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-146">Gets or sets the address of the queue to reply to.</span></span></summary>
        <value><span data-ttu-id="2c57b-147">Die Antwort auf die Adresse.</span><span class="sxs-lookup"><span data-stu-id="2c57b-147">The reply to queue address.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-148">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-148">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-149">Ermittelt oder definiert die Sitzungs-ID, um zu antworten.</span><span class="sxs-lookup"><span data-stu-id="2c57b-149">Gets or sets the session identifier to reply to.</span></span></summary>
        <value><span data-ttu-id="2c57b-150">Die Sitzungs-ID, an die geantwortet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2c57b-150">The session identifier to reply to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-151">Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden.</span><span class="sxs-lookup"><span data-stu-id="2c57b-151">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span></summary>
        <value><span data-ttu-id="2c57b-152">Die geplante Enqueue-Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="2c57b-152">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="2c57b-153">Dieser Wert ist für das verzögerte zu nachrichtensenden.</span><span class="sxs-lookup"><span data-stu-id="2c57b-153">This value is for delayed message sending.</span></span> <span data-ttu-id="2c57b-154">Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</span><span class="sxs-lookup"><span data-stu-id="2c57b-154">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-155">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-155">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="2c57b-156">Wenn der übergebene Wert DateTime.MaxValue ist.</span><span class="sxs-lookup"><span data-stu-id="2c57b-156">If the passed in value is DateTime.MaxValue.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-157">Ruft die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-157">Gets the unique number assigned to a message by the Service Bus.</span></span></summary>
        <value><span data-ttu-id="2c57b-158">Die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen wird.</span><span class="sxs-lookup"><span data-stu-id="2c57b-158">The unique number assigned to a message by the Service Bus.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-159">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-159">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="2c57b-160">Wenn die Nachricht nicht aus dem e-Mail-Server empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="2c57b-160">If the message was not received from the message server.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-161">Ruft ab oder legt den Bezeichner der Sitzung fest.</span><span class="sxs-lookup"><span data-stu-id="2c57b-161">Gets or sets the identifier of the session.</span></span></summary>
        <value><span data-ttu-id="2c57b-162">Der Bezeichner der Sitzung.</span><span class="sxs-lookup"><span data-stu-id="2c57b-162">The identifier of the session.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-163">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-163">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IMessageProperty.CreateCopy">
      <MemberSignature Language="C#" Value="System.ServiceModel.Channels.IMessageProperty IMessageProperty.CreateCopy ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.ServiceModel.Channels.IMessageProperty System.ServiceModel.Channels.IMessageProperty.CreateCopy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.System#ServiceModel#Channels#IMessageProperty#CreateCopy" />
      <MemberSignature Language="VB.NET" Value="Function CreateCopy () As IMessageProperty Implements IMessageProperty.CreateCopy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.IMessageProperty.CreateCopy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IMessageProperty</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-164">Ruft ab oder legt die Nachricht TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="2c57b-164">Gets or sets the message’s time to live value.</span></span> <span data-ttu-id="2c57b-165">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht abläuft, beginnend ab dem ab beim Senden der Nachricht an den Dienst Bus.Messages älter ist als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="2c57b-165">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="2c57b-166">Abonnenten werden können abgelaufene Nachrichten empfangen.</span><span class="sxs-lookup"><span data-stu-id="2c57b-166">Subscribers will be unable to receive expired messages.</span></span></summary>
        <value><span data-ttu-id="2c57b-167">Die Nachricht Gültigkeitsdauerwert.</span><span class="sxs-lookup"><span data-stu-id="2c57b-167">The message’s time to live value.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-168">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-168">If the message is in disposed state.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="2c57b-169">Wenn der übergebene Wert kleiner oder gleich TimeSpan.Zero.</span><span class="sxs-lookup"><span data-stu-id="2c57b-169">If the passed in value is less than or equal to TimeSpan.Zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-170">Ruft ab, oder legt senden zu Adresse.</span><span class="sxs-lookup"><span data-stu-id="2c57b-170">Gets or sets the send to address.</span></span></summary>
        <value><span data-ttu-id="2c57b-171">Die Adresse der Zielwarteschlange.</span><span class="sxs-lookup"><span data-stu-id="2c57b-171">The address of the destination queue.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="2c57b-172">Wenn die Nachricht im freigegebenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="2c57b-172">If the message is in disposed state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2c57b-173">Ruft ab oder legt einen Wert für den Partitionsschlüssel wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2c57b-173">Gets or sets a partition key value when a transaction is to be used to send messages via a transfer queue.</span></span></summary>
        <value><span data-ttu-id="2c57b-174">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="2c57b-174">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>