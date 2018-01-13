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
            Diese Klasse ist eine logische Darstellung zum Senden von Ereignissen an einer bestimmten Event Hub-Partition. Verwenden Sie nicht diese Klasse, wenn keine übertragbaren Senden von Ereignissen an bestimmte Partitionen stattdessen verwenden <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />.
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
            Schließt und frei von Ressourcen für die <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.
            </summary>
        <returns>Ein asynchroner Vorgang</returns>
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
            Ruft die <see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" /> dieser PartitionSender zugeordnet.
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
            Ruft die Partitions-ID für diese <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.
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
        <param name="eventData">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</param>
        <summary>
            Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einer bestimmten Event Hub-Partition. Die Zielpartition wird vorab festgelegt werden, wenn diese PartitionSender erstellt wurde.
            Dieses Muster senden betont Korrelation der Daten über die allgemeine Verfügbarkeit und die Latenz.
            <para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit der Überladung SendBatch) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diesen Typ des Sendeports ein, wenn: <para>ein. Der Client möchte direkte Kontrolle über die Verteilung der Daten auf Partitionen zu übernehmen. In diesem Fall ist der Client dafür verantwortlich, dass Sie sicher, dass mindestens ein Absender pro Ereignis-Hub-Partition vorhanden ist. </para> <para>b. Benutzer nicht mehr als einen Mittelwert direkte von Ereignissen an bestimmte Partition Partitionsschlüssel verwenden, aber für die Datenkorrelation mit Partitionsschema Portkonflikt vorliegt.</para></summary>
        <returns>Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException">die Gesamtgröße der <see cref="T:Microsoft.Azure.EventHubs.EventData" /> überschreitet eine vordefinierte Grenze, die vom Dienst festgelegt. Standardwert ist 256 KB.</exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException">Event Hubs-Dienst Probleme während des Vorgangs an.</exception>
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
        <param name="eventDatas">Batch von Ereignissen an Event Hub senden.</param>
        <summary>
            Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einer bestimmten Event Hub-Partition. Die eingerichteten Partition wird vorab festgelegt werden, wenn diese PartitionSender erstellt wurde.
            <para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, die vom selben Typ des Sendeports und wird verwendet, um die einzelnen senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para>Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen, die an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden mehrerer <see cref="T:Microsoft.Azure.EventHubs.EventData" />des in einer Transaktion. Um die ACID-Eigenschaften zu erreichen, der Gatewaydienst leitet alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des im Batch in einer einzelnen EventHub partitionieren.</para></summary>
        <returns>eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException">die Gesamtgröße der <see cref="T:Microsoft.Azure.EventHubs.EventData" /> überschreitet eine vordefinierte Grenze, die vom Dienst festgelegt. Standardwert ist 256 KB.</exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException">Event Hubs-Dienst Probleme während des Vorgangs an.</exception>
        <example>
            Beispielcode:
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