<Type Name="SBQueue" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBQueue">
  <TypeSignature Language="C#" Value="public class SBQueue : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBQueue extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
  <TypeSignature Language="VB.NET" Value="Public Class SBQueue&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBQueue = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibung der Warteschlange für Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SBQueue-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue (string id = null, string name = null, string type = null, Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Nullable&lt;DateTime&gt; accessedAt = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;long&gt; messageCount = null, Nullable&lt;TimeSpan&gt; lockDuration = null, Nullable&lt;int&gt; maxSizeInMegabytes = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;TimeSpan&gt; defaultMessageTimeToLive = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;TimeSpan&gt; duplicateDetectionHistoryTimeWindow = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Nullable&lt;TimeSpan&gt; autoDeleteOnIdle = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;bool&gt; enableExpress = null, string forwardTo = null, string forwardDeadLetteredMessagesTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;int64&gt; messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDuration, valuetype System.Nullable`1&lt;int32&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultMessageTimeToLive, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoDeleteOnIdle, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;bool&gt; enableExpress, string forwardTo, string forwardDeadLetteredMessagesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional countDetails As MessageCountDetails = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional messageCount As Nullable(Of Long) = null, Optional lockDuration As Nullable(Of TimeSpan) = null, Optional maxSizeInMegabytes As Nullable(Of Integer) = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional defaultMessageTimeToLive As Nullable(Of TimeSpan) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional duplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional status As Nullable(Of EntityStatus) = null, Optional autoDeleteOnIdle As Nullable(Of TimeSpan) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null, Optional forwardTo As String = null, Optional forwardDeadLetteredMessagesTo As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue : string * string * string * Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBQueue" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue (id, name, type, countDetails, createdAt, updatedAt, accessedAt, sizeInBytes, messageCount, lockDuration, maxSizeInMegabytes, requiresDuplicateDetection, requiresSession, defaultMessageTimeToLive, deadLetteringOnMessageExpiration, duplicateDetectionHistoryTimeWindow, maxDeliveryCount, status, autoDeleteOnIdle, enablePartitioning, enableExpress, forwardTo, forwardDeadLetteredMessagesTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="lockDuration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forwardTo" Type="System.String" />
        <Parameter Name="forwardDeadLetteredMessagesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="countDetails">Details zur Nachrichtenanzahl.</param>
        <param name="createdAt">Die genaue Uhrzeit der Erstellung der Nachrichteninhalts.</param>
        <param name="updatedAt">Die genaue Uhrzeit wurde die Nachricht aktualisiert.</param>
        <param name="accessedAt">Letzte Uhrzeit, an eine Nachricht gesendet wurde, bzw. des letzten gab es eine Receive-Anforderung an diese Warteschlange.</param>
        <param name="sizeInBytes">Die Größe der Warteschlange, in Bytes.</param>
        <param name="messageCount">Die Anzahl der Nachrichten in der Warteschlange.</param>
        <param name="lockDuration">ISO 8601 Timespan Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist. Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.</param>
        <param name="maxSizeInMegabytes">Die maximale Größe der Warteschlange in Megabyte an, die die Größe des Arbeitsspeichers für die Warteschlange zugeordnet ist.
            Standardwert ist 1024.</param>
        <param name="requiresDuplicateDetection">Ein Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.</param>
        <param name="requiresSession">Ein Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.</param>
        <param name="defaultMessageTimeToLive">ISO 8601 Standard Nachricht Timespan TTL-Wert. Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft. Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.</param>
        <param name="deadLetteringOnMessageExpiration">Ein Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</param>
        <param name="duplicateDetectionHistoryTimeWindow">ISO 8601 TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert. Der Standardwert ist 10 Minuten.</param>
        <param name="maxDeliveryCount">Die Anzahl maximaler Zustellungen. Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen. Standardwert ist 10.</param>
        <param name="status">Listet die möglichen Werte für den Status einer messaging-Entität an. Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"</param>
        <param name="autoDeleteOnIdle">ISO 8061 TimeSpan leerlaufintervalls nach dem die Warteschlange automatisch gelöscht wird. Die Mindestdauer ist fünf Minuten.</param>
        <param name="enablePartitioning">Ein Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</param>
        <param name="enableExpress">Ein Wert, der angibt, ob die Express-Entitäten aktiviert sind. Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.</param>
        <param name="forwardTo">Name der Warteschlange/Thema zum Weiterleiten von Nachrichten</param>
        <param name="forwardDeadLetteredMessagesTo">Name der Warteschlange/Thema zum Weiterleiten der Nachricht Dead Letter</param>
        <summary>
            Initialisiert eine neue Instanz der SBQueue-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zuletzt eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest ISO 8061 TimeSpan leerlaufintervalls nach dem die Warteschlange automatisch gelöscht wird. Die Mindestdauer ist fünf Minuten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Nachrichtendetails die Anzahl.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deadLetteringOnMessageExpiration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die ISO 8601-Standard Nachricht Timespan TTL-Wert fest. Hierbei handelt es sich um den Zeitraum, nach dem die Nachricht beginnend ab dem Zeitpunkt der Nachricht, um Service Bus gesendet wird abläuft. Dies ist der Standardwert verwendet, wenn TimeToLive nicht für eine Nachricht selbst festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest ISO 8601-TimeSpan-Struktur, die die Zeitspanne des duplikaterkennungsverlaufs definiert. Der Standardwert ist 10 Minuten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableExpress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Express-Entitäten aktiviert sind. Eine express-Warteschlange speichert eine Nachricht im Arbeitsspeicher vorübergehend, bevor sie in den persistenten Speicher geschrieben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enablePartitioning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardDeadLetteredMessagesTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Name der Warteschlange/Thema zum Weiterleiten der Nachricht Dead Letter abgerufen oder festgelegt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Namen von Warteschlange/Thema zum Weiterleiten von Nachrichten
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ISO-8601 Timespan Dauer einer vorschausperre; d. h. die Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.
            Der maximale Wert für die LockDuration ist 5 Minuten. Der Standardwert beträgt 1 Minute.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl maximaler Zustellungen. Eine Nachricht wird automatisch als unzustellbar gekennzeichnet nach dieser Anzahl von Übermittlungen. Standardwert ist 10.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Größe der Warteschlange in Megabyte an, die Größe des Arbeitsspeichers für die Warteschlange ist. Standardwert ist 1024.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.messageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten in der Warteschlange ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresDuplicateDetection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, wenn diese Warteschlange Erkennung doppelten Nachrichten erforderlich sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Warteschlange das Konzept der Sitzungen unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe der Warteschlange, in Bytes ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Listet die möglichen Werte für den Status einer messaging-Entität. Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die genaue Uhrzeit, an die Nachricht aktualisiert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>