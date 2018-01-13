<Type Name="EventData" FullName="Microsoft.ServiceBus.Messaging.EventData">
  <TypeSignature Language="C#" Value="public sealed class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventData" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="31718-101">Stellt das Ereignis gesendet und empfangen, die aus einem Datenstrom Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="31718-101">Represents the event sent and received from an Event Hubs stream.</span></span> <span data-ttu-id="31718-102">Es enthält den Text des Ereignisses, einen benutzerdefinierten Eigenschaftenbehälter sowie verschiedene Metadaten, die Beschreibung des Ereignisses, z. B. der Offset in der Partition und die Nummer in der datenstromsequenz.</span><span class="sxs-lookup"><span data-stu-id="31718-102">It contains the body of the event, a user-defined property bag, and various metadata describing the event, such as its offset in the partition and its number in the stream sequence.</span></span> <span data-ttu-id="31718-103">Partitionen werden mit einer Sequenz von Ereignisdaten gefüllt.</span><span class="sxs-lookup"><span data-stu-id="31718-103">Partitions are filled with a sequence of event data.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="31718-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31718-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : byte[] -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray"><span data-ttu-id="31718-105">Das Ereignis Daten Bytearray, das verwendet wird, um den Antworttext-Datenstrom zu bilden.</span><span class="sxs-lookup"><span data-stu-id="31718-105">The event data byte array which is used to form the body stream.</span></span></param>
        <summary><span data-ttu-id="31718-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die das angegebene Bytearray als Text verwendet.</span><span class="sxs-lookup"><span data-stu-id="31718-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the specified byte array as the body.</span></span></summary>
        <remarks><span data-ttu-id="31718-107">Wenn EventData senden, sollten Sie Eingabebytearrays als unveränderlich behandeln.</span><span class="sxs-lookup"><span data-stu-id="31718-107">You should treat the input byte array as immutable when sending EventData.</span></span> 
            
            <span data-ttu-id="31718-108">Beim Senden von Daten als auch alle Klonvorgang wird Service Bus dem Bytearray Verweis stattdessen, die tiefe Kopie des Byte-Arrays zugreifen, indem.</span><span class="sxs-lookup"><span data-stu-id="31718-108">When sending the data as well as any cloning operation, Service Bus will access the byte array by reference rather that by deep copy of the byte array.</span></span> <span data-ttu-id="31718-109">Auch löschen, mit der EventData-Instanz wird nur die Zuordnung mit dem Array dereferenzieren.</span><span class="sxs-lookup"><span data-stu-id="31718-109">Also disposing the EventData instance will only de-reference the association with the array.</span></span> <span data-ttu-id="31718-110">Der Benutzer ist verantwortlich für den Lebenszyklus des Bytearrays selbst.</span><span class="sxs-lookup"><span data-stu-id="31718-110">The user is responsible for the lifecycle of the byte-array itself.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; arraySegments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; arraySegments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Collections.Generic.IList{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegments As IList(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData arraySegments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegments" Type="System.Collections.Generic.IList&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegments"><span data-ttu-id="31718-111">IList der Array-Segmente als Text an den <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="31718-111">An IList of array segments to be sent as the body of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</span></span>
            </param>
        <summary><span data-ttu-id="31718-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die die angegebene Liste von bytearraysegmenten als Nachrichtentext verwendet.</span><span class="sxs-lookup"><span data-stu-id="31718-112">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the specified list of byte array segments as the body.</span></span></summary>
        <remarks><span data-ttu-id="31718-113">Benutzer in der Regel IList verwendet&lt;ArraySegment&lt;Byte&gt; &gt; Verwendung sein eigenes Pufferpool für Szenarien, die eine effiziente Nutzung von Arbeitsspeicher erfordern.</span><span class="sxs-lookup"><span data-stu-id="31718-113">Typically user will use IList&lt;ArraySegment&lt;byte&gt;&gt; when using there own buffer pool for scenarios that require efficient usage of memory.</span></span>
            
            <span data-ttu-id="31718-114">Beim Senden von Daten als auch alle Klonvorgang wird Service Bus die Array-Segmente Verweis stattdessen, die tiefe Kopie der Bytes zugreifen, indem.</span><span class="sxs-lookup"><span data-stu-id="31718-114">When sending the data as well as any cloning operation, Service Bus will access the array segments by reference rather that by deep copy of the bytes.</span></span> 
            
            <span data-ttu-id="31718-115">Freigeben der EventData-Instanz wird nur die Zuordnung mit der Liste dereferenzieren.</span><span class="sxs-lookup"><span data-stu-id="31718-115">Disposing the EventData instance will only de-reference the association with the list.</span></span> <span data-ttu-id="31718-116">Benutzer ist für den Lebenszyklus der Array-Segmente selbst verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="31718-116">User is responsible for the life cycle of the array segments themselves.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="31718-117">Ein Datenstrom, der als Antworttext-Datenstrom verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="31718-117">A stream which is used as the body stream.</span></span></param>
        <summary><span data-ttu-id="31718-118">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die den Datenstrom Argument wie der Textstream verwendet.</span><span class="sxs-lookup"><span data-stu-id="31718-118">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> class that uses the argument stream as the body stream.</span></span></summary>
        <remarks><span data-ttu-id="31718-119">Benutzer muss Besitzer der Freigabe des Datenstroms für die Verwendung dieses Konstruktors.</span><span class="sxs-lookup"><span data-stu-id="31718-119">User is expected to own the disposing of the stream when using this constructor.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (object content, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object content, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData (content, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="31718-120">.NET-Objekt</span><span class="sxs-lookup"><span data-stu-id="31718-120">.Net object</span></span></param>
        <param name="serializer"><span data-ttu-id="31718-121">das Serialisierungsprogramm zur Serialisierung verwendet<paramref name="content" /></span><span class="sxs-lookup"><span data-stu-id="31718-121">the serializer used to serialize <paramref name="content" /></span></span></param>
        <summary>
            <span data-ttu-id="31718-122">Der Konstruktor nimmt Eingabe Inhalt und Serialisierungsprogramm den Antworttext-Datenstrom zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="31718-122">Constructor which takes the input content and serializer to create the body stream.</span></span>
            </summary>
        <remarks><span data-ttu-id="31718-123">Wenn Inhalt ist einen Datenstrom und Seriazlier null, ist es gleichgesetzt verwenden<see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></span><span class="sxs-lookup"><span data-stu-id="31718-123">If content is a stream and seriazlier is null, then it is equate to use <see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventData" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventData.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="31718-124">Stellt eine tiefe Kopie des Diese Ereignisdaten an.</span><span class="sxs-lookup"><span data-stu-id="31718-124">Makes a deep copy of this event data.</span></span></summary>
        <returns><span data-ttu-id="31718-125">Eine Kopie dieser Ereignisdaten.</span><span class="sxs-lookup"><span data-stu-id="31718-125">A copy of this event data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="31718-126">Führt anwendungsspezifische Aufgaben durch, die mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zusammenhängen.</span><span class="sxs-lookup"><span data-stu-id="31718-126">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-127">Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="31718-127">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="31718-128">Die in die Warteschlange einzureihen Zeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="31718-128">The enqueue time in UTC.</span></span> <span data-ttu-id="31718-129">Dieser Wert stellt die tatsächliche Zeit des setzen die Ereignisdaten an.</span><span class="sxs-lookup"><span data-stu-id="31718-129">This value represents the actual time of enqueuing the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="eventData.GetBodyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="31718-130">Ruft ab oder legt den zugrunde liegenden Stream auf der Ereignistext Daten fest.</span><span class="sxs-lookup"><span data-stu-id="31718-130">Gets or sets the underlying stream to the event data body.</span></span></summary>
        <returns><span data-ttu-id="31718-131">Der zugrunde liegende Stream, der dem Textteil der Ereignis-Daten.</span><span class="sxs-lookup"><span data-stu-id="31718-131">The underlying stream to the event data body.</span></span></returns>
        <remarks><span data-ttu-id="31718-132">Diese Methode kann nur einmal aufgerufen werden, und anschließend Methode löst <see cref="T:System.InvalidOperationException" />.</span><span class="sxs-lookup"><span data-stu-id="31718-132">This method can only be called once and afterwards method will throw <see cref="T:System.InvalidOperationException" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="eventData.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="31718-133">Ruft das Ereignis in Byte ab.</span><span class="sxs-lookup"><span data-stu-id="31718-133">Gets the event data bytes.</span></span></summary>
        <returns><span data-ttu-id="31718-134">Die Ereignis-Datenbytes.</span><span class="sxs-lookup"><span data-stu-id="31718-134">The event data bytes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-135">Ruft den Offset der Daten relativ zu den Event Hub-Partition-Stream ab.</span><span class="sxs-lookup"><span data-stu-id="31718-135">Gets the offset of the data relative to the Event Hub partition stream.</span></span> <span data-ttu-id="31718-136">Der Offset ist eine Marke oder einen Bezeichner für ein Ereignis innerhalb des Event Hubs-Streams.</span><span class="sxs-lookup"><span data-stu-id="31718-136">The offset is a marker or identifier for an event within the Event Hubs stream.</span></span> <span data-ttu-id="31718-137">Der Bezeichner ist eindeutig innerhalb einer Partition des Event Hubs-Streams.</span><span class="sxs-lookup"><span data-stu-id="31718-137">The identifier is unique within a partition of the Event Hubs stream.</span></span></summary>
        <value><span data-ttu-id="31718-138">Der gelesenen Offset der Daten für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="31718-138">The read offset of the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-139">Ruft ab oder legt den Schlüssel, der verwendet wird, um zu bestimmen, zu welcher Partition die Ereignisdaten gesendet.</span><span class="sxs-lookup"><span data-stu-id="31718-139">Gets or sets the key that is used to determine to which partition to send event data.</span></span></summary>
        <value><span data-ttu-id="31718-140">Der Partitionsschlüssel für die Partition mit der Daten gesendet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="31718-140">A partition key for the partition to which event data should be sent.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-141">Ruft die Eigenschaften der Daten für das Ereignis, dass der Benutzer, die ausdrücklich hinzugefügt wurden, während der Vorgänge zu senden.</span><span class="sxs-lookup"><span data-stu-id="31718-141">Gets the user properties of the event data that the user explicitly added during send operations.</span></span></summary>
        <value><span data-ttu-id="31718-142">Die Eigenschaften der Daten für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="31718-142">The user properties of the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-143">Ruft die Anzahl der logischen Reihenfolge des Ereignisses innerhalb des Streams Partition des Event Hubs ab.</span><span class="sxs-lookup"><span data-stu-id="31718-143">Gets the logical sequence number of the event within the partition stream of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="31718-144">Die Anzahl der logischen Reihenfolge des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="31718-144">The logical sequence number of the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializedSizeInBytes">
      <MemberSignature Language="C#" Value="public long SerializedSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SerializedSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializedSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SerializedSizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="31718-145">Ruft ab oder legt die Systemeigenschaften, einschließlich der Daten für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="31718-145">Gets or sets the system properties, including the event data.</span></span></summary>
        <value><span data-ttu-id="31718-146">Die Systemeigenschaften, einschließlich der Daten für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="31718-146">The system properties, including the event data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>