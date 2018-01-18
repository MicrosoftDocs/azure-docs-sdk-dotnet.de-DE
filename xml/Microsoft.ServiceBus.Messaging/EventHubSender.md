<Type Name="EventHubSender" FullName="Microsoft.ServiceBus.Messaging.EventHubSender">
  <TypeSignature Language="C#" Value="public sealed class EventHubSender : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubSender extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubSender" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubSender = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="da4b7-101">Eine Clientklasse, die in der Send-Vorgänge für einen Event Hub verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="da4b7-101">A client class used in send operations for an Event Hub.</span></span>
            <span data-ttu-id="da4b7-102">Stellt eine logische Sender-Verbindung zu einer bestimmten Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="da4b7-102">Represents a logical sender connection to a specific Event Hub partition.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="eventHubSender.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="da4b7-103">Erstellt einen Batch, in denen Daten von Ereignisobjekten für späteren Aufruf von SendBatch oder SendBatchAsync hinzugefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="da4b7-103">Creates a batch where event data objects can be added for later SendBatch or SendBatchAsync call.</span></span></summary>
        <returns><span data-ttu-id="da4b7-104">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />zurück.</span><span class="sxs-lookup"><span data-stu-id="da4b7-104">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubSender CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubSender CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="da4b7-105">Die verwendete Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="da4b7-105">The connection string used.</span></span></param>
        <summary>
            <span data-ttu-id="da4b7-106">Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="da4b7-106">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> using the supplied connection string.</span></span>
            <span data-ttu-id="da4b7-107">Sollte verwendet werden, senden, verwenden eine "ConnectionString" mit SharedAcessSignature und Verleger.</span><span class="sxs-lookup"><span data-stu-id="da4b7-107">Intended to be used to send using a ConnectionString with SharedAcessSignature and Publisher.</span></span>
            </summary>
        <returns><span data-ttu-id="da4b7-108">Der erstellte<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /></span><span class="sxs-lookup"><span data-stu-id="da4b7-108">The created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /></span></span></returns>
        <remarks><span data-ttu-id="da4b7-109">Die Verbindung entweder aus dem Azure-Portal abgerufen oder erstellt eine <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="da4b7-109">The connection can be obtained either from the Azure portal, or created from a <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> instance.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubSender.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubSender.OnBeginClose (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubSender.OnBeginOpen (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubSender.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubSender.OnEndClose result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubSender.OnEndOpen result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubSender.OnOpen timeout" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="da4b7-110">Ruft die Partitions-ID für eine logische Partition einen Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="da4b7-110">Gets the partition ID for a logical partition of an Event Hub.</span></span></summary>
        <value><span data-ttu-id="da4b7-111">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="da4b7-111">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubSender.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="da4b7-112">Ruft den Pfad des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="da4b7-112">Gets the path of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="da4b7-113">Der Event Hub-Pfad.</span><span class="sxs-lookup"><span data-stu-id="da4b7-113">The Event Hub path.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Send(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.Send(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (data As EventData)" />
      <MemberSignature Language="F#" Value="member this.Send : Microsoft.ServiceBus.Messaging.EventData -&gt; unit" Usage="eventHubSender.Send data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="da4b7-114">Der zu sendende <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-114">The <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> to send.</span></span></param>
        <summary><span data-ttu-id="da4b7-115">Sendet Ereignisdaten an die logischen Partition durch dargestellt <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-115">Sends event data to the logical partition represented by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendAsync(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (data As EventData) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubSender.SendAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="da4b7-116">Der zu sendende <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-116">The <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> to send.</span></span></param>
        <summary><span data-ttu-id="da4b7-117">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.Send(Microsoft.ServiceBus.Messaging.EventData)" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-117">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.Send(Microsoft.ServiceBus.Messaging.EventData)" />.</span></span></summary>
        <returns><span data-ttu-id="da4b7-118">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da4b7-118">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (eventDataList As IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; unit" Usage="eventHubSender.SendBatch eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList"><span data-ttu-id="da4b7-119">Ein IEnumerable-Objekt, das mit Daten von Ereignisinstanzen ist.</span><span class="sxs-lookup"><span data-stu-id="da4b7-119">An IEnumerable object containing event data instances.</span></span></param>
        <summary><span data-ttu-id="da4b7-120">Sendet einen Batch von Ereignisdaten in der logischen Partition durch dargestellt <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-120">Sends a batch of event data to the logical partition represented by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span></span></summary>
        <remarks><span data-ttu-id="da4b7-121">Benutzer sollten sicherstellen, dass die Summe serialisierte Größe des <paramref name="eventDataList" /> sollte die maximale Größe der Datenübertragung ein Ereignis, also 256 k standardmäßig sein.</span><span class="sxs-lookup"><span data-stu-id="da4b7-121">User should make sure the total serialized size of <paramref name="eventDataList" /> should be under the size limit of one event data transmission, which is 256k by default.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException"><span data-ttu-id="da4b7-122">Wird ausgelöst, wenn die Summe der Größe serialisiert <paramref name="eventDataList" /> überschreitet die maximale zulässige Größe für ein Ereignis Übertragung (256 k standardmäßig).</span><span class="sxs-lookup"><span data-stu-id="da4b7-122">Thrown if the total serialized size of <paramref name="eventDataList" /> exceeds the allowed size limit for one event transmission (256k by default).</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (eventDataList As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubSender.SendBatchAsync eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList"><span data-ttu-id="da4b7-123">Ein IEnumerable-Objekt, das mit Daten von Ereignisinstanzen ist.</span><span class="sxs-lookup"><span data-stu-id="da4b7-123">An IEnumerable object containing event data instances.</span></span></param>
        <summary><span data-ttu-id="da4b7-124">Sendet asynchron einen Batch von Ereignisdaten in der logischen Partition durch dargestellt <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="da4b7-124">Asynchronously sends a batch of event data to the logical partition represented by <see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />.</span></span></summary>
        <returns><span data-ttu-id="da4b7-125">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="da4b7-125">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks><span data-ttu-id="da4b7-126">Benutzer sollten sicherstellen, dass die Summe serialisierte Größe des <paramref name="eventDataList" /> sollte die maximale Größe der Datenübertragung ein Ereignis, also 256 k standardmäßig sein.</span><span class="sxs-lookup"><span data-stu-id="da4b7-126">User should make sure the total serialized size of <paramref name="eventDataList" /> should be under the size limit of one event data transmission, which is 256k by default.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException"><span data-ttu-id="da4b7-127">Wird ausgelöst, wenn die Summe der Größe serialisiert <paramref name="eventDataList" /> überschreitet die maximale zulässige Größe für ein Ereignis Übertragung (256 k standardmäßig).</span><span class="sxs-lookup"><span data-stu-id="da4b7-127">Thrown if the total serialized size of <paramref name="eventDataList" /> exceeds the allowed size limit for one event transmission (256k by default).</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>