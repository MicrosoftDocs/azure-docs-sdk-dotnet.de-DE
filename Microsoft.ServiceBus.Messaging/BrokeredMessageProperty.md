<Type Name="BrokeredMessageProperty" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessageProperty : System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessageProperty extends System.Object implements class System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessageProperty&#xA;Implements IMessageProperty" />
  <TypeSignature Language="F#" Value="type BrokeredMessageProperty = class&#xA;    interface IMessageProperty" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IMessageProperty</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Stellt die Eigenschaftensammlung für einen <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessageProperty ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ des Inhalts fest.</summary>
        <value>Der Typ des Inhalts des Nachrichtentexts. Dies ist ein Content-Type-Bezeichner von Sender und Empfänger für anwendungsspezifische Logik verwendet wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Korrelation.</summary>
        <value>Die Korrelations-ID ein.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Anzahl der Lieferungen, die vorgenommen wurden, diese Nachricht zuzustellen.</summary>
        <value>Die Anzahl der Übermittlungen, die vorgenommen wurden, diese Nachricht zuzustellen.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht vom Service Bus nicht zugestellt wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</summary>
        <value>Die in die Warteschlange einzureihen Zeit in UTC. Dieser Wert stellt die tatsächliche Zeit des einreihen der Nachricht.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</summary>
        <value>Die Nachricht Ablaufzeit in UTC.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob die Persistenz für diese Eigenschaft zu erzwingen.</summary>
        <value>"true", um Persistenz für diese Eigenschaft zu erzwingen; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die anwendungsspezifische Bezeichnung.</summary>
        <value>Die anwendungsspezifische Bezeichnung.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</summary>
        <value>Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht aus der Service Bus nicht empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Sperrtoken der Nachricht vom Servicebus zugewiesen.</summary>
        <value>Das Sperrtoken der Nachricht vom Servicebus zugewiesen wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht aus der Service Bus nicht empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die vermittelte Nachricht ab.</summary>
        <value>Das Objekt für vermittelte Nachrichten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Nachricht fest.</summary>
        <value>Der Meldungsbezeichner.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.ArgumentException">Wenn die Nachrichten-ID ist null oder mehr als 128 Zeichen lang sein.</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public static readonly string Name;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Name" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Name As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Name : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
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
            Der Name, die zum Anwenden der Eigenschaftensammlung verwendet eine <see cref="T:System.ServiceModel.Channels.Message" /> beim Senden einer Nachricht.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer transaktionalen Nachricht an eine Warteschlange oder ein Thema, das nicht für Sitzungen aktivierte ist.</summary>
        <value>Gibt <see cref="T:System.String" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Eigenschaften für vermittelte Nachrichten ab.</summary>
        <value>Die Eigenschaften für vermittelte Nachrichten.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Adresse der Warteschlange, an die geantwortet.</summary>
        <value>Die Antwort auf die Adresse.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert die Sitzungs-ID, um zu antworten.</summary>
        <value>Die Sitzungs-ID, an die geantwortet werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden.</summary>
        <value>Die geplante Enqueue-Zeit in UTC. Dieser Wert ist für das verzögerte zu nachrichtensenden. Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wenn der übergebene Wert DateTime.MaxValue ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen.</summary>
        <value>Die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht nicht aus dem e-Mail-Server empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Sitzung fest.</summary>
        <value>Der Bezeichner der Sitzung.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IMessageProperty.CreateCopy">
      <MemberSignature Language="C#" Value="System.ServiceModel.Channels.IMessageProperty IMessageProperty.CreateCopy ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.ServiceModel.Channels.IMessageProperty System.ServiceModel.Channels.IMessageProperty.CreateCopy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.System#ServiceModel#Channels#IMessageProperty#CreateCopy" />
      <MemberSignature Language="VB.NET" Value="Function CreateCopy () As IMessageProperty Implements IMessageProperty.CreateCopy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.IMessageProperty.CreateCopy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IMessageProperty</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Nachricht TTL-Wert. Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht abläuft, beginnend ab dem ab beim Senden der Nachricht an den Dienst Bus.Messages älter ist als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten. Abonnenten werden können abgelaufene Nachrichten empfangen.</summary>
        <value>Die Nachricht Gültigkeitsdauerwert.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wenn der übergebene Wert kleiner oder gleich TimeSpan.Zero.</exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt senden zu Adresse.</summary>
        <value>Die Adresse der Zielwarteschlange.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht im freigegebenen Zustand befindet.</exception>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert für den Partitionsschlüssel wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</summary>
        <value>Gibt <see cref="T:System.String" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>