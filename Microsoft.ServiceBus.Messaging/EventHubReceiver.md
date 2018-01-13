<Type Name="EventHubReceiver" FullName="Microsoft.ServiceBus.Messaging.EventHubReceiver">
  <TypeSignature Language="C#" Value="public sealed class EventHubReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubReceiver = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Eine Clientklasse, die zur Verwendung in empfangen Vorgänge im Zusammenhang mit einem Event Hub-consumergruppe. Stellt eine logische Empfänger-Verbindung zu einer bestimmten Event Hub-Partition in einer consumergruppe.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Epoche-Wert, der verwendet wird, um die Partition des Besitzes während der Empfangsvorgang zu bestimmen.</summary>
        <value>Gibt <see cref="T:System.Int64" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
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
        <value>Der Pfad für den Ereignis-Hub.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Bezeichner der Empfänger die während der Erstellung des Empfängers festgelegt wurde.</summary>
        <value>Eine Zeichenfolge, die den Bezeichner darstellt, der einen Empfänger. Es zurück null, wenn der Bezeichner nicht festgelegt ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Namen des Event Hubs.</summary>
        <value>Der Name des Event Hubs.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="public bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der angibt, ob <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" /> wird behandelt, als inklusive Offset, was bedeutet, dass das erste Ereignis zurückgegeben, das Ereignis ist, das den Anfangsoffset enthält. Normalerweise ist das erste Ereignis zurückgegeben, das Ereignis nach der Startoffset.</summary>
        <value>Gibt <see cref="T:System.Boolean" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubReceiver.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginClose (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginOpen (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndClose result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndOpen result" />
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
    <Member MemberName="OnOpen">
      <MemberSignature Language="C#" Value="protected override void OnOpen (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnOpen(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnOpen timeout" />
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
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Partitions-ID für eine logische Partition einen Event Hub ab.</summary>
        <value>Die Partitions-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, werden die Anzahl der Ereignisse, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert. Dieser Wert wird standardmäßig von geerbt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />. Der Standardwert ist 300.</summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks> Änderungen an dieser Wert werden bei der nächsten verwendet Empfangsvorgang, aber dadurch die Anzahl der Ereignisse, die bereits im Cache vom Empfänger nicht beeinträchtigt wird. Wenn diese Eigenschaft auf NULL-Wert wird festgelegt, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" /> auf Null.
            Beachten Sie, dass die Anzahl die zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Wert kleiner als der erforderliche Mindestwert von 10 ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
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
        <remarks>Das Größenlimit handelt es sich nicht um einen absoluten Begrenzung. die Größe möglicherweise Anpassungsvorgang Folgendes zu einer Größe von mindestens eine Ereignisdaten wechseln. Änderungen an dieser Wert werden bei der nächsten verwendet Empfangsvorgang, aber dadurch die Anzahl der Ereignisse, die bereits im Cache vom Empfänger nicht beeinträchtigt wird. Wenn diese Eigenschaft auf Null-Wert wird festgelegt, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" /> auf 0 (null).
            Beachten Sie, dass die Größe zu niedrig festlegen die Wirksamkeit des Event Hubs auswirkt erhalten Anruf.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Größenwert kleiner als der erforderliche Mindestwert von 260 KB ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive " />
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
        <summary>Empfängt Daten von Event Hubs-Ereignis.</summary>
        <returns>Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> -Objekt oder null, wenn keine Ereignisdaten verfügbar ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</param>
        <summary>Empfängt Event Hubs-Ereignisdaten, bis die angegebene Anzahl an.</summary>
        <returns>Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung. Die Auflistung ist entweder leer, wenn kein Ereignis wird innerhalb der angegebenen Zeit oder alle Ereignisse zurückgegeben, bis zu <paramref name="maxCount" /> werden zurückgegeben.</returns>
        <remarks>Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben. Wird zurückgegeben, sobald Ereignisse vorhanden sind.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (waitTime As TimeSpan) As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</param>
        <summary>Empfängt Daten von Event Hubs-Ereignis mit dem angegebenen Timeoutwert an.</summary>
        <returns>Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung oder Null, wenn es keine Ereignisdaten verfügbar ist.</returns>
        <remarks>
          <paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer, waitTime As TimeSpan) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</param>
        <param name="waitTime">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</param>
        <summary>Empfängt Event Hubs-Ereignisdaten, bis die angegebene Anzahl mit dem angegebenen Timeoutwert an.</summary>
        <returns>Gibt die empfangenen Daten <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Auflistung. Die Auflistung ist entweder leer, wenn kein Ereignis wird innerhalb der angegebenen Zeit oder alle Ereignisse zurückgegeben, bis zu <paramref name="maxCount" /> werden zurückgegeben.</returns>
        <remarks>
          <paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist. Auch Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben. wird zurückgegeben, sobald Ereignisse vorhanden sind.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Dienst einen vorübergehenden Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn der Client eine Verbindung mit dem Dienst Problem verfügt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Ausgelöst, wenn Sie der aktuelle Namespace zu viel Last auf dem System platziert wird.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">Wird ausgelöst, wenn ein anderer Empfänger mit einer höheren <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" /> Wert verbunden ist, als der aktuelle Empfänger an die gleiche Partition gemäß <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben. Wird zurückgegeben, sobald Ereignisse vorhanden sind.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (waitTime As TimeSpan) As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount">Die Höchstmenge an Daten der Benutzer wird in einem Aufruf akzeptieren möchte.</param>
        <param name="waitTime">Die maximale Zeit ist der Benutzer möchte Ereignis eintreffende Daten zu warten.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>
          <paramref name="waitTime" />entspricht keine garantierte Wartezeit API Daten zurückgeben, sobald es verfügbar ist. Auch Dienst wartet nicht <paramref name="maxCount" /> Ereignisse gefüllt werden soll, bevor an den Benutzer zurückgegeben. Wird zurückgegeben, sobald Ereignisse vorhanden sind.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> Ruft einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ungefähre Empfänger Laufzeitinformationen für eine logische Partition einen Event Hub ab.
            Um die Einstellung zu aktivieren, finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" /> und<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingDateTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartingDateTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartingDateTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingDateTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartingDateTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit im UTC-Format für diesen Empfänger ein. Die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> Methode startet den Empfang von das nächste Ereignis hiernach <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" /> Wert. Bei null beginnt der Empfänger empfangen von Ereignissen vom Anfang des ereignisdatenstroms Event Hubs.</summary>
        <value>Das Datum und Uhrzeit in UTC.</value>
        <remarks>Dienst verwendet dieser DateTime-Wert nur als eine Näherung darstellt, bei der Übermittlung des nächsten Ereignisses.
            Bedenken Sie Uhr vorhanden sein können uhrabweichung zwischen Client und dem Zeitpunkt Dienst damit benutzeranwendung entworfen werden sollte, um Duplikate im Ereignisübermittlung zu behandeln.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingOffset">
      <MemberSignature Language="C#" Value="public string StartingOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartingOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartingOffset : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Anfangsoffset dieser Empfänger an. Die <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> Methode startet den Empfang von das nächste Ereignis aus, nachdem dieser Wert ausgeglichen. Wenn der Wert null ist, startet der Empfänger empfangen von Ereignissen vom Anfang des ereignisdatenstroms Event Hubs.</summary>
        <value>Der Startoffset.</value>
        <remarks>Dies Startoffset bindet nur einer einzigen Partition dargestellte <see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>