<Type Name="SBQueue" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBQueue">
  <TypeSignature Language="C#" Value="public class SBQueue : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBQueue extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
  <TypeSignature Language="VB.NET" Value="Public Class SBQueue&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBQueue = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d4f28-101">Beschreibung der Warteschlange für Ressource.</span><span class="sxs-lookup"><span data-stu-id="d4f28-101">Description of queue Resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-102">Initialisiert eine neue Instanz der SBQueue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4f28-102">Initializes a new instance of the SBQueue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue (string id = null, string name = null, string type = null, Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Nullable&lt;DateTime&gt; accessedAt = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;long&gt; messageCount = null, Nullable&lt;TimeSpan&gt; lockDuration = null, Nullable&lt;int&gt; maxSizeInMegabytes = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;TimeSpan&gt; defaultMessageTimeToLive = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;TimeSpan&gt; duplicateDetectionHistoryTimeWindow = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Nullable&lt;TimeSpan&gt; autoDeleteOnIdle = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;bool&gt; enableExpress = null, string forwardTo = null, string forwardDeadLetteredMessagesTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;int64&gt; messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDuration, valuetype System.Nullable`1&lt;int32&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultMessageTimeToLive, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoDeleteOnIdle, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;bool&gt; enableExpress, string forwardTo, string forwardDeadLetteredMessagesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional countDetails As MessageCountDetails = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional messageCount As Nullable(Of Long) = null, Optional lockDuration As Nullable(Of TimeSpan) = null, Optional maxSizeInMegabytes As Nullable(Of Integer) = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional defaultMessageTimeToLive As Nullable(Of TimeSpan) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional duplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional status As Nullable(Of EntityStatus) = null, Optional autoDeleteOnIdle As Nullable(Of TimeSpan) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null, Optional forwardTo As String = null, Optional forwardDeadLetteredMessagesTo As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue : string * string * string * Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBQueue" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue (id, name, type, countDetails, createdAt, updatedAt, accessedAt, sizeInBytes, messageCount, lockDuration, maxSizeInMegabytes, requiresDuplicateDetection, requiresSession, defaultMessageTimeToLive, deadLetteringOnMessageExpiration, duplicateDetectionHistoryTimeWindow, maxDeliveryCount, status, autoDeleteOnIdle, enablePartitioning, enableExpress, forwardTo, forwardDeadLetteredMessagesTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="lockDuration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forwardTo" Type="System.String" />
        <Parameter Name="forwardDeadLetteredMessagesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d4f28-103">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="d4f28-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="d4f28-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="d4f28-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="d4f28-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="d4f28-105">Resource type</span></span></param>
        <param name="countDetails"><span data-ttu-id="d4f28-106">Details zur Nachrichtenanzahl.</span><span class="sxs-lookup"><span data-stu-id="d4f28-106">Message Count Details.</span></span></param>
        <param name="createdAt"><span data-ttu-id="d4f28-107">Die genaue Uhrzeit der Erstellung der Nachrichteninhalts.</span><span class="sxs-lookup"><span data-stu-id="d4f28-107">The exact time the message was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="d4f28-108">Die genaue Uhrzeit wurde die Nachricht aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d4f28-108">The exact time the message was updated.</span></span></param>
        <param name="accessedAt"><span data-ttu-id="d4f28-109">Letzte Uhrzeit, an eine Nachricht gesendet wurde, bzw. des letzten gab es eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d4f28-109">Last time a message was sent, or the last time there was a receive request to this queue.</span></span></param>
        <param name="sizeInBytes"><span data-ttu-id="d4f28-110">Die Größe der Warteschlange, in Bytes.</span><span class="sxs-lookup"><span data-stu-id="d4f28-110">The size of the queue, in bytes.</span></span></param>
        <param name="messageCount"><span data-ttu-id="d4f28-111">Die Anzahl der Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d4f28-111">The number of messages in the queue.</span></span></param>
        <param name="lockDuration"><span data-ttu-id="d4f28-112">ISO 8601 Timespan Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-112">ISO 8601 timespan duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span> <span data-ttu-id="d4f28-113">Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="d4f28-113">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span></param>
        <param name="maxSizeInMegabytes"><span data-ttu-id="d4f28-114">Die maximale Größe der Warteschlange in Megabyte an, die die Größe des Arbeitsspeichers für die Warteschlange zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-114">The maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span>
            <span data-ttu-id="d4f28-115">Standardwert ist 1024.</span><span class="sxs-lookup"><span data-stu-id="d4f28-115">Default is 1024.</span></span></param>
        <param name="requiresDuplicateDetection"><span data-ttu-id="d4f28-116">Ein Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="d4f28-116">A value indicating if this queue requires duplicate detection.</span></span></param>
        <param name="requiresSession"><span data-ttu-id="d4f28-117">Ein Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d4f28-117">A value that indicates whether the queue supports the concept of sessions.</span></span></param>
        <param name="defaultMessageTimeToLive"><span data-ttu-id="d4f28-118">ISO 8601 Standard Nachricht Timespan TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="d4f28-118">ISO 8601 default message timespan to live value.</span></span> <span data-ttu-id="d4f28-119">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft.</span><span class="sxs-lookup"><span data-stu-id="d4f28-119">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="d4f28-120">Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-120">This is the default value used when TimeToLive is not set on a message itself.</span></span></param>
        <param name="deadLetteringOnMessageExpiration"><span data-ttu-id="d4f28-121">Ein Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="d4f28-121">A value that indicates whether this queue has dead letter support when a message expires.</span></span></param>
        <param name="duplicateDetectionHistoryTimeWindow"><span data-ttu-id="d4f28-122">ISO 8601 TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="d4f28-122">ISO 8601 timeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="d4f28-123">Der Standardwert ist 10 Minuten.</span><span class="sxs-lookup"><span data-stu-id="d4f28-123">The default value is 10 minutes.</span></span></param>
        <param name="maxDeliveryCount"><span data-ttu-id="d4f28-124">Die Anzahl maximaler Zustellungen.</span><span class="sxs-lookup"><span data-stu-id="d4f28-124">The maximum delivery count.</span></span> <span data-ttu-id="d4f28-125">Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="d4f28-125">A message is automatically deadlettered after this number of deliveries.</span></span> <span data-ttu-id="d4f28-126">Standardwert ist 10.</span><span class="sxs-lookup"><span data-stu-id="d4f28-126">default value is 10.</span></span></param>
        <param name="status"><span data-ttu-id="d4f28-127">Listet die möglichen Werte für den Status einer messaging-Entität an.</span><span class="sxs-lookup"><span data-stu-id="d4f28-127">Enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="d4f28-128">Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="d4f28-128">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span></param>
        <param name="autoDeleteOnIdle"><span data-ttu-id="d4f28-129">ISO 8061 TimeSpan leerlaufintervalls nach dem die Warteschlange automatisch gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="d4f28-129">ISO 8061 timeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="d4f28-130">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="d4f28-130">The minimum duration is 5 minutes.</span></span></param>
        <param name="enablePartitioning"><span data-ttu-id="d4f28-131">Ein Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="d4f28-131">A value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span></param>
        <param name="enableExpress"><span data-ttu-id="d4f28-132">Ein Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="d4f28-132">A value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="d4f28-133">Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="d4f28-133">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span></param>
        <param name="forwardTo"><span data-ttu-id="d4f28-134">Name der Warteschlange/Thema zum Weiterleiten von Nachrichten</span><span class="sxs-lookup"><span data-stu-id="d4f28-134">Queue/Topic name to forward the messages</span></span></param>
        <param name="forwardDeadLetteredMessagesTo"><span data-ttu-id="d4f28-135">Name der Warteschlange/Thema zum Weiterleiten der Nachricht Dead Letter</span><span class="sxs-lookup"><span data-stu-id="d4f28-135">Queue/Topic name to forward the Dead Letter message</span></span></param>
        <summary>
            <span data-ttu-id="d4f28-136">Initialisiert eine neue Instanz der SBQueue-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d4f28-136">Initializes a new instance of the SBQueue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-137">Ruft die zuletzt eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="d4f28-137">Gets last time a message was sent, or the last time there was a receive request to this queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-138">Ruft ab, oder legt ihn fest ISO 8061 TimeSpan leerlaufintervalls nach dem die Warteschlange automatisch gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="d4f28-138">Gets or sets ISO 8061 timeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="d4f28-139">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="d4f28-139">The minimum duration is 5 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-140">Ruft Nachrichtendetails die Anzahl.</span><span class="sxs-lookup"><span data-stu-id="d4f28-140">Gets message Count Details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-141">Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.</span><span class="sxs-lookup"><span data-stu-id="d4f28-141">Gets the exact time the message was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deadLetteringOnMessageExpiration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-142">Ruft ab oder legt einen Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="d4f28-142">Gets or sets a value that indicates whether this queue has dead letter support when a message expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-143">Ruft ab, oder legt die ISO 8601-Standard Nachricht Timespan TTL-Wert fest.</span><span class="sxs-lookup"><span data-stu-id="d4f28-143">Gets or sets ISO 8601 default message timespan to live value.</span></span> <span data-ttu-id="d4f28-144">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft.</span><span class="sxs-lookup"><span data-stu-id="d4f28-144">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="d4f28-145">Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-145">This is the default value used when TimeToLive is not set on a message itself.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-146">Ruft ab, oder legt ihn fest ISO 8601-TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="d4f28-146">Gets or sets ISO 8601 timeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="d4f28-147">Der Standardwert ist 10 Minuten.</span><span class="sxs-lookup"><span data-stu-id="d4f28-147">The default value is 10 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableExpress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-148">Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="d4f28-148">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="d4f28-149">Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="d4f28-149">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enablePartitioning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-150">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="d4f28-150">Gets or sets a value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardDeadLetteredMessagesTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-151">Name der Warteschlange/Thema zum Weiterleiten der Nachricht Dead Letter abgerufen oder festgelegt</span><span class="sxs-lookup"><span data-stu-id="d4f28-151">Gets or sets queue/Topic name to forward the Dead Letter message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-152">Ruft ab oder legt Namen von Warteschlange/Thema zum Weiterleiten von Nachrichten</span><span class="sxs-lookup"><span data-stu-id="d4f28-152">Gets or sets queue/Topic name to forward the messages</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-153">Ruft ab oder legt die ISO-8601 Timespan Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-153">Gets or sets ISO 8601 timespan duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span>
            <span data-ttu-id="d4f28-154">Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="d4f28-154">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-155">Ruft ab oder legt die Anzahl maximaler Zustellungen.</span><span class="sxs-lookup"><span data-stu-id="d4f28-155">Gets or sets the maximum delivery count.</span></span> <span data-ttu-id="d4f28-156">Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="d4f28-156">A message is automatically deadlettered after this number of deliveries.</span></span> <span data-ttu-id="d4f28-157">Standardwert ist 10.</span><span class="sxs-lookup"><span data-stu-id="d4f28-157">default value is 10.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-158">Ruft ab oder legt die maximale Größe der Warteschlange in Megabyte an, die Größe des Arbeitsspeichers für die Warteschlange ist.</span><span class="sxs-lookup"><span data-stu-id="d4f28-158">Gets or sets the maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span> <span data-ttu-id="d4f28-159">Standardwert ist 1024.</span><span class="sxs-lookup"><span data-stu-id="d4f28-159">Default is 1024.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.messageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-160">Ruft die Anzahl der Nachrichten in der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="d4f28-160">Gets the number of messages in the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresDuplicateDetection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-161">Ruft ab oder legt einen Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="d4f28-161">Gets or sets a value indicating if this queue requires duplicate detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-162">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d4f28-162">Gets or sets a value that indicates whether the queue supports the concept of sessions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-163">Ruft die Größe der Warteschlange, in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="d4f28-163">Gets the size of the queue, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-164">Ruft ab oder legt Listet die möglichen Werte für den Status einer messaging-Entität.</span><span class="sxs-lookup"><span data-stu-id="d4f28-164">Gets or sets enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="d4f28-165">Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="d4f28-165">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d4f28-166">Ruft die genaue Uhrzeit, an die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="d4f28-166">Gets the exact time the message was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>