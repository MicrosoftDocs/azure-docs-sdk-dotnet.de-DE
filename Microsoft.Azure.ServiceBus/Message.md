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
            Das Nachrichtenobjekt kommunizieren und Übertragen von Daten mit Service Bus verwendet wird.
            </summary>
    <remarks>
            Die Nachrichtenstruktur wird ausführlich erläutert die <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">-Produktdokumentation.</a></remarks>
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
            Erstellt eine neue Nachricht
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
        <param name="body">Die Nutzlast der Nachricht in bytes</param>
        <summary>
            Erstellt eine neue Nachricht aus der angegebenen Nutzlast an.
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
            Ruft den Nachrichtentext ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die einfachste Möglichkeit zum Erstellen einer neuen Nachricht aus einer Zeichenfolge lautet wie folgt:
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
        <summary>Klont eine Nachricht an, damit, dass es möglich ist, einen Klon einer bereits empfangene Nachricht als eine neue Nachricht zu senden. Die Systemeigenschaften der ursprünglichen Nachricht werden nicht kopiert.</summary>
        <returns>Eine geklonte <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</returns>
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
        <summary>Ermittelt oder definiert den Inhalt von diesem Gebiet vorkommenden Deskriptor.</summary>
        <value>RFC2045 Content-Type-Deskriptor.</value>
        <remarks>
              Beschreibt das optional die Nutzlast der Nachricht, mit der ein Deskriptor, befolgen das Format der RFC2045, Abschnitt 5, z. B. "Application/Json".
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
        <summary>Ruft ab oder legt die Korrelations-ID.</summary>
        <value>Korrelations-ID.</value>
        <remarks>
               Ermöglicht einer Anwendung an einen Kontext für die Nachricht für die Zwecke der Korrelation, z. B. reflektieren die Nachrichten-ID einer Nachricht, die beantwortet wird.
               Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a>.
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
            Ein Schlüssel für Benutzer, die detaillierte fehlerbeschreibung darstellt, wenn eine Nachricht aus einer Entität eine Unterwarteschlange für unzustellbare Nachrichten empfangen wird.
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
            Schlüssel für Benutzer, die für unzustellbare Nachrichten Grund darstellt, wenn eine Nachricht aus einer Entität eine Unterwarteschlange für unzustellbare Nachrichten empfangen wird.
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
        <summary>Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</summary>
        <value>Die Nachricht Ablaufzeit in UTC. Diese Eigenschaft ist schreibgeschützt.</value>
        <remarks>
             Der UTC-Moment, in dem die Nachricht zum Entfernen markiert wird und wegen Ablaufs nicht mehr von der Entität abgerufen werden kann. Ablauf wird gesteuert, indem die <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> und dieser Eigenschaft wird von berechnet.<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></remarks>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht nicht empfangen wurde. Für das Beispiel wurde jedoch keine neue Nachricht erstellt noch gesendet und empfangen.</exception>
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
        <summary>Ruft ab oder legt eine anwendungsspezifische Bezeichnung.</summary>
        <value>Die anwendungsspezifische Bezeichnung</value>
        <remarks>
              Diese Eigenschaft ermöglicht der Anwendung, dem Empfänger auf standardisierte Weise den Zweck der Nachricht anzuzeigen, ähnlich einer Betreffzeile für E-Mails. Die zugeordnete AMQP-Eigenschaft ist "Betreff".
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
            Ruft ab oder legt die Nachrichten-ID zur Identifizierung der Nachrichteninhalts.
            </summary>
        <value>To be added.</value>
        <remarks>
               Der Nachrichtenbezeichner ist ein von der Anwendung definierter Wert, der die Nachricht und ihre Nutzlast eindeutig identifiziert. Der Bezeichner ist eine Zeichenfolge in freier Form und kann eine GUID oder einen aus dem Anwendungskontext abgeleiteten Bezeichner widerspiegeln. Wenn aktiviert, die <a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">duplikaterkennung</a> Funktion identifiziert und entfernt Sekunde und weitere Übermittlung von Nachrichten mit der gleichen MessageId.
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
        <summary>Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer Nachricht an eine partitionierte Entität.</summary>
        <value>der Partitionsschlüssel. Maximale Länge beträgt 128 Zeichen.</value>
        <remarks>
               Für <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">partitionierte Entitäten</a> ermöglicht das Festlegen dieses Werts, verwandte Nachrichten derselben internen Partition zuzuweisen, sodass die Reihenfolge der Übermittlung ordnungsgemäß aufgezeichnet wird. Die Partition wird von einer Hashfunktion über diesen Wert ausgewählt und kann nicht direkt ausgewählt werden. Für Sitzungen aktivierte Entitäten die <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> Eigenschaft überschreibt diesen Wert.
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
        <summary>Ruft ab oder legt die Adresse einer Entität zum Senden von Antworten an.</summary>
        <value>Die Antwortadresse für die Entität.</value>
        <remarks>
               Dieser optionale und von der Anwendung definierte Wert ist eine Standardmethode, einen Antwortpfad zum Empfänger der Nachricht auszudrücken. Wenn ein Absender eine Antwort erwartet, legt er den Wert auf den absoluten oder relativen Pfad der Warteschlange oder des Themas fest, an den bzw. das die Antwort gesendet werden soll.
               Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a>.
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
        <summary>Ruft ab oder legt sie fest, eine Sitzung Bezeichner erweitern die <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" /> Adresse.</summary>
        <value>Sitzungs-ID. Maximale Länge beträgt 128 Zeichen.</value>
        <remarks>
               Dieser Wert die ReplyTo-Informationen ergänzt und gibt an, welche die "SessionId" für die Antwort beim Senden an die Antwort-Entität festgelegt werden soll. Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">Nachrichtenrouting und Korrelation</a></remarks>
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
        <summary>Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden. Diese Eigenschaft gibt die Zeit in UTC; Wenn die Eigenschaft festlegen, muss der angegebene DateTime-Wert auch in UTC.</summary>
        <value>Die geplante Enqueue-Zeit in UTC. Dieser Wert ist für das verzögerte zu nachrichtensenden.
            Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</value>
        <remarks> Zeitpunkt der einreihen bedeutet nicht, dass die Nachricht zur gleichen Zeit gesendet wird. Erhalten sie in die Warteschlange eingereiht, aber tatsächliche sendende erforderliche Zeit hängt von der Warteschlange arbeitsauslastung und den Zustand.</remarks>
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
        <summary>Ermittelt oder definiert die Sitzungs-ID für einen sitzungsfähigen Entität.</summary>
        <value>Die Sitzungs-ID. Maximale Länge beträgt 128 Zeichen.</value>
        <remarks>
               Bei sitzungsabhängigen Entitäten gibt dieser von der Anwendung definierte Wert die Sitzungszugehörigkeit der Nachricht an. Nachrichten mit demselben Sitzungsbezeichner unterliegen einer zusammenfassenden Sperre und ermöglichen eine Verarbeitung in exakter Reihenfolge und Demultiplexing. Bei nicht sitzungsabhängigen Entitäten wird dieser Wert ignoriert.
               Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">Nachricht Sitzungen</a>.
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
            Ruft die Gesamtgröße des Nachrichtentexts in Bytes ab.
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
            Ruft die <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />, dient zum Speichern von Eigenschaften, die vom System festgelegt werden.
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
            Ruft ab oder legt die Nachricht "time to live" Wert. 
            </summary>
        <value>Die Nachricht Gültigkeitsdauerwert.</value>
        <remarks>
                Dieser Wert ist die relative Dauer, die nach dem die Nachricht abläuft, beginnend mit den Zeitpunkt der Nachrichteninhalts akzeptiert und durch den Broker gespeichert werden, da in erfasst wurde <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />. Wenn nicht explizit festlegen, wird der angenommene Wert der DefaultTimeToLive für den betreffenden Warteschlange oder ein Thema. Eine auf Nachrichtenebene <see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /> Wert darf nicht länger als die Entität DefaultTimeToLive-Einstellung, und es wird automatisch angepasst, wenn dies der Fall ist. Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">Ablauf</a></remarks>
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
        <summary>Ruft ab oder legt die Adresse "zu" fest.</summary>
        <value>Die Adresse "to".</value>
        <remarks>
               Diese Eigenschaft ist für die künftige Verwendung in Routingszenarien reserviert und wird derzeit vom Broker selbst ignoriert. Clientanwendungen können diesen Wert verwenden, in der Regel gesteuerte <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">Auto-vorwärtsverkettungs</a> Szenarien an, dass das vorgesehene logische Ziel der Nachricht.
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
        <summary>Gibt eine Zeichenfolge, die die aktuelle Nachricht darstellt.</summary>
        <returns>Die Zeichenfolgendarstellung der aktuellen Nachricht.</returns>
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
            Ruft die Sammlung "Benutzereigenschaften", die für die benutzerdefinierte Meldung Metadaten verwendet werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
            Nur nach Wert Typen werden unterstützt: Byte, Sbyte, Char, Short, Ushort, Int, "uint", long, Ulong, Float, double, Decimal, Bool, Guid, Zeichenfolge, Uri, "DateTime", "DateTimeOffset", TimeSpan, Stream, Byte [] und IList / IDictionary von unterstützte Typen
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
        <summary>Ermittelt oder definiert einen Partitionsschlüssel zum Senden einer Nachricht in eine Entität über eine partitionierte Übertragungswarteschlange.</summary>
        <value>der Partitionsschlüssel. Maximale Länge beträgt 128 Zeichen. </value>
        <remarks>
               Wenn über eine Übertragungswarteschlange im Rahmen einer Transaktion eine Nachricht gesendet wird, wird dieser Wert die Übertragung Warteschlange Partition ausgewählt: Dies ist funktionell gleichwertig mit <see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" /> und stellt sicher, dass Nachrichten zusammen und in Reihenfolge gespeichert sind, wie sie übertragen werden.
               Finden Sie unter <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">übertragen, und senden Sie über</a>.
               </remarks>
      </Docs>
    </Member>
  </Members>
</Type>