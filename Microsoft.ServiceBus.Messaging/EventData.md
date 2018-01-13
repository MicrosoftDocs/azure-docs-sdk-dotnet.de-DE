<Type Name="EventData" FullName="Microsoft.ServiceBus.Messaging.EventData">
  <TypeSignature Language="C#" Value="public sealed class EventData : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventData extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventData" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventData = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Stellt das Ereignis gesendet und empfangen, die aus einem Datenstrom Event Hubs. Es enthält den Text des Ereignisses, einen benutzerdefinierten Eigenschaftenbehälter sowie verschiedene Metadaten, die Beschreibung des Ereignisses, z. B. der Offset in der Partition und die Nummer in der datenstromsequenz. Partitionen werden mit einer Sequenz von Ereignisdaten gefüllt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : byte[] -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray">Das Ereignis Daten Bytearray, das verwendet wird, um den Antworttext-Datenstrom zu bilden.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die das angegebene Bytearray als Text verwendet.</summary>
        <remarks>Wenn EventData senden, sollten Sie Eingabebytearrays als unveränderlich behandeln. 
            
            Beim Senden von Daten als auch alle Klonvorgang wird Service Bus dem Bytearray Verweis stattdessen, die tiefe Kopie des Byte-Arrays zugreifen, indem. Auch löschen, mit der EventData-Instanz wird nur die Zuordnung mit dem Array dereferenzieren. Der Benutzer ist verantwortlich für den Lebenszyklus des Bytearrays selbst.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; arraySegments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; arraySegments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Collections.Generic.IList{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (arraySegments As IList(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.Collections.Generic.IList&lt;ArraySegment&lt;byte&gt;&gt; -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData arraySegments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="arraySegments" Type="System.Collections.Generic.IList&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="arraySegments">IList der Array-Segmente als Text an den <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.
            </param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die die angegebene Liste von bytearraysegmenten als Nachrichtentext verwendet.</summary>
        <remarks>Benutzer in der Regel IList verwendet&lt;ArraySegment&lt;Byte&gt; &gt; Verwendung sein eigenes Pufferpool für Szenarien, die eine effiziente Nutzung von Arbeitsspeicher erfordern.
            
            Beim Senden von Daten als auch alle Klonvorgang wird Service Bus die Array-Segmente Verweis stattdessen, die tiefe Kopie der Bytes zugreifen, indem. 
            
            Freigeben der EventData-Instanz wird nur die Zuordnung mit der Liste dereferenzieren. Benutzer ist für den Lebenszyklus der Array-Segmente selbst verantwortlich.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">Ein Datenstrom, der als Antworttext-Datenstrom verwendet wird.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Klasse, die den Datenstrom Argument wie der Textstream verwendet.</summary>
        <remarks>Benutzer muss Besitzer der Freigabe des Datenstroms für die Verwendung dieses Konstruktors.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (object content, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object content, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventData : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="new Microsoft.ServiceBus.Messaging.EventData (content, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="content">.NET-Objekt</param>
        <param name="serializer">das Serialisierungsprogramm zur Serialisierung verwendet<paramref name="content" /></param>
        <summary>
            Der Konstruktor nimmt Eingabe Inhalt und Serialisierungsprogramm den Antworttext-Datenstrom zu erstellen.
            </summary>
        <remarks>Wenn Inhalt ist einen Datenstrom und Seriazlier null, ist es gleichgesetzt verwenden<see cref="M:Microsoft.ServiceBus.Messaging.EventData.#ctor(System.IO.Stream)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventData" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventData.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Stellt eine tiefe Kopie des Diese Ereignisdaten an.</summary>
        <returns>Eine Kopie dieser Ereignisdaten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventData.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Führt anwendungsspezifische Aufgaben durch, die mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zusammenhängen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventData.EnqueuedTimeUtc" />
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
        <value>Die in die Warteschlange einzureihen Zeit in UTC. Dieser Wert stellt die tatsächliche Zeit des setzen die Ereignisdaten an.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="eventData.GetBodyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft ab oder legt den zugrunde liegenden Stream auf der Ereignistext Daten fest.</summary>
        <returns>Der zugrunde liegende Stream, der dem Textteil der Ereignis-Daten.</returns>
        <remarks>Diese Methode kann nur einmal aufgerufen werden, und anschließend Methode löst <see cref="T:System.InvalidOperationException" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventData.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="eventData.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft das Ereignis in Byte ab.</summary>
        <returns>Die Ereignis-Datenbytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.ServiceBus.Messaging.EventData.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Offset der Daten relativ zu den Event Hub-Partition-Stream ab. Der Offset ist eine Marke oder einen Bezeichner für ein Ereignis innerhalb des Event Hubs-Streams. Der Bezeichner ist eindeutig innerhalb einer Partition des Event Hubs-Streams.</summary>
        <value>Der gelesenen Offset der Daten für das Ereignis.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventData.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Schlüssel, der verwendet wird, um zu bestimmen, zu welcher Partition die Ereignisdaten gesendet.</summary>
        <value>Der Partitionsschlüssel für die Partition mit der Daten gesendet werden sollen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Eigenschaften der Daten für das Ereignis, dass der Benutzer, die ausdrücklich hinzugefügt wurden, während der Vorgänge zu senden.</summary>
        <value>Die Eigenschaften der Daten für das Ereignis.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Anzahl der logischen Reihenfolge des Ereignisses innerhalb des Streams Partition des Event Hubs ab.</summary>
        <value>Die Anzahl der logischen Reihenfolge des Ereignisses.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializedSizeInBytes">
      <MemberSignature Language="C#" Value="public long SerializedSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SerializedSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializedSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SerializedSizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.EventData.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Systemeigenschaften, einschließlich der Daten für das Ereignis.</summary>
        <value>Die Systemeigenschaften, einschließlich der Daten für das Ereignis.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>