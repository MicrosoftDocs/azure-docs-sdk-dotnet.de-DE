<Type Name="Message" FullName="Microsoft.Azure.ServiceBus.Message">
  <TypeSignature Language="C#" Value="public class Message" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Message extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message" />
  <TypeSignature Language="VB.NET" Value="Public Class Message" />
  <TypeSignature Language="F#" Value="type Message = class" />
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
            <span data-ttu-id="7db75-101">Das Nachrichtenobjekt kommunizieren und Übertragen von Daten mit Service Bus verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-101">The message object used to communicate and transfer data with Service Bus.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="7db75-102">Die Nachrichtenstruktur wird ausführlich erläutert die <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">-Produktdokumentation.</a></span><span class="sxs-lookup"><span data-stu-id="7db75-102">The message structure is discussed in detail in the <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">product documentation.</a></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor" />
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
        <summary>
            <span data-ttu-id="7db75-103">Erstellt eine neue Nachricht</span><span class="sxs-lookup"><span data-stu-id="7db75-103">Creates a new Message</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] body);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (body As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Message : byte[] -&gt; Microsoft.Azure.ServiceBus.Message" Usage="new Microsoft.Azure.ServiceBus.Message body" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="array" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="body"><span data-ttu-id="7db75-104">Die Nutzlast der Nachricht in bytes</span><span class="sxs-lookup"><span data-stu-id="7db75-104">The payload of the message in bytes</span></span></param>
        <summary>
            <span data-ttu-id="7db75-105">Erstellt eine neue Nachricht aus der angegebenen Nutzlast an.</span><span class="sxs-lookup"><span data-stu-id="7db75-105">Creates a new message from the specified payload.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public byte[] Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As Byte()" />
      <MemberSignature Language="F#" Value="member this.Body : byte[] with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7db75-106">Ruft den Nachrichtentext ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="7db75-106">Gets or sets the body of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7db75-107">Die einfachste Möglichkeit zum Erstellen einer neuen Nachricht aus einer Zeichenfolge lautet wie folgt:</span><span class="sxs-lookup"><span data-stu-id="7db75-107">The easiest way to create a new message from a string is the following:</span></span>
            <code>
            message.Body = System.Text.Encoding.UTF8.GetBytes("Message1");
            </code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.ServiceBus.Message Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Message" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.ServiceBus.Message" Usage="message.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7db75-108">Klont eine Nachricht an, damit, dass es möglich ist, einen Klon einer bereits empfangene Nachricht als eine neue Nachricht zu senden.</span><span class="sxs-lookup"><span data-stu-id="7db75-108">Clones a message, so that it is possible to send a clone of an already received message as a new message.</span></span> <span data-ttu-id="7db75-109">Die Systemeigenschaften der ursprünglichen Nachricht werden nicht kopiert.</span><span class="sxs-lookup"><span data-stu-id="7db75-109">The system properties of original message are not copied.</span></span></summary>
        <returns><span data-ttu-id="7db75-110">Eine geklonte <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span><span class="sxs-lookup"><span data-stu-id="7db75-110">A cloned <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ContentType" />
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
        <summary><span data-ttu-id="7db75-111">Ermittelt oder definiert den Inhalt von diesem Gebiet vorkommenden Deskriptor.</span><span class="sxs-lookup"><span data-stu-id="7db75-111">Gets or sets the content tpye descriptor.</span></span></summary>
        <value><span data-ttu-id="7db75-112">RFC2045 Content-Type-Deskriptor.</span><span class="sxs-lookup"><span data-stu-id="7db75-112">RFC2045 Content-Type descriptor.</span></span></value>
        <remarks>
              <span data-ttu-id="7db75-113">Beschreibt das optional die Nutzlast der Nachricht, mit der ein Deskriptor, befolgen das Format der RFC2045, Abschnitt 5, z. B. "Application/Json".</span><span class="sxs-lookup"><span data-stu-id="7db75-113">Optionally describes the payload of the message, with a descriptor following the format of RFC2045, Section 5, for example "application/json".</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.CorrelationId" />
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
        <summary><span data-ttu-id="7db75-114">Ruft ab oder legt die Korrelations-ID.</span><span class="sxs-lookup"><span data-stu-id="7db75-114">Gets or sets the a correlation identifier.</span></span></summary>
        <value><span data-ttu-id="7db75-115">Korrelations-ID.</span><span class="sxs-lookup"><span data-stu-id="7db75-115">Correlation identifier.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-116">Ermöglicht einer Anwendung an einen Kontext für die Nachricht für die Zwecke der Korrelation, z. B. reflektieren die Nachrichten-ID einer Nachricht, die beantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-116">Allows an application to specify a context for the message for the purposes of correlation, for example reflecting the MessageId of a message that is being replied to.</span></span>
               <span data-ttu-id="7db75-117">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a>.</span><span class="sxs-lookup"><span data-stu-id="7db75-117">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterErrorDescriptionHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterErrorDescriptionHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterErrorDescriptionHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterErrorDescriptionHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="7db75-118">Ein Schlüssel für Benutzer, die detaillierte fehlerbeschreibung darstellt, wenn eine Nachricht aus einer Entität eine Unterwarteschlange für unzustellbare Nachrichten empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-118">User property key representing detailed error description, when a message is received from a deadletter subqueue of an entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterReasonHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterReasonHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterReasonHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterReasonHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterReasonHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="7db75-119">Schlüssel für Benutzer, die für unzustellbare Nachrichten Grund darstellt, wenn eine Nachricht aus einer Entität eine Unterwarteschlange für unzustellbare Nachrichten empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-119">User property key representing deadletter reason, when a message is received from a deadletter subqueue of an entity.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
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
        <summary><span data-ttu-id="7db75-120">Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="7db75-120">Gets the date and time in UTC at which the message is set to expire.</span></span></summary>
        <value><span data-ttu-id="7db75-121">Die Nachricht Ablaufzeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="7db75-121">The message expiration time in UTC.</span></span> <span data-ttu-id="7db75-122">Diese Eigenschaft ist schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="7db75-122">This property is read-only.</span></span></value>
        <remarks>
             <span data-ttu-id="7db75-123">Der UTC-Moment, in dem die Nachricht zum Entfernen markiert wird und wegen Ablaufs nicht mehr von der Entität abgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="7db75-123">The UTC instant at which the message is marked for removal and no longer available for retrieval from the entity due to expiration.</span></span> <span data-ttu-id="7db75-124">Ablauf wird gesteuert, indem die <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> und dieser Eigenschaft wird von berechnet.<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></span><span class="sxs-lookup"><span data-stu-id="7db75-124">Expiry is controlled by the <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> property and this property is computed from <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="7db75-125">Wenn die Nachricht nicht empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="7db75-125">If the message has not been received.</span></span> <span data-ttu-id="7db75-126">Für das Beispiel wurde jedoch keine neue Nachricht erstellt noch gesendet und empfangen.</span><span class="sxs-lookup"><span data-stu-id="7db75-126">For example if a new message was created but not yet sent and received.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Label" />
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
        <summary><span data-ttu-id="7db75-127">Ruft ab oder legt eine anwendungsspezifische Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="7db75-127">Gets or sets an application specific label.</span></span></summary>
        <value><span data-ttu-id="7db75-128">Die anwendungsspezifische Bezeichnung</span><span class="sxs-lookup"><span data-stu-id="7db75-128">The application specific label</span></span></value>
        <remarks>
              <span data-ttu-id="7db75-129">Diese Eigenschaft ermöglicht der Anwendung, dem Empfänger auf standardisierte Weise den Zweck der Nachricht anzuzeigen, ähnlich einer Betreffzeile für E-Mails.</span><span class="sxs-lookup"><span data-stu-id="7db75-129">This property enables the application to indicate the purpose of the message to the receiver in a standardized fashion, similar to an email subject line.</span></span> <span data-ttu-id="7db75-130">Die zugeordnete AMQP-Eigenschaft ist "Betreff".</span><span class="sxs-lookup"><span data-stu-id="7db75-130">The mapped AMQP property is "subject".</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.MessageId" />
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
            <span data-ttu-id="7db75-131">Ruft ab oder legt die Nachrichten-ID zur Identifizierung der Nachrichteninhalts.</span><span class="sxs-lookup"><span data-stu-id="7db75-131">Gets or sets the MessageId to identify the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
               <span data-ttu-id="7db75-132">Der Nachrichtenbezeichner ist ein von der Anwendung definierter Wert, der die Nachricht und ihre Nutzlast eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="7db75-132">The message identifier is an application-defined value that uniquely identifies the message and its payload.</span></span> <span data-ttu-id="7db75-133">Der Bezeichner ist eine Zeichenfolge in freier Form und kann eine GUID oder einen aus dem Anwendungskontext abgeleiteten Bezeichner widerspiegeln.</span><span class="sxs-lookup"><span data-stu-id="7db75-133">The identifier is a free-form string and can reflect a GUID or an identifier derived from the application context.</span></span> <span data-ttu-id="7db75-134">Wenn aktiviert, die <a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">duplikaterkennung</a> Funktion identifiziert und entfernt Sekunde und weitere Übermittlung von Nachrichten mit der gleichen MessageId.</span><span class="sxs-lookup"><span data-stu-id="7db75-134">If enabled, the <a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">duplicate detection</a> feature identifies and removes second and further submissions of messages with the same MessageId.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.PartitionKey" />
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
        <summary><span data-ttu-id="7db75-135">Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer Nachricht an eine partitionierte Entität.</span><span class="sxs-lookup"><span data-stu-id="7db75-135">Gets or sets a partition key for sending a message to a partitioned entity.</span></span></summary>
        <value><span data-ttu-id="7db75-136">der Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="7db75-136">The partition key.</span></span> <span data-ttu-id="7db75-137">Maximale Länge beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="7db75-137">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-138">Für <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">partitionierte Entitäten</a> ermöglicht das Festlegen dieses Werts, verwandte Nachrichten derselben internen Partition zuzuweisen, sodass die Reihenfolge der Übermittlung ordnungsgemäß aufgezeichnet wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-138">For <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">partitioned entities</a>, setting this value enables assigning related messages to the same internal partition, so that submission sequence order is correctly recorded.</span></span> <span data-ttu-id="7db75-139">Die Partition wird von einer Hashfunktion über diesen Wert ausgewählt und kann nicht direkt ausgewählt werden.</span><span class="sxs-lookup"><span data-stu-id="7db75-139">The partition is chosen by a hash function over this value and cannot be chosen directly.</span></span> <span data-ttu-id="7db75-140">Für Sitzungen aktivierte Entitäten die <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> Eigenschaft überschreibt diesen Wert.</span><span class="sxs-lookup"><span data-stu-id="7db75-140">For session-aware entities, the <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> property overrides this value.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyTo" />
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
        <summary><span data-ttu-id="7db75-141">Ruft ab oder legt die Adresse einer Entität zum Senden von Antworten an.</span><span class="sxs-lookup"><span data-stu-id="7db75-141">Gets or sets the address of an entity to send replies to.</span></span></summary>
        <value><span data-ttu-id="7db75-142">Die Antwortadresse für die Entität.</span><span class="sxs-lookup"><span data-stu-id="7db75-142">The reply entity address.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-143">Dieser optionale und von der Anwendung definierte Wert ist eine Standardmethode, einen Antwortpfad zum Empfänger der Nachricht auszudrücken.</span><span class="sxs-lookup"><span data-stu-id="7db75-143">This optional and application-defined value is a standard way to express a reply path to the receiver of the message.</span></span> <span data-ttu-id="7db75-144">Wenn ein Absender eine Antwort erwartet, legt er den Wert auf den absoluten oder relativen Pfad der Warteschlange oder des Themas fest, an den bzw. das die Antwort gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="7db75-144">When a sender expects a reply, it sets the value to the absolute or relative path of the queue or topic it expects the reply to be sent to.</span></span>
               <span data-ttu-id="7db75-145">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a>.</span><span class="sxs-lookup"><span data-stu-id="7db75-145">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
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
        <summary><span data-ttu-id="7db75-146">Ruft ab oder legt sie fest, eine Sitzung Bezeichner erweitern die <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" /> Adresse.</span><span class="sxs-lookup"><span data-stu-id="7db75-146">Gets or sets a session identifier augmenting the <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" /> address.</span></span></summary>
        <value><span data-ttu-id="7db75-147">Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="7db75-147">Session identifier.</span></span> <span data-ttu-id="7db75-148">Maximale Länge beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="7db75-148">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-149">Dieser Wert die ReplyTo-Informationen ergänzt und gibt an, welche die "SessionId" für die Antwort beim Senden an die Antwort-Entität festgelegt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7db75-149">This value augments the ReplyTo information and specifies which SessionId should be set for the reply when sent to the reply entity.</span></span> <span data-ttu-id="7db75-150">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a></span><span class="sxs-lookup"><span data-stu-id="7db75-150">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Message Routing and Correlation</a></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
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
        <summary><span data-ttu-id="7db75-151">Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden.</span><span class="sxs-lookup"><span data-stu-id="7db75-151">Gets or sets the date and time in UTC at which the message will be enqueued.</span></span> <span data-ttu-id="7db75-152">Diese Eigenschaft gibt die Zeit in UTC; Wenn die Eigenschaft festlegen, muss der angegebene DateTime-Wert auch in UTC.</span><span class="sxs-lookup"><span data-stu-id="7db75-152">This property returns the time in UTC; when setting the property, the supplied DateTime value must also be in UTC.</span></span></summary>
        <value><span data-ttu-id="7db75-153">Die geplante Enqueue-Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="7db75-153">The scheduled enqueue time in UTC.</span></span> <span data-ttu-id="7db75-154">Dieser Wert ist für das verzögerte zu nachrichtensenden.</span><span class="sxs-lookup"><span data-stu-id="7db75-154">This value is for delayed message sending.</span></span>
            <span data-ttu-id="7db75-155">Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</span><span class="sxs-lookup"><span data-stu-id="7db75-155">It is utilized to delay messages sending to a specific time in the future.</span></span></value>
        <remarks> <span data-ttu-id="7db75-156">Zeitpunkt der einreihen bedeutet nicht, dass die Nachricht zur gleichen Zeit gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="7db75-156">Message enqueuing time does not mean that the message will be sent at the same time.</span></span> <span data-ttu-id="7db75-157">Erhalten sie in die Warteschlange eingereiht, aber tatsächliche sendende erforderliche Zeit hängt von der Warteschlange arbeitsauslastung und den Zustand.</span><span class="sxs-lookup"><span data-stu-id="7db75-157">It will get enqueued, but the actual sending time depends on the queue's workload and its state.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.SessionId" />
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
        <summary><span data-ttu-id="7db75-158">Ermittelt oder definiert die Sitzungs-ID für einen sitzungsfähigen Entität.</span><span class="sxs-lookup"><span data-stu-id="7db75-158">Gets or sets the session identifier for a session-aware entity.</span></span></summary>
        <value><span data-ttu-id="7db75-159">Die Sitzungs-ID.</span><span class="sxs-lookup"><span data-stu-id="7db75-159">The session identifier.</span></span> <span data-ttu-id="7db75-160">Maximale Länge beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="7db75-160">Maximum length is 128 characters.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-161">Bei sitzungsabhängigen Entitäten gibt dieser von der Anwendung definierte Wert die Sitzungszugehörigkeit der Nachricht an.</span><span class="sxs-lookup"><span data-stu-id="7db75-161">For session-aware entities, this application-defined value specifies the session affiliation of the message.</span></span> <span data-ttu-id="7db75-162">Nachrichten mit demselben Sitzungsbezeichner unterliegen einer zusammenfassenden Sperre und ermöglichen eine Verarbeitung in exakter Reihenfolge und Demultiplexing.</span><span class="sxs-lookup"><span data-stu-id="7db75-162">Messages with the same session identifier are subject to summary locking and enable exact in-order processing and demultiplexing.</span></span> <span data-ttu-id="7db75-163">Bei nicht sitzungsabhängigen Entitäten wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="7db75-163">For session-unaware entities, this value is ignored.</span></span>
               <span data-ttu-id="7db75-164">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">Nachricht Sitzungen</a>.</span><span class="sxs-lookup"><span data-stu-id="7db75-164">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">Message Sessions</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.Azure.ServiceBus.Message.Size" />
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
        <summary>
            <span data-ttu-id="7db75-165">Ruft die Gesamtgröße des Nachrichtentexts in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="7db75-165">Gets the total size of the message body in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.Message/SystemPropertiesCollection SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As Message.SystemPropertiesCollection" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" Usage="Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7db75-166">Ruft die <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />, dient zum Speichern von Eigenschaften, die vom System festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="7db75-166">Gets the <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />, which is used to store properties that are set by the system.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7db75-167">Ruft ab oder legt die Nachricht "time to live" Wert.</span><span class="sxs-lookup"><span data-stu-id="7db75-167">Gets or sets the message’s "time to live" value.</span></span> 
            </summary>
        <value><span data-ttu-id="7db75-168">Die Nachricht Gültigkeitsdauerwert.</span><span class="sxs-lookup"><span data-stu-id="7db75-168">The message’s time to live value.</span></span></value>
        <remarks>
                <span data-ttu-id="7db75-169">Dieser Wert ist die relative Dauer, die nach dem die Nachricht abläuft, beginnend mit den Zeitpunkt der Nachrichteninhalts akzeptiert und durch den Broker gespeichert werden, da in erfasst wurde <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />.</span><span class="sxs-lookup"><span data-stu-id="7db75-169">This value is the relative duration after which the message expires, starting from the instant the message has been accepted and stored by the broker, as captured in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />.</span></span> <span data-ttu-id="7db75-170">Wenn nicht explizit festlegen, wird der angenommene Wert der DefaultTimeToLive für den betreffenden Warteschlange oder ein Thema.</span><span class="sxs-lookup"><span data-stu-id="7db75-170">When not set explicitly, the assumed value is the DefaultTimeToLive for the respective queue or topic.</span></span> <span data-ttu-id="7db75-171">Eine auf Nachrichtenebene <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> Wert darf nicht länger als die Entität DefaultTimeToLive-Einstellung, und es wird automatisch angepasst, wenn dies der Fall ist.</span><span class="sxs-lookup"><span data-stu-id="7db75-171">A message-level <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> value cannot be longer than the entity's DefaultTimeToLive setting and it is silently adjusted if it does.</span></span> <span data-ttu-id="7db75-172">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">Ablauf</a></span><span class="sxs-lookup"><span data-stu-id="7db75-172">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">Expiration</a></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.To" />
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
        <summary><span data-ttu-id="7db75-173">Ruft ab oder legt die Adresse "zu" fest.</span><span class="sxs-lookup"><span data-stu-id="7db75-173">Gets or sets the "to" address.</span></span></summary>
        <value><span data-ttu-id="7db75-174">Die Adresse "to".</span><span class="sxs-lookup"><span data-stu-id="7db75-174">The "to" address.</span></span></value>
        <remarks>
               <span data-ttu-id="7db75-175">Diese Eigenschaft ist für die künftige Verwendung in Routingszenarien reserviert und wird derzeit vom Broker selbst ignoriert.</span><span class="sxs-lookup"><span data-stu-id="7db75-175">This property is reserved for future use in routing scenarios and presently ignored by the broker itself.</span></span> <span data-ttu-id="7db75-176">Clientanwendungen können diesen Wert verwenden, in der Regel gesteuerte <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">Auto-vorwärtsverkettungs</a> Szenarien an, dass das vorgesehene logische Ziel der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="7db75-176">Applications can use this value in rule-driven <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">auto-forward chaining</a> scenarios to indicate the intended logical destination of the message.</span></span>
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="message.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7db75-177">Gibt eine Zeichenfolge, die die aktuelle Nachricht darstellt.</span><span class="sxs-lookup"><span data-stu-id="7db75-177">Returns a string that represents the current message.</span></span></summary>
        <returns><span data-ttu-id="7db75-178">Die Zeichenfolgendarstellung der aktuellen Nachricht.</span><span class="sxs-lookup"><span data-stu-id="7db75-178">The string representation of the current message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; UserProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; UserProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.UserProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7db75-179">Ruft die Sammlung "Benutzereigenschaften", die für die benutzerdefinierte Meldung Metadaten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="7db75-179">Gets the "user properties" bag, which can be used for custom message metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7db75-180">Nur nach Wert Typen werden unterstützt: Byte, Sbyte, Char, Short, Ushort, Int, "uint", long, Ulong, Float, double, Decimal, Bool, Guid, Zeichenfolge, Uri, "DateTime", "DateTimeOffset", TimeSpan, Stream, Byte [] und IList / IDictionary von unterstützte Typen</span><span class="sxs-lookup"><span data-stu-id="7db75-180">Only following value types are supported: byte, sbyte, char, short, ushort, int, uint, long, ulong, float, double, decimal, bool, Guid, string, Uri, DateTime, DateTimeOffset, TimeSpan, Stream, byte[], and IList / IDictionary of supported types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
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
        <summary><span data-ttu-id="7db75-181">Ermittelt oder definiert einen Partitionsschlüssel zum Senden einer Nachricht in eine Entität über eine partitionierte Übertragungswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="7db75-181">Gets or sets a partition key for sending a message into an entity via a partitioned transfer queue.</span></span></summary>
        <value><span data-ttu-id="7db75-182">der Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="7db75-182">The partition key.</span></span> <span data-ttu-id="7db75-183">Maximale Länge beträgt 128 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="7db75-183">Maximum length is 128 characters.</span></span> </value>
        <remarks>
               <span data-ttu-id="7db75-184">Wenn über eine Übertragungswarteschlange im Rahmen einer Transaktion eine Nachricht gesendet wird, wird dieser Wert die Übertragung Warteschlange Partition ausgewählt: Dies ist funktionell gleichwertig mit <see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" /> und stellt sicher, dass Nachrichten zusammen und in Reihenfolge gespeichert sind, wie sie übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="7db75-184">If a message is sent via a transfer queue in the scope of a transaction, this value selects the transfer queue partition: This is functionally equivalent to <see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" /> and ensures that messages are kept together and in order as they are transferred.</span></span>
               <span data-ttu-id="7db75-185">Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">übertragen, und senden Sie über</a>.</span><span class="sxs-lookup"><span data-stu-id="7db75-185">See <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">Transfers and Send Via</a>.</span></span>
               </remarks>
      </Docs>
    </Member>
  </Members>
</Type>