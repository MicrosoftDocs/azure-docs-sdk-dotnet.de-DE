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
    <summary>Stellt die consumergruppe innerhalb eines Event Hubs dar. Diese Klasse wird für eine bestimmte consumergruppe innerhalb eines Event Hubs Empfänger erstellt. Dies kann die standardconsumergruppe oder eine andere benutzerdefinierte consumergruppe sein.</summary>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> -Objekt, das an der angegebenen Partition des Event Hubs gebunden ist.</returns>
        <remarks>Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert hat, diese Überladung wird immer Throw InvalidOperationException Prüfpunkt ConsumerGroup aktiviert Quellformat, sodass Epoche funktioniert (verwenden Sie die Überladung, die als Eingabeargument Epoche angeben). Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />.</exception>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingDateTimeUtc">Die UTC-Startzeit zum Empfangen von Nachrichten.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition, beginnend am angegebenen Datum und Uhrzeit. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</returns>
        <remarks>Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.
            
            Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />, mit einer <paramref name="startingDateTimeUtc" /> angegebenen.</exception>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition und den Wert der angegebenen Epoche. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</returns>
        <remarks>Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert, hat, der Empfänger die nächste Nachricht vom Prüfpunkt Offset erhalten. Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Wird ausgelöst, wenn die Anzahl der Empfänger, der der Partition angegeben werden, indem Sie derzeit verbunden <paramref name="partitionId" /> überschreitet die maximal zulässige Kontingent, die vom Dienst festgelegt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Derzeit wird ausgelöst, wenn ein Empfänger für die Partition entsprechend den Angaben von verbunden <paramref name="partitionId" />, mit einer <paramref name="startingOffset" /> angegebenen.</exception>
        <code>
                Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.
                
                Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.
                Beschreibung der EventHubDescription;
                
                EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.StartOfStream);
                
                Var EventData = Empfänger. Receive();
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingDateTimeUtc">Die UTC-Startzeit zum Empfangen von Nachrichten.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition, beginnend am angegebenen Datum und Uhrzeit. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</returns>
        <remarks>Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.
            
            Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="offsetInclusive">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass die erste <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
            Ereignis zurückgegeben wird das Ereignis, das den Anfangsoffset enthält. Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</param>
        <param name="receiverOptions">To be added.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />zurück.</returns>
        <remarks>To be added.</remarks>
        <code>
                Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus der ersten Partitionen die standardconsumergruppe. Es wird verwendet, / / ein zuvor gespeicherter Offset als ab offset und das Ereignis zurück / / als Erstes Ereignis
                
                Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.
                Darüber hinaus vorausgesetzt, dass Benutzer die gespeicherte Offset EventHubDescription Beschreibung abgerufen hat; eine Zeichenfolge StoredOffset = "2478";
                
                EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() StoredOffset);
                
                EventData wird der offset haben == StoredOffset Var EventData = Empfänger. Receive();
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden. Der Anfang des Streams angeben zu können, finden Sie unter <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="partitionId" /> liegt nicht innerhalb des erwarteten Bereichs, als durch die <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> Eigenschaft.</exception>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="offsetInclusive">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält. Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Erstellt einen neuen Event Hubs-Empfänger in der angegebenen Partition aus, auf dem angegebenen Startoffset. Können Sie zum Empfangen von Ereignissen für eine Partition Event Hubs, die gemäß den erstellten Empfänger <paramref name="partitionId" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />zurück.</returns>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert hat, diese Überladung wird immer Throw InvalidOperationException Prüfpunkt ConsumerGroup aktiviert Quellformat, sodass Epoche funktioniert (verwenden Sie die Überladung, die als Eingabeargument Epoche angeben). Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</remarks>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingDateTimeUtc">Die UTC-Startzeit zum Empfangen von Nachrichten.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>Dienst diese Option nur verwenden <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.
            
            Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</remarks>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>Wenn die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Prüfpunkt aktiviert, hat, der Empfänger die nächste Nachricht vom Prüfpunkt Offset erhalten. Wenn Prüfpunkt deaktiviert ist, wird dann Empfänger vom Beginn des ereignisdatenstroms, Meldung gemäß der Aufbewahrungsrichtlinie für die Meldung des Event Hubs.</remarks>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingDateTimeUtc">Die UTC-Startzeit zum Empfangen von Nachrichten.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>Dienst wird nur verwendet, dies <paramref name="startingDateTimeUtc" /> als Näherungswert beim Bestimmen des nächsten Ereignisses zu übermitteln.
            
            Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</remarks>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="offsetInclusive">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält. Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
        <code>
                Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus der ersten Partitionen die standardconsumergruppe. Es wird verwendet, / / ein zuvor gespeicherter Offset als ab offset und das Ereignis zurück / / als Erstes Ereignis
                
                Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.
                Darüber hinaus vorausgesetzt, dass Benutzer die gespeicherte Offset EventHubDescription Beschreibung abgerufen hat; eine Zeichenfolge StoredOffset = "2478";
                
                EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() StoredOffset);
                
                EventData wird der offset haben == StoredOffset Var EventData = Empfänger. Receive();
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden. Der Anfang des Streams angeben zu können, finden Sie unter <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
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
        <param name="partitionId">Die ID der Partition.</param>
        <param name="startingOffset">Der Startoffset an der mit dem Nachrichten empfangen werden.</param>
        <param name="offsetInclusive">Ein boolescher Wert, der angibt, ob <paramref name="startingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält. Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</param>
        <param name="epoch">Der Epoch-Wert. Der Dienst verwendet diesen Wert zum Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
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
            Der Name der standardmäßigen ConsumerGroup, die beim Erstellen der EventHub vorab erstellte ist.
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
        <summary> Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value> "true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> mit <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />. </value>
        <remarks>Der Standardwert wird aus dem Wert des abgeleitet.<see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></remarks>
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
            Die Konstante, die das Ende eines Streams kennzeichnet. Dies kann als Argument Offset im Erstellen von remoteereignisempfängern zum Starten empfangen aus dem letzten Ereignis, anstelle von einem bestimmten Zeitpunkt im Zeit-Offset-Wert verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.
                
                Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.
                Beschreibung der EventHubDescription;
                
                EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.EndOfStream);
                
                Var EventData = Empfänger. Receive();
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
        <summary>Ruft den Pfad der Ereignis-Hub.</summary>
        <value>Der Pfad der Ereignis-hub</value>
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
        <summary>Ruft den Namen der Gruppe "Consumer".</summary>
        <value>Der Name der Gruppe "Consumer".</value>
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
        <summary>Ruft ab oder legt sie fest, werden die Anzahl der Ereignisse, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert. Dieser Wert wird standardmäßig von geerbt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />. Der Standardwert ist 10.000.</summary>
        <value>Die Anzahl der Ereignisse, die der Empfänger zwischenspeichern können.</value>
        <remarks>Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> erstellt, die von dieser Instanz wird dieser Wert standardmäßig erben.
            Änderungen an dieser Wert ist nicht auf bereits erstellte Empfänger übertragen, aber verwendet werden, indem Sie neue <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> nach der Änderung erstellt wurden. Auch wenn diese Eigenschaft auf NULL festgelegt werden <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" /> auf Null.
            Beachten Sie, dass die Anzahl die zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Wert kleiner als der erforderliche Mindestwert von 10 ist.</exception>
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
        <summary>Ruft ab oder legt sie fest, werden die maximale Größe (in Bytes), insgesamt, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert. Die Größe der einzelnen Ereignisdaten richtet sich nach der <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> Eigenschaft.</summary>
        <value>Gibt <see cref="T:System.Int64" />zurück.</value>
        <remarks>Das Größenlimit handelt es sich nicht um einen absoluten Begrenzung. die Größe möglicherweise Anpassungsvorgang Folgendes zu einer Größe von mindestens eine Ereignisdaten wechseln. Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> erstellt, die von dieser Instanz wird dieser Wert standardmäßig erben.
            Änderungen an dieser Wert ist nicht auf bereits erstellte Empfänger übertragen, aber verwendet werden, indem Sie neue <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> nach der Änderung erstellt wurden. Auch wenn diese Eigenschaft auf Null-Wert festgelegt wird, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" /> auf 0 (null).
            Beachten Sie, dass die Größe zu niedrig festlegen beeinflussen die Wirksamkeit des Event Hubs Aufruf empfangen wird.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Größenwert kleiner als der erforderliche Mindestwert von 260 KB ist.</exception>
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
        <typeparam name="T">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <summary>Registriert eine Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen von Event Hubs für den angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> beginnend <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />. Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</summary>
        <remarks>Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</remarks>
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
        <typeparam name="T">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</param>
        <summary>Registriert eine Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen von Event Hubs für den angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> beginnend <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />. Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</summary>
        <remarks>Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</remarks>
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
        <typeparam name="T">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</summary>
        <returns>Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</returns>
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
        <typeparam name="T">Implementierung von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</typeparam>
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</returns>
        <remarks>Erweiterte ausführen <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> erstellen, implementieren Sie eine <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Klasse die können Sie steuern, wie ein Ereignis Prozessoren erstellt werden.</remarks>
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="eventProcessorFactory">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</param>
        <summary>Registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Objekt zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, beginnend ab dem <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />. Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</summary>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();
                 
                Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};
                 
                 subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="eventProcessorFactory">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</param>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</param>
        <summary>Registriert die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> Objekt zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> zum Starten der Nutzen von Ereignissen für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, beginnend ab dem <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />. Verwenden Sie diese Überladung, um eine Ereignisprozessor, Prüfpunkte der Nachricht Offset mithilfe einer benutzerdefinierten Implementierung von erstellen <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</summary>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();
                 
                Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};
                 
                 subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="eventProcessorFactory">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />.</summary>
        <returns>Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <code>
                TestEventProcessorFactory ProcessorFactory = neue TestEventProcessorFactory();
            
                Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};
                
                "await" subscriberGroup.RegisterProcessorFactoryAsync (Lease, neue TestCheckpointManager() ProcessorFactory); }
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="checkpointManager">Prüfpunkte den Offset für den angegebenen partitionieren, wenn <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> aufgerufen wird.</param>
        <param name="eventProcessorFactory">Die Factory zum Erstellen einer Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</param>
        <param name="processorOptions">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />-Objekt.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</returns>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory implementiert IEventProcessorFactory Var ProcessorFactory = neue TestEventProcessorFactory();
                 
                Jeder Shard zu starten, verarbeiten Nachrichten Var SubscriberGroup Ereignisprozessor registrieren = receiveClient.GetDefaultConsumerGroup(); Foreach (Var PartitionId in hubDescription.PartitionIds) {Lease Lease neue Lease() = {PartitionId = PartitionId, Offset = EventHubTestUtils.DefaultStartingOffset};
                 
                 subscriberGroup.RegisterProcessorFactory (Lease, neue TestCheckpointManager() ProcessorFactory); }
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
            Die Konstante, die kennzeichnet den Beginn eines Datenstroms. Dies kann als Argument Offset im Erstellen von remoteereignisempfängern verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                Der folgende Codeausschnitt erstellt einen Empfänger, die Ereignisse empfangen / / aus den ersten Partitionen von der Standardeinstellung Consumer umschlagdienstschemas.
                
                Angenommen Sie, wir die Beschreibung der ermöglicht uns die Partitions-Ids abgerufen haben.
                Beschreibung der EventHubDescription;
                
                EventHubClient Client = EventHubClient.CreateFromConnectionString(connection); Var DefaultGroup = Client. GetDefaultConsumerGroup(); Var-Empfänger = defaultGroup.CreateReceiver (Beschreibung. PartitionIds.First() EventHubConsumerGroup.StartOfStream);
                
                Var EventData = Empfänger. Receive();
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="reason">Grund für die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> aufgerufen wurde.</param>
        <summary>Hebt die Registrierung <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> für die Partition, die vom angegebenen <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />. Dies führt zu <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> für den zugrunde liegenden Ereignisprozessor aufgerufen wird.</summary>
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
        <param name="lease">Partitionsinformationen.</param>
        <param name="reason">Grund <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> aufgerufen wurde.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</summary>
        <returns>Eine Aufgabeninstanz, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>