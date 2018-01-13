<Type Name="EventHubConsumerGroup" FullName="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup">
  <TypeSignature Language="C#" Value="public sealed class EventHubConsumerGroup : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubConsumerGroup extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubConsumerGroup&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubConsumerGroup = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="dcba5-101">Stellt die consumergruppe innerhalb eines Event Hubs dar.</span><span class="sxs-lookup"><span data-stu-id="dcba5-101">Represents the consumer group within an Event Hub.</span></span> <span data-ttu-id="dcba5-102">Diese Klasse wird für eine bestimmte consumergruppe innerhalb eines Event Hubs Empfänger erstellt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-102">This class creates receivers for a specific consumer group within an Event Hub.</span></span> <span data-ttu-id="dcba5-103">Dies kann die standardconsumergruppe oder eine andere benutzerdefinierte consumergruppe sein.</span><span class="sxs-lookup"><span data-stu-id="dcba5-103">This can be the default consumer group or another user-created consumer group.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-104">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-104">The ID of the partition.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-105">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-105">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-106">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-106">Creates a new Event Hubs receiver in the specified partition.</span></span> <span data-ttu-id="dcba5-107">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-107">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-108">Gibt die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> -Objekt, das an der angegebenen Partition des Event Hubs gebunden ist.</span><span class="sxs-lookup"><span data-stu-id="dcba5-108">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> object that is tied to the given Event Hubs partition.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-109">Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert hat, diese Überladung wird immer Throw InvalidOperationException Prüfpunkt ConsumerGroup aktiviert Quellformat, sodass Epoche funktioniert (verwenden Sie die Überladung, die als Eingabeargument Epoche angeben).</span><span class="sxs-lookup"><span data-stu-id="dcba5-109">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, this overload will always throw InvalidOperationException because checkpoint enabled ConsumerGroup requires epoch to work (please use the overload that supply epoch as input argument).</span></span> <span data-ttu-id="dcba5-110">Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="dcba5-110">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="dcba5-111">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-111">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="dcba5-112">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-112">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-113">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-113">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="dcba5-114">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-114">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="dcba5-115">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-115">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, DateTime startingDateTimeUtc, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, valuetype System.DateTime startingDateTimeUtc, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * DateTime * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingDateTimeUtc, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-116">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-116">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="dcba5-117">Die UTC-Startzeit zum Empfangen von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-117">The starting UTC time for receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-118">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-118">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-119">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition, beginnend am angegebenen Datum und Uhrzeit.</span><span class="sxs-lookup"><span data-stu-id="dcba5-119">Creates a new Event Hubs receiver in the specified partition, starting at the specified date and time.</span></span> <span data-ttu-id="dcba5-120">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-120">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-121">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-121">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-122">Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-122">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="dcba5-123">Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-123">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="dcba5-124">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-124">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="dcba5-125">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-125">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-126">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-126">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="dcba5-127">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-127">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="dcba5-128">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />, mit einer <paramref name="startingDateTimeUtc" /> angegebenen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-128">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />, with an <paramref name="startingDateTimeUtc" /> specified.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-129">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-129">The ID of the partition.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-130">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-130">The epoch value.</span></span> <span data-ttu-id="dcba5-131">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-131">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-132">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-132">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-133">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition und den Wert der angegebenen Epoche.</span><span class="sxs-lookup"><span data-stu-id="dcba5-133">Creates a new Event Hubs receiver in the specified partition, and the specified epoch value.</span></span> <span data-ttu-id="dcba5-134">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-134">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-135">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-135">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-136">Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert, hat, der Empfänger die nächste Nachricht vom Prüfpunkt Offset erhalten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-136">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, then the receiver will get next message from the checkpoint offset.</span></span> <span data-ttu-id="dcba5-137">Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="dcba5-137">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the event hub.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="dcba5-138">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-138">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="dcba5-139">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-139">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-140">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-140">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-141">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-141">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-142">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-142">The starting offset at which to start receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-143">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-143">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-144">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-144">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="dcba5-145">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-145">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-146">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-146">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-147">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-147">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="dcba5-148">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-148">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="dcba5-149">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />, mit einer <paramref name="startingOffset" /> angegebenen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-149">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />, with an <paramref name="startingOffset" /> specified.</span></span></exception>
        <code>
                <span data-ttu-id="dcba5-150">Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.</span><span class="sxs-lookup"><span data-stu-id="dcba5-150">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="dcba5-151">Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-151">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="dcba5-152">Beschreibung der EventHubDescription;</span><span class="sxs-lookup"><span data-stu-id="dcba5-152">EventHubDescription description;</span></span>
                
                <span data-ttu-id="dcba5-153">EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.StartOfStream);</span><span class="sxs-lookup"><span data-stu-id="dcba5-153">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.StartOfStream);</span></span>
                
                <span data-ttu-id="dcba5-154">Var EventData = Empfänger. Receive();</span><span class="sxs-lookup"><span data-stu-id="dcba5-154">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, DateTime startingDateTimeUtc, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, valuetype System.DateTime startingDateTimeUtc, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * DateTime * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingDateTimeUtc, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-155">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-155">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="dcba5-156">Die UTC-Startzeit zum Empfangen von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-156">The starting UTC time for receiving messages.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-157">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-157">The epoch value.</span></span> <span data-ttu-id="dcba5-158">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-158">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-159">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-159">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-160">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition, beginnend am angegebenen Datum und Uhrzeit.</span><span class="sxs-lookup"><span data-stu-id="dcba5-160">Creates a new Event Hubs receiver in the specified partition, starting at the specified date and time.</span></span> <span data-ttu-id="dcba5-161">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-161">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-162">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-162">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-163">Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-163">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="dcba5-164">Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-164">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="dcba5-165">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-165">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="dcba5-166">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-166">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-167">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-167">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, bool offsetInclusive, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, bool offsetInclusive, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * bool * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-168">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-168">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-169">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-169">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="dcba5-170">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass die erste <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param></span><span class="sxs-lookup"><span data-stu-id="dcba5-170">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first <param name="receiverOptions">Options for a event hub receiver.</param></span></span>
            <span data-ttu-id="dcba5-171">Ereignis zurückgegeben wird das Ereignis, das den Anfangsoffset enthält.</span><span class="sxs-lookup"><span data-stu-id="dcba5-171">event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="dcba5-172">Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-172">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="receiverOptions">To be added.</param>
        <summary><span data-ttu-id="dcba5-173">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-173">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="dcba5-174">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-174">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-175">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-175">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="dcba5-176">Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus der ersten Partitionen die standardconsumergruppe.</span><span class="sxs-lookup"><span data-stu-id="dcba5-176">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer group.</span></span> <span data-ttu-id="dcba5-177">Es wird verwendet, / / ein zuvor gespeicherter Offset als ab offset und das Ereignis zurück / / als Erstes Ereignis</span><span class="sxs-lookup"><span data-stu-id="dcba5-177">It uses // a previously stored offset as starting offset and return that event // as the first event</span></span>
                
                <span data-ttu-id="dcba5-178">Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-178">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="dcba5-179">Darüber hinaus vorausgesetzt, dass Benutzer die gespeicherte Offset EventHubDescription Beschreibung abgerufen hat; eine Zeichenfolge StoredOffset = "2478";</span><span class="sxs-lookup"><span data-stu-id="dcba5-179">// Also assume user has retrieved the stored offset EventHubDescription description; string storedOffset = "2478";</span></span>
                
                <span data-ttu-id="dcba5-180">EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() StoredOffset);</span><span class="sxs-lookup"><span data-stu-id="dcba5-180">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), storedOffset);</span></span>
                
                <span data-ttu-id="dcba5-181">EventData wird der offset haben == StoredOffset Var EventData = Empfänger. Receive();</span><span class="sxs-lookup"><span data-stu-id="dcba5-181">// eventData will have offset == storedOffset var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-182">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-182">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-183">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-183">The starting offset at which to start receiving messages.</span></span> <span data-ttu-id="dcba5-184">Der Anfang des Streams angeben zu können, finden Sie unter <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-184">To specify the start of the stream, see <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-185">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-185">The epoch value.</span></span> <span data-ttu-id="dcba5-186">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-186">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-187">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-187">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-188">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-188">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span></summary>
        <returns><span data-ttu-id="dcba5-189">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-189">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="dcba5-190">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-190">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="dcba5-191">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-191">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-192">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-192">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * bool * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-193">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-193">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-194">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-194">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="dcba5-195">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält.</span><span class="sxs-lookup"><span data-stu-id="dcba5-195">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="dcba5-196">Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-196">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-197">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-197">The epoch value.</span></span> <span data-ttu-id="dcba5-198">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-198">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-199">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-199">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-200">Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-200">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="dcba5-201">Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-201">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-202">Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-202">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-203">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-203">The ID of the partition.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-204">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-204">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-205">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-205">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-206">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-206">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-207">Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert hat, diese Überladung wird immer Throw InvalidOperationException Prüfpunkt ConsumerGroup aktiviert Quellformat, sodass Epoche funktioniert (verwenden Sie die Überladung, die als Eingabeargument Epoche angeben).</span><span class="sxs-lookup"><span data-stu-id="dcba5-207">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, this overload will always throw InvalidOperationException because checkpoint enabled ConsumerGroup requires epoch to work (please use the overload that supply epoch as input argument).</span></span> <span data-ttu-id="dcba5-208">Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="dcba5-208">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, DateTime startingDateTimeUtc, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, valuetype System.DateTime startingDateTimeUtc, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * DateTime * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingDateTimeUtc, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-209">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-209">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="dcba5-210">Die UTC-Startzeit zum Empfangen von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-210">The starting UTC time for receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-211">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-211">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-212">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-212">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-213">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-213">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-214">Dienst diese Option nur verwenden <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-214">Service only use this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="dcba5-215">Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-215">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-216">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-216">The ID of the partition.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-217">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-217">The epoch value.</span></span> <span data-ttu-id="dcba5-218">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-218">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-219">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-219">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-220">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-220">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-221">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-221">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-222">Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert, hat, der Empfänger die nächste Nachricht vom Prüfpunkt Offset erhalten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-222">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, then the receiver will get next message from the checkpoint offset.</span></span> <span data-ttu-id="dcba5-223">Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="dcba5-223">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-224">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-224">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-225">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-225">The starting offset at which to start receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-226">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-226">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-227">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-227">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-228">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-228">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, DateTime startingDateTimeUtc, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, valuetype System.DateTime startingDateTimeUtc, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * DateTime * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingDateTimeUtc, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-229">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-229">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="dcba5-230">Die UTC-Startzeit zum Empfangen von Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="dcba5-230">The starting UTC time for receiving messages.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-231">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-231">The epoch value.</span></span> <span data-ttu-id="dcba5-232">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-232">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-233">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-233">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-234">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-234">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-235">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-235">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-236">Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-236">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="dcba5-237">Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-237">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, bool offsetInclusive, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, bool offsetInclusive, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * bool * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-238">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-238">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-239">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-239">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="dcba5-240">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält.</span><span class="sxs-lookup"><span data-stu-id="dcba5-240">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="dcba5-241">Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-241">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-242">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-242">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-243">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-243">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-244">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-244">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="dcba5-245">Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus der ersten Partitionen die standardconsumergruppe.</span><span class="sxs-lookup"><span data-stu-id="dcba5-245">// The following code snippet creates a receiver that receive events // from the first partitions of the default consumer group.</span></span> <span data-ttu-id="dcba5-246">Es wird verwendet, / / ein zuvor gespeicherter Offset als ab offset und das Ereignis zurück / / als Erstes Ereignis</span><span class="sxs-lookup"><span data-stu-id="dcba5-246">It uses // a previously stored offset as starting offset and return that event // as the first event</span></span>
                
                <span data-ttu-id="dcba5-247">Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-247">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="dcba5-248">Darüber hinaus vorausgesetzt, dass Benutzer die gespeicherte Offset EventHubDescription Beschreibung abgerufen hat; eine Zeichenfolge StoredOffset = "2478";</span><span class="sxs-lookup"><span data-stu-id="dcba5-248">// Also assume user has retrieved the stored offset EventHubDescription description; string storedOffset = "2478";</span></span>
                
                <span data-ttu-id="dcba5-249">EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() StoredOffset);</span><span class="sxs-lookup"><span data-stu-id="dcba5-249">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), storedOffset);</span></span>
                
                <span data-ttu-id="dcba5-250">EventData wird der offset haben == StoredOffset Var EventData = Empfänger. Receive();</span><span class="sxs-lookup"><span data-stu-id="dcba5-250">// eventData will have offset == storedOffset var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-251">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-251">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-252">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-252">The starting offset at which to start receiving messages.</span></span> <span data-ttu-id="dcba5-253">Der Anfang des Streams angeben zu können, finden Sie unter <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-253">To specify the start of the stream, see <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-254">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-254">The epoch value.</span></span> <span data-ttu-id="dcba5-255">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-255">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-256">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-256">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-257">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-257">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-258">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-258">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * bool * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="dcba5-259">Die ID der Partition.</span><span class="sxs-lookup"><span data-stu-id="dcba5-259">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="dcba5-260">Der Startoffset an der mit dem Nachrichten empfangen werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-260">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="dcba5-261">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält.</span><span class="sxs-lookup"><span data-stu-id="dcba5-261">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="dcba5-262">Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</span><span class="sxs-lookup"><span data-stu-id="dcba5-262">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="epoch"><span data-ttu-id="dcba5-263">Der Epoch-Wert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-263">The epoch value.</span></span> <span data-ttu-id="dcba5-264">Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-264">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="dcba5-265">Optionen für einen Hub-Ereignisempfänger verwenden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-265">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="dcba5-266">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-266">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-267">Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-267">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultGroupName">
      <MemberSignature Language="C#" Value="public const string DefaultGroupName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultGroupName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.DefaultGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultGroupName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultGroupName : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.DefaultGroupName" />
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
            <span data-ttu-id="dcba5-268">Der Name der standardmäßigen ConsumerGroup, die beim Erstellen der EventHub vorab erstellte ist.</span><span class="sxs-lookup"><span data-stu-id="dcba5-268">The name of the default ConsumerGroup that is pre-created when creating EventHub.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetDefaultConsumerGroup" />
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="dcba5-269">Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="dcba5-269">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="dcba5-270">"true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-270">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span> </value>
        <remarks><span data-ttu-id="dcba5-271">Der Standardwert wird aus dem Wert des abgeleitet.<see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="dcba5-271">Its default value is derived from the value of <see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOfStream">
      <MemberSignature Language="C#" Value="public const string EndOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EndOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EndOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Const EndOfStream As String " />
      <MemberSignature Language="F#" Value="val mutable EndOfStream : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EndOfStream" />
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
            <span data-ttu-id="dcba5-272">Die Konstante, die das Ende eines Streams kennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="dcba5-272">The constant that denotes the end of a stream.</span></span> <span data-ttu-id="dcba5-273">Dies kann als Argument Offset im Erstellen von remoteereignisempfängern zum Starten empfangen aus dem letzten Ereignis, anstelle von einem bestimmten Zeitpunkt im Zeit-Offset-Wert verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-273">This can be used as an offset argument in receiver creation to start receiving from the latest event, instead of a specific point in time/offset value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                <span data-ttu-id="dcba5-274">Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.</span><span class="sxs-lookup"><span data-stu-id="dcba5-274">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="dcba5-275">Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-275">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="dcba5-276">Beschreibung der EventHubDescription;</span><span class="sxs-lookup"><span data-stu-id="dcba5-276">EventHubDescription description;</span></span>
                
                <span data-ttu-id="dcba5-277">EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.EndOfStream);</span><span class="sxs-lookup"><span data-stu-id="dcba5-277">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.EndOfStream);</span></span>
                
                <span data-ttu-id="dcba5-278">Var EventData = Empfänger. Receive();</span><span class="sxs-lookup"><span data-stu-id="dcba5-278">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dcba5-279">Ruft den Pfad der Ereignis-Hub.</span><span class="sxs-lookup"><span data-stu-id="dcba5-279">Gets the event hub path.</span></span></summary>
        <value><span data-ttu-id="dcba5-280">Der Pfad der Ereignis-hub</span><span class="sxs-lookup"><span data-stu-id="dcba5-280">The event hub path</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventProcessorLifeCycleManagerFaulted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; EventProcessorLifeCycleManagerFaulted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; EventProcessorLifeCycleManagerFaulted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventProcessorLifeCycleManagerFaulted" />
      <MemberSignature Language="VB.NET" Value="Public Event EventProcessorLifeCycleManagerFaulted As EventHandler(Of EventProcessorFaultedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.EventProcessorLifeCycleManagerFaulted : EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; " Usage="member this.EventProcessorLifeCycleManagerFaulted : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dcba5-281">Ruft den Namen der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="dcba5-281">Gets the name of the consumer group.</span></span></summary>
        <value><span data-ttu-id="dcba5-282">Der Name der Gruppe "Consumer".</span><span class="sxs-lookup"><span data-stu-id="dcba5-282">The name of the consumer group.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubConsumerGroup.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubConsumerGroup.OnBeginClose (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubConsumerGroup.OnBeginOpen (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubConsumerGroup.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubConsumerGroup.OnEndClose result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubConsumerGroup.OnEndOpen result" />
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
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dcba5-283">Ruft ab oder legt sie fest, werden die Anzahl der Ereignisse, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-283">Gets or sets the number of events that any receive operation will actively cache.</span></span> <span data-ttu-id="dcba5-284">Dieser Wert wird standardmäßig von geerbt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-284">By default, this value is inherited from <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span></span> <span data-ttu-id="dcba5-285">Der Standardwert ist 10.000.</span><span class="sxs-lookup"><span data-stu-id="dcba5-285">The default value is 10,000.</span></span></summary>
        <value><span data-ttu-id="dcba5-286">Die Anzahl der Ereignisse, die der Empfänger zwischenspeichern können.</span><span class="sxs-lookup"><span data-stu-id="dcba5-286">The number of events that the receiver can cache.</span></span></value>
        <remarks><span data-ttu-id="dcba5-287">Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> erstellt, die von dieser Instanz wird dieser Wert standardmäßig erben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-287">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created from this instance will inherit this value by default.</span></span>
            <span data-ttu-id="dcba5-288">Änderungen an dieser Wert ist nicht auf bereits erstellte Empfänger übertragen, aber verwendet werden, indem Sie neue <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> nach der Änderung erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-288">Changes to this value will not be propagate to already created receiver, but will be used by new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created after the change.</span></span> <span data-ttu-id="dcba5-289">Auch wenn diese Eigenschaft auf NULL festgelegt werden <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" /> auf Null.</span><span class="sxs-lookup"><span data-stu-id="dcba5-289">Also setting this property to non-zero will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" /> to null.</span></span>
            <span data-ttu-id="dcba5-290">Beachten Sie, dass die Anzahl die zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</span><span class="sxs-lookup"><span data-stu-id="dcba5-290">Note that setting the count too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-291">Wird ausgelöst, wenn der Wert kleiner als der erforderliche Mindestwert von 10 ist.</span><span class="sxs-lookup"><span data-stu-id="dcba5-291">Thrown if the value is less than the minimum required value of 10.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dcba5-292">Ruft ab oder legt sie fest, werden die maximale Größe (in Bytes), insgesamt, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert.</span><span class="sxs-lookup"><span data-stu-id="dcba5-292">Gets or sets the maximum size (in bytes) in total that any receive operation will actively cache.</span></span> <span data-ttu-id="dcba5-293">Die Größe der einzelnen Ereignisdaten richtet sich nach der <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="dcba5-293">The size of each event data is determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> property.</span></span></summary>
        <value><span data-ttu-id="dcba5-294">Gibt <see cref="T:System.Int64" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-294">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks><span data-ttu-id="dcba5-295">Das Größenlimit handelt es sich nicht um einen absoluten Begrenzung.</span><span class="sxs-lookup"><span data-stu-id="dcba5-295">The size limit is not an absolute limit.</span></span> <span data-ttu-id="dcba5-296">die Größe möglicherweise Anpassungsvorgang Folgendes zu einer Größe von mindestens eine Ereignisdaten wechseln.</span><span class="sxs-lookup"><span data-stu-id="dcba5-296">the size might go over by at least one event data worth of size.</span></span> <span data-ttu-id="dcba5-297">Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> erstellt, die von dieser Instanz wird dieser Wert standardmäßig erben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-297">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created from this instance will inherit this value by default.</span></span>
            <span data-ttu-id="dcba5-298">Änderungen an dieser Wert ist nicht auf bereits erstellte Empfänger übertragen, aber verwendet werden, indem Sie neue <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> nach der Änderung erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-298">Changes to this value will not be propagate to already created receiver, but will be used by new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created after the change.</span></span> <span data-ttu-id="dcba5-299">Auch wenn diese Eigenschaft auf Null-Wert festgelegt wird, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" /> auf 0 (null).</span><span class="sxs-lookup"><span data-stu-id="dcba5-299">Also, setting this property to non-null value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" /> to zero.</span></span>
            <span data-ttu-id="dcba5-300">Beachten Sie, dass die Größe zu niedrig festlegen beeinflussen die Wirksamkeit des Event Hubs Aufruf empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-300">Note that setting the size too low will affect the effective performance of the Event Hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="dcba5-301">Wird ausgelöst, wenn die Größenwert kleiner als der erforderliche Mindestwert von 260 KB ist.</span><span class="sxs-lookup"><span data-stu-id="dcba5-301">Thrown when the size value is less than the minimum required value of 260K bytes.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public void RegisterProcessor&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessor&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager -&gt; unit (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessor (lease, checkpointManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="dcba5-302">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-302">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="dcba5-303">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-303">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-304">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-304">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <summary><span data-ttu-id="dcba5-305">Registriert eine Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen von Event Hubs für den angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> beginnend <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-305">Registers an implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events from Event Hubs for the specified <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="dcba5-306">Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-306">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks><span data-ttu-id="dcba5-307">Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-307">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public void RegisterProcessor&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessor&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; unit (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessor (lease, checkpointManager, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="dcba5-308">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-308">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="dcba5-309">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-309">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-310">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-310">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="dcba5-311">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-311">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="dcba5-312">Registriert eine Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen von Event Hubs für den angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> beginnend <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-312">Registers an implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events from Event Hubs for the specified <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="dcba5-313">Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-313">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks><span data-ttu-id="dcba5-314">Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-314">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorAsync``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessorAsync (lease, checkpointManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="dcba5-315">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-315">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="dcba5-316">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-316">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-317">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-317">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <summary><span data-ttu-id="dcba5-318">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-318">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-319">Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-319">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorAsync``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessorAsync (lease, checkpointManager, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="dcba5-320">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-320">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="dcba5-321">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-321">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-322">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-322">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="dcba5-323">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-323">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="dcba5-324">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-324">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-325">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-325">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks><span data-ttu-id="dcba5-326">Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-326">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactory">
      <MemberSignature Language="C#" Value="public void RegisterProcessorFactory (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessorFactory(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactory : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; unit" Usage="eventHubConsumerGroup.RegisterProcessorFactory (lease, checkpointManager, eventProcessorFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-327">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-327">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-328">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-328">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="dcba5-329">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-329">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <summary><span data-ttu-id="dcba5-330">Registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Objekt zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, beginnend ab dem <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-330">Registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> object used to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="dcba5-331">Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-331">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="dcba5-332">TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();</span><span class="sxs-lookup"><span data-stu-id="dcba5-332">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="dcba5-333">Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};</span><span class="sxs-lookup"><span data-stu-id="dcba5-333">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="dcba5-334">subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }</span><span class="sxs-lookup"><span data-stu-id="dcba5-334">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactory">
      <MemberSignature Language="C#" Value="public void RegisterProcessorFactory (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessorFactory(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactory : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; unit" Usage="eventHubConsumerGroup.RegisterProcessorFactory (lease, checkpointManager, eventProcessorFactory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-335">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-335">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-336">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-336">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="dcba5-337">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-337">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="dcba5-338">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-338">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="dcba5-339">Registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Objekt zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, beginnend ab dem <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-339">Registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> object used to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="dcba5-340">Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-340">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="dcba5-341">TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();</span><span class="sxs-lookup"><span data-stu-id="dcba5-341">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="dcba5-342">Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};</span><span class="sxs-lookup"><span data-stu-id="dcba5-342">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="dcba5-343">subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }</span><span class="sxs-lookup"><span data-stu-id="dcba5-343">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.RegisterProcessorFactoryAsync (lease, checkpointManager, eventProcessorFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-344">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-344">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-345">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-345">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="dcba5-346">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-346">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <summary><span data-ttu-id="dcba5-347">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-347">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-348">Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-348">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="dcba5-349">TestEventProcessorFactory ProcessorFactory = neue TestEventProcessorFactory();</span><span class="sxs-lookup"><span data-stu-id="dcba5-349">TestEventProcessorFactory processorFactory = new TestEventProcessorFactory();</span></span>
            
                <span data-ttu-id="dcba5-350">Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};</span><span class="sxs-lookup"><span data-stu-id="dcba5-350">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                
                <span data-ttu-id="dcba5-351">"await" subscriberGroup.RegisterProcessorFactoryAsync (Lease, neue TestCheckpointManager() ProcessorFactory); }</span><span class="sxs-lookup"><span data-stu-id="dcba5-351">await subscriberGroup.RegisterProcessorFactoryAsync(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.RegisterProcessorFactoryAsync (lease, checkpointManager, eventProcessorFactory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-352">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-352">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="dcba5-353">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-353">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="dcba5-354">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-354">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="dcba5-355">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-355">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="dcba5-356">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-356">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-357">Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</span><span class="sxs-lookup"><span data-stu-id="dcba5-357">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="dcba5-358">TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();</span><span class="sxs-lookup"><span data-stu-id="dcba5-358">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="dcba5-359">Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};</span><span class="sxs-lookup"><span data-stu-id="dcba5-359">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="dcba5-360">subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }</span><span class="sxs-lookup"><span data-stu-id="dcba5-360">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="StartOfStream">
      <MemberSignature Language="C#" Value="public const string StartOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string StartOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Const StartOfStream As String " />
      <MemberSignature Language="F#" Value="val mutable StartOfStream : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />
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
            <span data-ttu-id="dcba5-361">Die Konstante, die kennzeichnet den Beginn eines Datenstroms.</span><span class="sxs-lookup"><span data-stu-id="dcba5-361">The constant that denotes the start of a stream.</span></span> <span data-ttu-id="dcba5-362">Dies kann als Argument Offset im Erstellen von remoteereignisempfängern verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="dcba5-362">This can be used as an offset argument in receiver creation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                <span data-ttu-id="dcba5-363">Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.</span><span class="sxs-lookup"><span data-stu-id="dcba5-363">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="dcba5-364">Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="dcba5-364">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="dcba5-365">Beschreibung der EventHubDescription;</span><span class="sxs-lookup"><span data-stu-id="dcba5-365">EventHubDescription description;</span></span>
                
                <span data-ttu-id="dcba5-366">EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.StartOfStream);</span><span class="sxs-lookup"><span data-stu-id="dcba5-366">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.StartOfStream);</span></span>
                
                <span data-ttu-id="dcba5-367">Var EventData = Empfänger. Receive();</span><span class="sxs-lookup"><span data-stu-id="dcba5-367">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="UnregisterProcessor">
      <MemberSignature Language="C#" Value="public void UnregisterProcessor (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnregisterProcessor(class Microsoft.ServiceBus.Messaging.Lease lease, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="F#" Value="member this.UnregisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.CloseReason -&gt; unit" Usage="eventHubConsumerGroup.UnregisterProcessor (lease, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-368">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-368">Partition information.</span></span></param>
        <param name="reason"><span data-ttu-id="dcba5-369">Grund für die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="dcba5-369">Reason for which <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> was called.</span></span></param>
        <summary><span data-ttu-id="dcba5-370">Hebt die Registrierung <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-370">Unregisters <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />.</span></span> <span data-ttu-id="dcba5-371">Dies führt zu <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> für den zugrunde liegenden Ereignisprozessor aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="dcba5-371">This results in <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> being called on the underlying event processor.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterProcessorAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterProcessorAsync(class Microsoft.ServiceBus.Messaging.Lease lease, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="F#" Value="member this.UnregisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.CloseReason -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.UnregisterProcessorAsync (lease, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="dcba5-372">Partitionsinformationen.</span><span class="sxs-lookup"><span data-stu-id="dcba5-372">Partition information.</span></span></param>
        <param name="reason"><span data-ttu-id="dcba5-373">Grund <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="dcba5-373">Reason that <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> was called.</span></span></param>
        <summary><span data-ttu-id="dcba5-374">Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span><span class="sxs-lookup"><span data-stu-id="dcba5-374">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span></span></summary>
        <returns><span data-ttu-id="dcba5-375">Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="dcba5-375">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>