<Type Name="QueueInner" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner">
  <TypeSignature Language="C#" Value="public class QueueInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type QueueInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="20fca-101">Beschreibung der Warteschlange für Ressource.</span><span class="sxs-lookup"><span data-stu-id="20fca-101">Description of queue Resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20fca-102">Initialisiert eine neue Instanz der QueueInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20fca-102">Initializes a new instance of the QueueInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string lockDuration = null, Nullable&lt;DateTime&gt; accessedAt = null, string autoDeleteOnIdle = null, Nullable&lt;DateTime&gt; createdAt = null, string defaultMessageTimeToLive = null, string duplicateDetectionHistoryTimeWindow = null, Nullable&lt;bool&gt; enableBatchedOperations = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;bool&gt; enableExpress = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;long&gt; maxSizeInMegabytes = null, Nullable&lt;long&gt; messageCount = null, Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status = null, Nullable&lt;bool&gt; supportOrdering = null, Nullable&lt;DateTime&gt; updatedAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string lockDuration, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, string autoDeleteOnIdle, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, string defaultMessageTimeToLive, string duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;bool&gt; enableBatchedOperations, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;bool&gt; enableExpress, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;int64&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;int64&gt; messageCount, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;bool&gt; supportOrdering, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional lockDuration As String = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional autoDeleteOnIdle As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional defaultMessageTimeToLive As String = null, Optional duplicateDetectionHistoryTimeWindow As String = null, Optional enableBatchedOperations As Nullable(Of Boolean) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional maxSizeInMegabytes As Nullable(Of Long) = null, Optional messageCount As Nullable(Of Long) = null, Optional countDetails As MessageCountDetails = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional status As Nullable(Of EntityStatus) = null, Optional supportOrdering As Nullable(Of Boolean) = null, Optional updatedAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * string * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner (location, id, name, type, tags, lockDuration, accessedAt, autoDeleteOnIdle, createdAt, defaultMessageTimeToLive, duplicateDetectionHistoryTimeWindow, enableBatchedOperations, deadLetteringOnMessageExpiration, enableExpress, enablePartitioning, maxDeliveryCount, maxSizeInMegabytes, messageCount, countDetails, requiresDuplicateDetection, requiresSession, sizeInBytes, status, supportOrdering, updatedAt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="lockDuration" Type="System.String" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.String" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.String" />
        <Parameter Name="enableBatchedOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;" />
        <Parameter Name="supportOrdering" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="lockDuration"><span data-ttu-id="20fca-103">Die Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-103">The duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span>
            <span data-ttu-id="20fca-104">Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="20fca-104">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span> <span data-ttu-id="20fca-105">Der Dienst akzeptiert ein C#-TimeSpan Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx</span><span class="sxs-lookup"><span data-stu-id="20fca-105">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx</span></span></param>
        <param name="accessedAt"><span data-ttu-id="20fca-106">Letzte Uhrzeit, an eine Nachricht gesendet wurde, bzw. des letzten gab es eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="20fca-106">Last time a message was sent, or the last time there was a receive request to this queue.</span></span></param>
        <param name="autoDeleteOnIdle"><span data-ttu-id="20fca-107">die TimeSpan-leerlaufintervalls nach dem die Warteschlange automatisch gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="20fca-107">the TimeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="20fca-108">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="20fca-108">The minimum duration is 5 minutes.</span></span> <span data-ttu-id="20fca-109">Der Dienst akzeptiert eine C#-TimeSpan-Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span><span class="sxs-lookup"><span data-stu-id="20fca-109">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span></span>
            <span data-ttu-id="20fca-110">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage.</span><span class="sxs-lookup"><span data-stu-id="20fca-110">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days.</span></span></param>
        <param name="createdAt"><span data-ttu-id="20fca-111">Die genaue Uhrzeit der Erstellung der Warteschlangenobjekts.</span><span class="sxs-lookup"><span data-stu-id="20fca-111">The exact time the Queue was created.</span></span></param>
        <param name="defaultMessageTimeToLive"><span data-ttu-id="20fca-112">Die Nachricht Standardzeit TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="20fca-112">The default message time to live value.</span></span> <span data-ttu-id="20fca-113">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft.</span><span class="sxs-lookup"><span data-stu-id="20fca-113">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="20fca-114">Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-114">This is the default value used when TimeToLive is not set on a message itself.</span></span>
            <span data-ttu-id="20fca-115">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage.</span><span class="sxs-lookup"><span data-stu-id="20fca-115">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days.</span></span> <span data-ttu-id="20fca-116">Der Dienst akzeptiert ein C#-TimeSpan Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx</span><span class="sxs-lookup"><span data-stu-id="20fca-116">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx</span></span>
            </param>
        <param name="duplicateDetectionHistoryTimeWindow"><span data-ttu-id="20fca-117">TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="20fca-117">TimeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="20fca-118">Der Standardwert ist 10 Minuten.</span><span class="sxs-lookup"><span data-stu-id="20fca-118">The default value is 10 minutes.</span></span> <span data-ttu-id="20fca-119">Der Dienst akzeptiert eine C#-TimeSpan-Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span><span class="sxs-lookup"><span data-stu-id="20fca-119">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx .</span></span>
            <span data-ttu-id="20fca-120">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage</span><span class="sxs-lookup"><span data-stu-id="20fca-120">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days</span></span></param>
        <param name="enableBatchedOperations"><span data-ttu-id="20fca-121">Ein Wert, der angibt, ob serverseitige Batchvorgänge aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="20fca-121">A value that indicates whether server-side batched operations are enabled.</span></span></param>
        <param name="deadLetteringOnMessageExpiration"><span data-ttu-id="20fca-122">Ein Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="20fca-122">A value that indicates whether this queue has dead letter support when a message expires.</span></span></param>
        <param name="enableExpress"><span data-ttu-id="20fca-123">Ein Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="20fca-123">A value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="20fca-124">Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="20fca-124">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span></param>
        <param name="enablePartitioning"><span data-ttu-id="20fca-125">Ein Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="20fca-125">A value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span></param>
        <param name="maxDeliveryCount"><span data-ttu-id="20fca-126">Die Anzahl maximaler Zustellungen.</span><span class="sxs-lookup"><span data-stu-id="20fca-126">The maximum delivery count.</span></span> <span data-ttu-id="20fca-127">Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="20fca-127">A message is automatically deadlettered after this number of deliveries.</span></span></param>
        <param name="maxSizeInMegabytes"><span data-ttu-id="20fca-128">Die maximale Größe der Warteschlange in Megabyte an, die die Größe des Arbeitsspeichers für die Warteschlange zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-128">The maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span></param>
        <param name="messageCount"><span data-ttu-id="20fca-129">Die Anzahl der Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="20fca-129">The number of messages in the queue.</span></span></param>
        <param name="countDetails">To be added.</param>
        <param name="requiresDuplicateDetection"><span data-ttu-id="20fca-130">Ein Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="20fca-130">A value indicating if this queue requires duplicate detection.</span></span></param>
        <param name="requiresSession"><span data-ttu-id="20fca-131">Ein Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="20fca-131">A value that indicates whether the queue supports the concept of sessions.</span></span></param>
        <param name="sizeInBytes"><span data-ttu-id="20fca-132">Die Größe der Warteschlange, in Bytes.</span><span class="sxs-lookup"><span data-stu-id="20fca-132">The size of the queue, in bytes.</span></span></param>
        <param name="status"><span data-ttu-id="20fca-133">Listet die möglichen Werte für den Status einer messaging-Entität an.</span><span class="sxs-lookup"><span data-stu-id="20fca-133">Enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="20fca-134">Folgende Werte sind möglich: "Active", "Erstellen", "Löschen", "Deaktiviert", "ReceiveDisabled", "Umbenennen", "Wiederherstellen", "SendDisabled", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="20fca-134">Possible values include: 'Active', 'Creating', 'Deleting', 'Disabled', 'ReceiveDisabled', 'Renaming', 'Restoring', 'SendDisabled', 'Unknown'</span></span></param>
        <param name="supportOrdering"><span data-ttu-id="20fca-135">Ein Wert, der angibt, ob die Warteschlange Sortierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="20fca-135">A value that indicates whether the queue supports ordering.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="20fca-136">Der genaue Zeitpunkt, zu die Warteschlange aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="20fca-136">The exact time the Queue was updated.</span></span></param>
        <summary>
            <span data-ttu-id="20fca-137">Initialisiert eine neue Instanz der QueueInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20fca-137">Initializes a new instance of the QueueInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-138">Ruft die zuletzt eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="20fca-138">Gets last time a message was sent, or the last time there was a receive request to this queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public string AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As String" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-139">Ruft ab oder legt das Intervall der TimeSpan im Leerlauf nach dem die Warteschlange automatisch gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="20fca-139">Gets or sets the TimeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="20fca-140">Die Mindestdauer ist fünf Minuten.</span><span class="sxs-lookup"><span data-stu-id="20fca-140">The minimum duration is 5 minutes.</span></span> <span data-ttu-id="20fca-141">Der Dienst akzeptiert eine C#-TimeSpan-Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span><span class="sxs-lookup"><span data-stu-id="20fca-141">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span></span>
            <span data-ttu-id="20fca-142">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage.</span><span class="sxs-lookup"><span data-stu-id="20fca-142">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-143">Ruft die genaue Uhrzeit, die Erstellung die Warteschlange, ab.</span><span class="sxs-lookup"><span data-stu-id="20fca-143">Gets the exact time the Queue was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-144">Ruft ab oder legt einen Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="20fca-144">Gets or sets a value that indicates whether this queue has dead letter support when a message expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public string DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As String" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-145">Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert.</span><span class="sxs-lookup"><span data-stu-id="20fca-145">Gets or sets the default message time to live value.</span></span> <span data-ttu-id="20fca-146">Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft.</span><span class="sxs-lookup"><span data-stu-id="20fca-146">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="20fca-147">Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-147">This is the default value used when TimeToLive is not set on a message itself.</span></span> <span data-ttu-id="20fca-148">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage.</span><span class="sxs-lookup"><span data-stu-id="20fca-148">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days.</span></span> <span data-ttu-id="20fca-149">Der Dienst akzeptiert ein C#-TimeSpan Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx</span><span class="sxs-lookup"><span data-stu-id="20fca-149">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public string DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As String" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-150">Ruft ab oder legt TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</span><span class="sxs-lookup"><span data-stu-id="20fca-150">Gets or sets timeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="20fca-151">Der Standardwert ist 10 Minuten.</span><span class="sxs-lookup"><span data-stu-id="20fca-151">The default value is 10 minutes.</span></span> <span data-ttu-id="20fca-152">Der Dienst akzeptiert eine C#-TimeSpan-Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx.</span><span class="sxs-lookup"><span data-stu-id="20fca-152">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx .</span></span>
            <span data-ttu-id="20fca-153">Format ist "TT. Hh und Standardwert ist dieser Eigenschaft 10675199 Tage</span><span class="sxs-lookup"><span data-stu-id="20fca-153">Format is 'DD.HH:MM:SS' and default value of this property is 10675199 days</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBatchedOperations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-154">Ruft ab oder legt einen Wert, der angibt, ob serverseitige Batchvorgänge aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="20fca-154">Gets or sets a value that indicates whether server-side batched operations are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-155">Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="20fca-155">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="20fca-156">Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="20fca-156">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-157">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="20fca-157">Gets or sets a value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public string LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As String" />
      <MemberSignature Language="F#" Value="member this.LockDuration : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-158">Ruft ab oder legt die Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-158">Gets or sets the duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span> <span data-ttu-id="20fca-159">Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="20fca-159">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span>
            <span data-ttu-id="20fca-160">Der Dienst akzeptiert ein C#-TimeSpan Standardformat für Lokalisierung Dauer https://msdn.microsoft.com/en-us/library/ee372286 (v=vs.110).aspx</span><span class="sxs-lookup"><span data-stu-id="20fca-160">The service accepts a C# Standard TimeSpan Format for loc duration https://msdn.microsoft.com/en-us/library/ee372286(v=vs.110).aspx</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-161">Ruft ab oder legt die Anzahl maximaler Zustellungen.</span><span class="sxs-lookup"><span data-stu-id="20fca-161">Gets or sets the maximum delivery count.</span></span> <span data-ttu-id="20fca-162">Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</span><span class="sxs-lookup"><span data-stu-id="20fca-162">A message is automatically deadlettered after this number of deliveries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-163">Ruft ab oder legt die maximale Größe der Warteschlange in Megabyte an, die Größe des Arbeitsspeichers für die Warteschlange ist.</span><span class="sxs-lookup"><span data-stu-id="20fca-163">Gets or sets the maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-164">Ruft die Anzahl der Nachrichten in der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="20fca-164">Gets the number of messages in the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-165">Ruft ab oder legt einen Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="20fca-165">Gets or sets a value indicating if this queue requires duplicate detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-166">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="20fca-166">Gets or sets a value that indicates whether the queue supports the concept of sessions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-167">Ruft die Größe der Warteschlange, in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="20fca-167">Gets the size of the queue, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-168">Ruft Listet die möglichen Werte für den Status einer messaging-Entität.</span><span class="sxs-lookup"><span data-stu-id="20fca-168">Gets enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="20fca-169">Folgende Werte sind möglich: "Active", "Erstellen", "Löschen", "Deaktiviert", "ReceiveDisabled", "Umbenennen", "Wiederherstellen", "SendDisabled", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="20fca-169">Possible values include: 'Active', 'Creating', 'Deleting', 'Disabled', 'ReceiveDisabled', 'Renaming', 'Restoring', 'SendDisabled', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportOrdering")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20fca-170">Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange Sortierung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="20fca-170">Gets or sets a value that indicates whether the queue supports ordering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20fca-171">Ruft die genaue Uhrzeit, an die Warteschlange aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="20fca-171">Gets the exact time the Queue was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>