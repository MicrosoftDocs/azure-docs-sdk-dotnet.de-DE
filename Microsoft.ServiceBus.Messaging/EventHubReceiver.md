<Type Name="EventHubReceiver" FullName="Microsoft.ServiceBus.Messaging.EventHubReceiver">
  <TypeSignature Language="C#" Value="public sealed class EventHubReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubReceiver = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="7a31c-101">Eine Clientklasse, die zur Verwendung in empfangen Vorgänge im Zusammenhang mit einem Event Hub-consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="7a31c-101">A client class used in receive operations related to an Event Hub consumer group.</span></span> <span data-ttu-id="7a31c-102">Stellt eine logische Empfänger-Verbindung zu einer bestimmten Event Hub-Partition in einer consumergruppe.</span><span class="sxs-lookup"><span data-stu-id="7a31c-102">Represents a logical receiver connection to a specific Event Hub partition within a consumer group.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-103">Ruft den Epoche-Wert, der verwendet wird, um die Partition des Besitzes während der Empfangsvorgang zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="7a31c-103">Gets the epoch value that is used to determine partition ownership during the receive operation.</span></span></summary>
        <value><span data-ttu-id="7a31c-104">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7a31c-104">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-105">Ruft den Pfad der Ereignis-Hub.</span><span class="sxs-lookup"><span data-stu-id="7a31c-105">Gets the event hub path.</span></span></summary>
        <value><span data-ttu-id="7a31c-106">Der Pfad für den Ereignis-Hub.</span><span class="sxs-lookup"><span data-stu-id="7a31c-106">The event hub path.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-107">Ruft den Bezeichner der Empfänger die während der Erstellung des Empfängers festgelegt wurde.</span><span class="sxs-lookup"><span data-stu-id="7a31c-107">Gets the identifier of a receiver which was set during the creation of the receiver.</span></span></summary>
        <value><span data-ttu-id="7a31c-108">Eine Zeichenfolge, die den Bezeichner darstellt, der einen Empfänger.</span><span class="sxs-lookup"><span data-stu-id="7a31c-108">A string representing the identifier of a receiver.</span></span> <span data-ttu-id="7a31c-109">Es zurück null, wenn der Bezeichner nicht festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-109">It will return null if the identifier is not set.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-110">Ruft den Namen des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="7a31c-110">Gets the name of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="7a31c-111">Der Name des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="7a31c-111">The name of the Event Hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="public bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-112">Ruft einen Wert, der angibt, ob <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält.</span><span class="sxs-lookup"><span data-stu-id="7a31c-112">Gets a value indicating whether <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="7a31c-113">Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="7a31c-113">Normally, the first event returned is the event after the starting offset.</span></span></summary>
        <value><span data-ttu-id="7a31c-114">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7a31c-114">Returns <see cref="T:System.Boolean" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubReceiver.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginOpen (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndOpen result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpen">
      <MemberSignature Language="C#" Value="protected override void OnOpen (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnOpen(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnOpen timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-115">Ruft die Partitions-ID für eine logische Partition einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="7a31c-115">Gets the partition ID for a logical partition of an Event Hub.</span></span></summary>
        <value><span data-ttu-id="7a31c-116">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="7a31c-116">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-117">Ruft ab oder legt sie fest, werden die Anzahl der Ereignisse, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert.</span><span class="sxs-lookup"><span data-stu-id="7a31c-117">Gets or sets the number of events that any receive operation will actively cache.</span></span> <span data-ttu-id="7a31c-118">Dieser Wert wird standardmäßig von geerbt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-118">By default, this value is inherited from <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</span></span> <span data-ttu-id="7a31c-119">Der Standardwert ist 300.</span><span class="sxs-lookup"><span data-stu-id="7a31c-119">The default value is 300.</span></span></summary>
        <value><span data-ttu-id="7a31c-120">Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="7a31c-120">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="7a31c-121">Änderungen an dieser Wert werden bei der nächsten verwendet Empfangsvorgang, aber dadurch die Anzahl der Ereignisse, die bereits im Cache vom Empfänger nicht beeinträchtigt wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-121">Changes to this value will be used in next receive operation, however this does not affect the number of events already cached by the receiver.</span></span> <span data-ttu-id="7a31c-122">Wenn diese Eigenschaft auf NULL-Wert wird festgelegt, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" /> auf Null.</span><span class="sxs-lookup"><span data-stu-id="7a31c-122">Setting this property to non-zero value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" /> to null.</span></span>
            <span data-ttu-id="7a31c-123">Beachten Sie, dass die Anzahl die zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</span><span class="sxs-lookup"><span data-stu-id="7a31c-123">Note that setting the count too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7a31c-124">Wird ausgelöst, wenn der Wert kleiner als der erforderliche Mindestwert von 10 ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-124">Thrown if the value is less than the minimum required value of 10.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-125">Ruft ab oder legt sie fest, werden die maximale Größe (in Bytes), insgesamt, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert.</span><span class="sxs-lookup"><span data-stu-id="7a31c-125">Gets or sets the maximum size (in bytes) in total that any receive operation will actively cache.</span></span> <span data-ttu-id="7a31c-126">Die Größe der einzelnen Ereignisdaten richtet sich nach der <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="7a31c-126">The size of each event data is determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> property.</span></span></summary>
        <value><span data-ttu-id="7a31c-127">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7a31c-127">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks><span data-ttu-id="7a31c-128">Das Größenlimit handelt es sich nicht um einen absoluten Begrenzung.</span><span class="sxs-lookup"><span data-stu-id="7a31c-128">The size limit is not an absolute limit.</span></span> <span data-ttu-id="7a31c-129">die Größe möglicherweise Anpassungsvorgang Folgendes zu einer Größe von mindestens eine Ereignisdaten wechseln.</span><span class="sxs-lookup"><span data-stu-id="7a31c-129">the size might go over by at least one event data worth of size.</span></span> <span data-ttu-id="7a31c-130">Änderungen an dieser Wert werden bei der nächsten verwendet Empfangsvorgang, aber dadurch die Anzahl der Ereignisse, die bereits im Cache vom Empfänger nicht beeinträchtigt wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-130">Changes to this value will be used in next receive operation, however this does not affect the number of events already cached by the receiver.</span></span> <span data-ttu-id="7a31c-131">Wenn diese Eigenschaft auf Null-Wert wird festgelegt, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" /> auf 0 (null).</span><span class="sxs-lookup"><span data-stu-id="7a31c-131">Setting this property to non-null value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" /> to zero.</span></span>
            <span data-ttu-id="7a31c-132">Beachten Sie, dass die Größe zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</span><span class="sxs-lookup"><span data-stu-id="7a31c-132">Note that setting the size too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7a31c-133">Wird ausgelöst, wenn die Größenwert kleiner als der erforderliche Mindestwert von 260 KB ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-133">Thrown when the size value is less than the minimum required value of 260K bytes.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive " />
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
        <summary><span data-ttu-id="7a31c-134">Empfängt Daten von Event Hubs-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="7a31c-134">Receives Event Hubs event data.</span></span></summary>
        <returns><span data-ttu-id="7a31c-135">Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> -Objekt oder null, wenn keine Ereignisdaten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-135">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> object, or null if no event data is available.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7a31c-136">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-136">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7a31c-137">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-137">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7a31c-138">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-138">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7a31c-139">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-139">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7a31c-140">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</span><span class="sxs-lookup"><span data-stu-id="7a31c-140">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <summary><span data-ttu-id="7a31c-141">Empfängt Event Hubs-Ereignisdaten, bis die angegebene Anzahl an.</span><span class="sxs-lookup"><span data-stu-id="7a31c-141">Receives Event Hubs event data, up to the specified count.</span></span></summary>
        <returns><span data-ttu-id="7a31c-142">Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung.</span><span class="sxs-lookup"><span data-stu-id="7a31c-142">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection.</span></span> <span data-ttu-id="7a31c-143">Die Auflistung ist entweder leer, wenn kein Ereignis wird innerhalb der angegebenen Zeit oder alle Ereignisse zurückgegeben, bis zu <paramref name="maxCount" /> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-143">The collection is either empty if no event is returned within the specified time, or all events up to <paramref name="maxCount" /> are returned.</span></span></returns>
        <remarks><span data-ttu-id="7a31c-144">Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-144">Service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7a31c-145">Wird zurückgegeben, sobald Ereignisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="7a31c-145">It returns as soon as there are any events available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7a31c-146">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-146">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7a31c-147">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-147">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7a31c-148">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-148">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7a31c-149">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-149">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (waitTime As TimeSpan) As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime"><span data-ttu-id="7a31c-150">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</span><span class="sxs-lookup"><span data-stu-id="7a31c-150">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7a31c-151">Empfängt Daten von Event Hubs-Ereignis mit dem angegebenen Timeoutwert an.</span><span class="sxs-lookup"><span data-stu-id="7a31c-151">Receives Event Hubs event data with the specified timeout value.</span></span></summary>
        <returns><span data-ttu-id="7a31c-152">Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung oder Null, wenn es keine Ereignisdaten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-152">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection, or null if there is no event data available.</span></span></returns>
        <remarks>
          <span data-ttu-id="7a31c-153"><paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-153"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7a31c-154">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-154">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7a31c-155">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-155">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7a31c-156">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-156">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7a31c-157">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-157">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer, waitTime As TimeSpan) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7a31c-158">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</span><span class="sxs-lookup"><span data-stu-id="7a31c-158">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <param name="waitTime"><span data-ttu-id="7a31c-159">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</span><span class="sxs-lookup"><span data-stu-id="7a31c-159">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7a31c-160">Empfängt Event Hubs-Ereignisdaten, bis die angegebene Anzahl mit dem angegebenen Timeoutwert an.</span><span class="sxs-lookup"><span data-stu-id="7a31c-160">Receives Event Hubs event data, up to the specified count with the specified timeout value.</span></span></summary>
        <returns><span data-ttu-id="7a31c-161">Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung.</span><span class="sxs-lookup"><span data-stu-id="7a31c-161">Returns the received <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> collection.</span></span> <span data-ttu-id="7a31c-162">Die Auflistung ist entweder leer, wenn kein Ereignis wird innerhalb der angegebenen Zeit oder alle Ereignisse zurückgegeben, bis zu <paramref name="maxCount" /> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-162">The collection is either empty if no event is returned within the specified time, or all events up to <paramref name="maxCount" /> are returned.</span></span></returns>
        <remarks>
          <span data-ttu-id="7a31c-163"><paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-163"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span> <span data-ttu-id="7a31c-164">Auch Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-164">Also service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7a31c-165">wird zurückgegeben, sobald Ereignisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="7a31c-165">it returns as soon as there are any events available.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="7a31c-166">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-166">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="7a31c-167">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-167">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException"><span data-ttu-id="7a31c-168">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</span><span class="sxs-lookup"><span data-stu-id="7a31c-168">Thrown if the current namespace is placing too much load on the system.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="7a31c-169">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-169">Thrown if another receiver with a higher <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> value is connected as the current receiver to the same partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7a31c-170">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-170">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />.</span></span></summary>
        <returns><span data-ttu-id="7a31c-171">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-171">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7a31c-172">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</span><span class="sxs-lookup"><span data-stu-id="7a31c-172">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <summary><span data-ttu-id="7a31c-173">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-173">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />.</span></span></summary>
        <returns><span data-ttu-id="7a31c-174">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7a31c-174">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="7a31c-175">Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-175">Service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7a31c-176">Wird zurückgegeben, sobald Ereignisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="7a31c-176">It returns as soon as there are any events available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (waitTime As TimeSpan) As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime"><span data-ttu-id="7a31c-177">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</span><span class="sxs-lookup"><span data-stu-id="7a31c-177">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7a31c-178">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-178">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />.</span></span></summary>
        <returns><span data-ttu-id="7a31c-179">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7a31c-179">The task representing the asynchronous operation.</span></span></returns>
        <remarks>
          <span data-ttu-id="7a31c-180"><paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-180"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount"><span data-ttu-id="7a31c-181">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</span><span class="sxs-lookup"><span data-stu-id="7a31c-181">The maximum amount of event data the user is willing to accept in one call.</span></span></param>
        <param name="waitTime"><span data-ttu-id="7a31c-182">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</span><span class="sxs-lookup"><span data-stu-id="7a31c-182">The maximum time the user is willing to wait for event data to arrive.</span></span></param>
        <summary><span data-ttu-id="7a31c-183">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-183">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />.</span></span></summary>
        <returns><span data-ttu-id="7a31c-184">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7a31c-184">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>
          <span data-ttu-id="7a31c-185"><paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-185"><paramref name="waitTime" /> is not a guaranteed wait time, as API will return data as soon as it is available.</span></span> <span data-ttu-id="7a31c-186">Auch Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7a31c-186">Also service does not wait for <paramref name="maxCount" /> events to be filled before returning to user.</span></span> <span data-ttu-id="7a31c-187">Wird zurückgegeben, sobald Ereignisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="7a31c-187">It returns as soon as there are any events available.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="7a31c-188">Ruft einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="7a31c-188">Gets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a31c-189">Ruft die ungefähre Empfänger Laufzeitinformationen für eine logische Partition einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="7a31c-189">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="7a31c-190">Um die Einstellung zu aktivieren, finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" /> und<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="7a31c-190">To enable the setting, refer to <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" /> and <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingDateTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartingDateTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartingDateTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingDateTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartingDateTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-191">Ruft das Datum und die Uhrzeit im UTC-Format für diesen Empfänger ein.</span><span class="sxs-lookup"><span data-stu-id="7a31c-191">Gets the starting date and time in UTC format for this receiver.</span></span> <span data-ttu-id="7a31c-192">Die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> Methode startet den Empfang von das nächste Ereignis hiernach <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="7a31c-192">The <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> method starts receiving the next event after this <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" /> value.</span></span> <span data-ttu-id="7a31c-193">Bei null beginnt der Empfänger empfangen von Ereignissen vom Anfang des ereignisdatenstroms Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="7a31c-193">If null, the receiver starts receiving events from the beginning of the Event Hubs event stream.</span></span></summary>
        <value><span data-ttu-id="7a31c-194">Das Datum und Uhrzeit in UTC.</span><span class="sxs-lookup"><span data-stu-id="7a31c-194">The starting date and time in UTC.</span></span></value>
        <remarks><span data-ttu-id="7a31c-195">Dienst verwendet dieser DateTime-Wert nur als eine Näherung darstellt, bei der Übermittlung des nächsten Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="7a31c-195">Service only uses this datetime as an approximation when delivering next event.</span></span>
            <span data-ttu-id="7a31c-196">Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="7a31c-196">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingOffset">
      <MemberSignature Language="C#" Value="public string StartingOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartingOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartingOffset : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7a31c-197">Ruft den Anfangsoffset dieser Empfänger an.</span><span class="sxs-lookup"><span data-stu-id="7a31c-197">Gets the starting offset for this receiver.</span></span> <span data-ttu-id="7a31c-198">Die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> Methode startet den Empfang von das nächste Ereignis aus, nachdem dieser Wert ausgeglichen.</span><span class="sxs-lookup"><span data-stu-id="7a31c-198">The <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> method starts receiving the next event after this offset value.</span></span> <span data-ttu-id="7a31c-199">Wenn der Wert null ist, startet der Empfänger empfangen von Ereignissen vom Anfang des ereignisdatenstroms Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="7a31c-199">If the value is null, the receiver starts receiving events from the beginning of the Event Hubs event stream.</span></span></summary>
        <value><span data-ttu-id="7a31c-200">Der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="7a31c-200">The starting offset.</span></span></value>
        <remarks><span data-ttu-id="7a31c-201">Dies Startoffset bindet nur einer einzigen Partition dargestellte <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="7a31c-201">This starting offset ties to one partition only, represented by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>