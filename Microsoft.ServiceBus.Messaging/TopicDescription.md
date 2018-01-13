<Type Name="TopicDescription" FullName="Microsoft.ServiceBus.Messaging.TopicDescription">
  <TypeSignature Language="C#" Value="public sealed class TopicDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TopicDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TopicDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type TopicDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="TopicDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Eine Beschreibung des Themas darstellt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.TopicDescription : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="new Microsoft.ServiceBus.Messaging.TopicDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> Klasse mit dem angegebenen relativen Pfad.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Zeit und Datum, an dem zuletzt eine Nachricht an das Thema gesendet wurde.</summary>
        <value>Die Uhrzeit und Datum, an dem zuletzt eine Nachricht an das Thema gesendet wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Autorisierungsregeln für die Beschreibung ab.</summary>
        <value>Die Autorisierungsregeln für die Beschreibung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> leerlaufintervalls nach dem Thema automatisch gelöscht. Die Mindestdauer ist fünf Minuten.</summary>
        <value>Das automatische Löschen im Leerlauf Zeitspanne für das Thema.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Status der Verfügbarkeit von dieser Instanz ab.</summary>
        <value>Der Status der Verfügbarkeit von dieser Instanz.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Uhrzeit und Datum, an das Thema erstellt wurde.</summary>
        <value>Die Uhrzeit und Datum, an das Thema erstellt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Standardzeit für die Nachricht TTL-Wert für ein Thema. Hierbei handelt es sich um den Zeitraum, nach dem Ablauf die Nachricht beginnend ab dem Zeitpunkt der Nachricht an den Servicebus gesendet wird. Dies ist die Standardeinstellung Wert wird verwendet, wenn <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> für eine Nachricht selbst nicht festgelegt ist. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten. Abonnenten werden können abgelaufene Nachrichten empfangen.</summary>
        <value>Die Nachricht Standardzeit Gültigkeitsdauer für ein Thema.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</summary>
        <value>Die <see cref="T:System.TimeSpan" /> -Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
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
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind. Ein expressthema speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</summary>
        <value>"true", wenn die Express-Entitäten aktiviert sind; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFilteringMessagesBeforePublishing">
      <MemberSignature Language="C#" Value="public bool EnableFilteringMessagesBeforePublishing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFilteringMessagesBeforePublishing As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableFilteringMessagesBeforePublishing : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob Nachrichten vor der Veröffentlichung gefiltert werden sollen.</summary>
        <value>"true", wenn die nachrichtenfilterung vor der Veröffentlichung aktiviert ist; andernfalls "false".</value>
        <remarks> Dieses Feature wird empfohlen, nur für Entwicklungs- und Testzwecken verwendet werden soll.  
            Wenn an das Thema neue Regeln oder Filter hinzugefügt werden, kann z. B. diese Funktion verwendet werden, stellen Sie sicher, dass der neue Filter-Ausdruck wie erwartet funktioniert. Sobald getestet und einwandfrei funktioniert, sollte die Funktion in der produktionsumgebung deaktiviert werden. </remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException">Wird ausgelöst, wenn die Abonnements nicht übereinstimmen.</exception>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt fest, ob So aktivieren Sie das Thema, um mehrere nachrichtenbroker partitioniert werden. Ein expressthema speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</summary>
        <value>True, aktivieren Sie das Thema, um mehrere nachrichtenbroker partitioniert werden soll. andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, ob anonymer Zugriff zulässig ist.</summary>
        <value>"true", wenn anonymer Zugriff zulässig ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Größe des Themas in Megabyte an, die Größe des Arbeitsspeichers, die für das Thema zugeordnet ist.</summary>
        <value>Die maximale Größe in Megabyte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft Nachrichtendetails zum Thema ab.</summary>
        <value>Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> , enthält die Anzahl der aktiven Nachrichten, unzustellbare Nachrichten, geplante Nachrichten, Nachrichten an andere Warteschlangen, Abonnements oder Themen zu übertragen, und übertragen Sie die Anzahl der Nachrichten an die Dead Letter-Warteschlange.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
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
              Der Zeitpunkt der live-Standardwert
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Pfad des Themas.</summary>
        <value>Der Pfad des Themas.</value>
        <remarks>
              Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Wert, der angibt, ob ein Thema Duplizierung Erkennung erforderlich ist.</summary>
        <value>"true", wenn ein Thema Duplizierung Erkennung erfordert; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Größe des Themas in Bytes ab.</summary>
        <value>Die Größe des Themas in Bytes.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den aktuellen Status des Themas (aktiviert oder deaktiviert) fest. Wenn eine Entität deaktiviert ist, kann keine diese Entität Nachrichten senden oder empfangen.</summary>
        <value>Der Status des Themas.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public int SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : int" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Klicken Sie dann Anzahl der Abonnements ab.</summary>
        <value>Eine <see cref="T:System.Int32" /> , die die Anzahl der Abonnements darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Reihenfolge der Methode Unterstützung.</summary>
        <value>Die Unterstützung, die Reihenfolge der Methode.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Uhrzeit und Datum, an das Thema wurde aktualisiert.</summary>
        <value>Die Uhrzeit und Datum, an das Thema wurde aktualisiert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen der dieser Beschreibung zugeordnete Benutzermetadaten.</summary>
        <value>Die dieser Beschreibung zugeordnete Benutzermetadaten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>