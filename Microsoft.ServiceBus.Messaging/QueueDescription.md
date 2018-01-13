<Type Name="QueueDescription" FullName="Microsoft.ServiceBus.Messaging.QueueDescription">
  <TypeSignature Language="C#" Value="public sealed class QueueDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type QueueDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="QueueDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die Metadatenbeschreibung der Warteschlange.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QueueDescription : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="new Microsoft.ServiceBus.Messaging.QueueDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Namespace.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> Klasse mit dem angegebenen relativen Pfad.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das letzte Mal eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.</summary>
        <value>Das letzte Mal eine Receive-Anforderung an diese Warteschlange wurde, oder das letzte Mal eine Nachricht gesendet wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ab.</summary>
        <value>Die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> leerlaufintervalls nach dem die Warteschlange automatisch gelöscht. Die Mindestdauer ist fünf Minuten.</summary>
        <value>Das automatische Löschen im Leerlauf Zeitspanne für die Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Verfügbarkeitsstatus für die Entität für die Warteschlange ab.</summary>
        <value>Der Status der Entität Verfügbarkeit für die Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.</summary>
        <value>Der Zeitpunkt, an die Nachricht erstellt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert. Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft. Dies ist die Standardeinstellung Wert wird verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> für eine Nachricht selbst nicht festgelegt ist. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten. Abonnenten werden können abgelaufene Nachrichten empfangen. Eine Nachricht kann einen niedrigeren TimeToLive-Wert als die hier angegebene aufweisen, aber standardmäßig TimeToLive festgelegt ist, um <see cref="F:System.TimeSpan.MaxValue" />. Aus diesem Grund wird diese Eigenschaft die Standardzeit TTL-Wert auf Nachrichten angewendet.</summary>
        <value>Die Nachricht Standardzeit TTL-Wert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert. Der Standardwert ist 10 Minuten.</summary>
        <value>Die <see cref="T:System.TimeSpan" /> -Struktur, die Zeitfenster für Verlauf der duplikaterkennung Duplizierung darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob serverseitige Batchvorgänge aktiviert werden.</summary>
        <value>"true", wenn der Batch-Vorgänge aktiviert sind; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</summary>
        <value>True, wenn die Warteschlange für unzustellbare Support bei Ablauf einer Nachricht; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind. Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</summary>
        <value>"true", wenn die Express-Entitäten aktiviert sind; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange, die mehrere nachrichtenbroker partitioniert werden aktiviert ist. </summary>
        <value>"true", wenn die Warteschlange, die mehrere nachrichtenbroker partitioniert werden aktiviert ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachricht weitergeleitet wird.</summary>
        <value>Der Pfad für den Empfänger, an dem die Warteschlange für unzustellbare Nachrichten mit Buchstaben gekennzeichneten Nachricht weitergeleitet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Pfad fest, an den Empfänger, an dem die Nachricht weitergeleitet wird.</summary>
        <value>Der Pfad für den Empfänger, an dem die Nachricht weitergeleitet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Nachricht anonym ist zugegriffen werden kann.</summary>
        <value>"true", wenn die Nachricht anonym ist zugegriffen werden kann; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist. Der Höchstwert für <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> beträgt fünf Minuten; der Standardwert beträgt 1 Minute.</summary>
        <value>Die Dauer der Sperre.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl maximaler Zustellungen. Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen.</summary>
        <value>Die Anzahl der maximale Übermittlungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Größe der Warteschlange in Megabyte an, die Größe des Arbeitsspeichers für die Warteschlange ist.</summary>
        <value>Die maximale Größe der Warteschlange in Megabyte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Anzahl der Nachrichten in der Warteschlange ab.</summary>
        <value>Die Anzahl der Meldungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Details für eine Warteschlange.</summary>
        <value>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> mit der Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten, die auf andere Warteschlangen, Abonnements oder Themen übertragen. anschließend übertragen Sie die Anzahl der Nachrichten an die Dead Letter-Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
              Der Zeitpunkt der live Standardwert in bytes
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen der Warteschlange fest.</summary>
        <value>Der Name der Warteschlange.</value>
        <remarks>
              Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</summary>
        <value>True, wenn diese Warteschlange muss die Erkennung von Duplikaten; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange das Konzept der Sitzung unterstützt.</summary>
        <value>"true", wenn der empfängeranwendung nur aus der Warteschlange über erhalten kann eine <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false, wenn eine Warteschlange empfangen kann mit <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Größe der Warteschlange in Bytes ab.</summary>
        <value>Die Größe der Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den aktuellen Status der Warteschlange (aktiviert oder deaktiviert) fest. Wenn eine Entität deaktiviert ist, kann keine diese Entität Nachrichten senden oder empfangen.</summary>
        <value>Der aktuelle Status der Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange Sortierung unterstützt.</summary>
        <value>"true", wenn die Warteschlange unterstützt Sortierung; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die genaue Uhrzeit, zu der die Nachricht aktualisiert wurde.</summary>
        <value>Der Zeitpunkt, zu die Nachricht aktualisiert wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Benutzermetadaten.</summary>
        <value>Die Benutzermetadaten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>