<Type Name="PartitionSender" FullName="Microsoft.Azure.EventHubs.PartitionSender">
  <TypeSignature Language="C#" Value="public sealed class PartitionSender : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionSender extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.PartitionSender" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type PartitionSender = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2fe3b-101">Diese Klasse ist eine logische Darstellung zum Senden von Ereignissen an einer bestimmten Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-101">This sender class is a logical representation of sending events to a specific EventHub partition.</span></span> <span data-ttu-id="2fe3b-102">Verwenden Sie nicht diese Klasse, wenn keine übertragbaren Senden von Ereignissen an bestimmte Partitionen stattdessen verwenden <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-102">Do not use this class if you do not care about sending events to specific partitions, instead use <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreatePartitionSender(System.String)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionSender.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionSender/&lt;CloseAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2fe3b-103">Schließt und frei von Ressourcen für die <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-103">Closes and releases resources for the <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2fe3b-104">Ein asynchroner Vorgang</span><span class="sxs-lookup"><span data-stu-id="2fe3b-104">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubClient EventHubClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventHubClient EventHubClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubClient As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.EventHubClient : Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fe3b-105">Ruft die <see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" /> dieser PartitionSender zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-105">Gets the <see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" /> associated with this PartitionSender.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionSender.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.PartitionSender.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fe3b-106">Ruft die Partitions-ID für diese <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-106">Gets the partition ID for this <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="partitionSender.SendAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="2fe3b-107">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-107">the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to be sent.</span></span></param>
        <summary>
            <span data-ttu-id="2fe3b-108">Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einer bestimmten Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-108">Send <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to a specific EventHub partition.</span></span> <span data-ttu-id="2fe3b-109">Die Zielpartition wird vorab festgelegt werden, wenn diese PartitionSender erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-109">The target partition is pre-determined when this PartitionSender was created.</span></span>
            <span data-ttu-id="2fe3b-110">Dieses Muster senden betont Korrelation der Daten über die allgemeine Verfügbarkeit und die Latenz.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-110">This send pattern emphasizes data correlation over general availability and latency.</span></span>
            <span data-ttu-id="2fe3b-111"><para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit der Überladung SendBatch) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diesen Typ des Sendeports ein, wenn: <para>ein. Der Client möchte direkte Kontrolle über die Verteilung der Daten auf Partitionen zu übernehmen. In diesem Fall ist der Client dafür verantwortlich, dass Sie sicher, dass mindestens ein Absender pro Ereignis-Hub-Partition vorhanden ist. </para> <para>b. Benutzer nicht mehr als einen Mittelwert direkte von Ereignissen an bestimmte Partition Partitionsschlüssel verwenden, aber für die Datenkorrelation mit Partitionsschema Portkonflikt vorliegt.</para></span><span class="sxs-lookup"><span data-stu-id="2fe3b-111"><para>There are 3 ways to send to EventHubs, each exposed as a method (along with its sendBatch overload):</para><para>i.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para><para>ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /></para><para>iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para> Use this type of send if: <para>a. The client wants to take direct control of distribution of data across partitions. In this case client is responsible for making sure there is at least one sender per event hub partition.</para><para>b. User cannot use partition key as a mean to direct events to specific partition, yet there is a need for data correlation with partitioning scheme.</para></span></span></summary>
        <returns><span data-ttu-id="2fe3b-112">Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-112">A Task that completes when the send operations is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException"><span data-ttu-id="2fe3b-113">die Gesamtgröße der <see cref="T:Microsoft.Azure.EventHubs.EventData" /> überschreitet eine vordefinierte Grenze, die vom Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-113">the total size of the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> exceeds a pre-defined limit set by the service.</span></span> <span data-ttu-id="2fe3b-114">Standardwert ist 256 KB.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-114">Default is 256k bytes.</span></span></exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException"><span data-ttu-id="2fe3b-115">Event Hubs-Dienst Probleme während des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-115">Event Hubs service encountered problems during the operation.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="partitionSender.SendAsync eventDatas" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionSender/&lt;SendAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDatas"><span data-ttu-id="2fe3b-116">Batch von Ereignissen an Event Hub senden.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-116">batch of events to send to EventHub</span></span></param>
        <summary>
            <span data-ttu-id="2fe3b-117">Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einer bestimmten Event Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-117">Send <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to a specific EventHub partition.</span></span> <span data-ttu-id="2fe3b-118">Die eingerichteten Partition wird vorab festgelegt werden, wenn diese PartitionSender erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-118">The targeted partition is pre-determined when this PartitionSender was created.</span></span>
            <span data-ttu-id="2fe3b-119"><para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, die vom selben Typ des Sendeports und wird verwendet, um die einzelnen senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para>Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen, die an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden mehrerer <see cref="T:Microsoft.Azure.EventHubs.EventData" />des in einer Transaktion. Um die ACID-Eigenschaften zu erreichen, der Gatewaydienst leitet alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des im Batch in einer einzelnen EventHub partitionieren.</para></span><span class="sxs-lookup"><span data-stu-id="2fe3b-119"><para> There are 3 ways to send to EventHubs, to understand this particular type of send refer to the overload <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, which is the same type of send and is used to send single <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para> Sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s is useful in the following cases: <para>i.    Efficient send - sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximizes the overall throughput by optimally using the number of sessions created to EventHubs' service.</para><para>ii.   Sending multiple <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in a Transaction. To acheive ACID properties, the Gateway Service will forward all <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in the batch to a single EventHub partition.</para></span></span></summary>
        <returns><span data-ttu-id="2fe3b-120">eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-120">a Task that completes when the send operation is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException"><span data-ttu-id="2fe3b-121">die Gesamtgröße der <see cref="T:Microsoft.Azure.EventHubs.EventData" /> überschreitet eine vordefinierte Grenze, die vom Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-121">the total size of the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> exceeds a pre-defined limit set by the service.</span></span> <span data-ttu-id="2fe3b-122">Standardwert ist 256 KB.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-122">Default is 256k bytes.</span></span></exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException"><span data-ttu-id="2fe3b-123">Event Hubs-Dienst Probleme während des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="2fe3b-123">Event Hubs service encountered problems during the operation.</span></span></exception>
        <example>
            <span data-ttu-id="2fe3b-124">Beispielcode:</span><span class="sxs-lookup"><span data-stu-id="2fe3b-124">Sample code:</span></span>
            <code>
            EventHubClient client = EventHubClient.Create("__connectionString__");
            PartitionSender senderToPartitionOne = client.CreatePartitionSender("1");
                    
            while (true)
            {
                var events = new List&lt;EventData&gt;();
                for (int count = 1; count &lt; 11; count++)
                {
                    var payload = new PayloadEvent(count);
                    byte[] payloadBytes = Encoding.UTF8.GetBytes(JsonConvert.SerializeObject(payload));
                    var sendEvent = new EventData(payloadBytes);
                    var applicationProperties = new Dictionary&lt;string, string&gt;();
                    applicationProperties["from"] = "csharpClient";
                    sendEvent.Properties = applicationProperties;
                    events.Add(sendEvent);
                }
                    
                await senderToPartitionOne.SendAsync(events);
                Console.WriteLine("Sent Batch... Size: {0}", events.Count);
                
            }
            </code></example>
      </Docs>
    </Member>
  </Members>
</Type>