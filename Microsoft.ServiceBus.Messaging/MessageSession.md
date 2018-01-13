<Type Name="MessageSession" FullName="Microsoft.ServiceBus.Messaging.MessageSession">
  <TypeSignature Language="C#" Value="public abstract class MessageSession : Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSession extends Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSession" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSession&#xA;Inherits MessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageSession = class&#xA;    inherit MessageReceiver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessageReceiver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetState">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetState() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetState" />
      <MemberSignature Language="VB.NET" Value="Public Function GetState () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetState : unit -&gt; System.IO.Stream" Usage="messageSession.GetState " />
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
        <summary>Ruft den Zustand der meldungssitzung ab.</summary>
        <returns>Der Stream, aus dem Informationen über den Zustand beibehalten wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="member this.GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="messageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft asynchron den Status der meldungssitzung ab.</summary>
        <returns>Der Stream, aus dem Informationen über den Zustand beibehalten wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExclusiveMode">
      <MemberSignature Language="C#" Value="public bool IsExclusiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExclusiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IsExclusiveMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExclusiveMode : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public override long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die letzte eingesehenen Sequenznummer in der Sitzung.</summary>
        <value>Die Anzahl der zuletzt eingesehenen Sequenz, in der Sitzung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Datum und Uhrzeit, an dem die nachrichtensitzung entsperrt wird.</summary>
        <value>Das Datum und die Uhrzeit für die nachrichtensitzung gesperrt werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; LockToken { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public Property LockToken As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.LockToken : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>Das Sperrtoken </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected override void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="propertiesToModify"></param>
        <param name="timeout"> Das Timeout. </param>
        <summary> Verwirft eine Peek gesperrt Nachricht. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messageSession.OnAbort " />
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
        <summary>Bricht die nachrichtensitzung ab. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="propertiesToModify"> Die Eigenschaften für die Abandon-Aktion hinzufügen.</param>
        <param name="fromSync"></param>
        <param name="timeout">    Das Timeout. </param>
        <param name="callback">   Der Rückruf. </param>
        <param name="state">      Der Zustand. </param>
        <summary>
            Führt eine Aktion kann beginnen. 
            </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Startet einen asynchronen Vorgang, um das Kommunikationsobjekt für die Message-Sitzung zu schließen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="deliveryTags"> Eine Auflistung von Übermittlung Tags.</param>
        <param name="fromSync"> Der Beginn der Synchronisierung.</param>
        <param name="timeout"> Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback"> Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state"> Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</summary>
        <returns>Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="lockTokens"> Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</param>
        <param name="fromSync"> Der Beginn der Synchronisierung.</param>
        <param name="timeout"> Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback"> Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state"> Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des Vorgangs OnComplete oder BeginComplete.</summary>
        <returns>Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="propertiesToModify"> Nachrichteneigenschaften ändern. </param>
        <param name="deadLetterReason">  Der Grund für unzustellbare Nachrichten die Nachricht. </param>
        <param name="deadLetterErrorDescription">  Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht. </param>
        <param name="fromSync"> "true", wenn dies von einer Synchronisierungsmethode aufgerufen wurde.</param>
        <param name="timeout">    Das Timeout. </param>
        <param name="callback">   Der Rückruf. </param>
        <param name="state">      Der Zustand. </param>
        <summary> Führt den Anfang verschoben werden soll unzustellbare speicherwarteschlangen-Aktion an. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="propertiesToModify"> Nachrichteneigenschaften ändern. </param>
        <param name="fromSync"></param>
        <param name="timeout">    Das Timeout. </param>
        <param name="callback">   Der Rückruf. </param>
        <param name="state">      Der Zustand. </param>
        <summary> Führt die Begin Aktion verzögern. </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginGetState (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  Die TrackingContext verwenden. </param>
        <param name="timeout">  Das Timeout. </param>
        <param name="callback"> Der Rückruf. </param>
        <param name="state">    Der Zustand. </param>
        <summary> Führt die Begin-Get-Status-Aktion. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginOpen (timeout, callback, state)" />
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
        <param name="timeout">Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. </param>
        <summary>Führt beim Aufrufen des Vorgangs OnOpen des Nachrichtenempfängers.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um ein Kommunikationsobjekt zu öffnen, für die nachrichtensitzung verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="fromSequenceNumber"> Die Sequenznummer der Sitzung einsehen.</param>
        <param name="messageCount"> Die Anzahl der Nachricht in den Vorgang.</param>
        <param name="timeout"> Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback"> Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state"> Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Beim Aufrufen des Vorgangs OnPeek oder BeginPeek führt.</summary>
        <returns>Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Einsehen einer Kommunikation der meldungssitzung verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewLock">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewLock (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="timeout"> Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback"> Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state"> Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des Vorgangs RenewLock oder BeginRenewLock.</summary>
        <returns>Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status des Vorgangs verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="lockTokens"> Die Auflistung der Lock-Token an den gesperrten Nachrichteninstanzen gebunden.</param>
        <param name="fromSync"> Der Beginn der Synchronisierung.</param>
        <param name="timeout"> Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</param>
        <param name="callback"> Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state"> Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des Vorgangs OnBegin für Sperren von Nachrichten.</summary>
        <returns>Ein<see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Erneuern Sie die Verarbeitung von Nachrichten Sperre verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream sessionState, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream sessionState, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginSetState (trackingContext, sessionState, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sessionState" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  Die TrackingContext verwenden. </param>
        <param name="sessionState">   Der Zustand. </param>
        <param name="timeout">  Das Timeout. </param>
        <param name="callback"> Der Rückruf. </param>
        <param name="state">    Der Zustand. </param>
        <summary> Führt die Begin die Aktion. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, receipts, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="receipts"> Die eingehenden Bestätigungen. </param>
        <param name="timeout">  Das Timeout. </param>
        <param name="callback"> Der Rückruf. </param>
        <param name="state">    Der Zustand. </param>
        <summary> Führt die Begin Try Empfangsaktion. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="messageCount"> Anzahl der Nachrichten. </param>
        <param name="serverWaitTime"> Das Timeout. </param>
        <param name="callback">     Der Rückruf. </param>
        <param name="state">        Der Zustand. </param>
        <summary> Führt die Begin Try Empfangsaktion. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="messageCount"> Anzahl der Nachrichten. </param>
        <param name="serverWaitTime"> Das Timeout. </param>
        <param name="callback">     Der Rückruf. </param>
        <param name="state">        Der Zustand. </param>
        <summary> Führt die Begin Try Empfangsaktion. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected override void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="timeout"> Das Timeout. </param>
        <summary> Schließt eine Peek gesperrten Nachricht ab. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageSession.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">To be added.</param>
        <param name="lockTokens">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary> Verschiebt eine Nachricht an die Dead Letter-Warteschlange an. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected override void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="lockTokens"> Die Lock-Token. </param>
        <param name="propertiesToModify"> Nachrichteneigenschaften ändern. </param>
        <param name="timeout">    Das Timeout. </param>
        <summary> Eine Nachricht wird verzögert. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected override void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageSession.OnEndAbandon result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abbrechen von Nachrichten und seine Sperre abgeben verweist.</param>
        <summary>Beendet einen asynchronen Vorgang zum Verwerfen der Nachrichteninhalts und dessen Sperre abgeben.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messageSession.OnEndClose result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Schließen Sie des Kommunikationsobjekts für die nachrichtensitzung verweist.</param>
        <summary>Beendet einen asynchronen Vorgang, um das Kommunikationsobjekt für die Message-Sitzung zu schließen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected override void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndComplete : IAsyncResult -&gt; unit" Usage="messageSession.OnEndComplete result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Empfangen von Nachrichten abschließen verweist.</param>
        <summary>Führt die vollständige End-Vorgang des Nachrichtenempfängers an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDeadLetter result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang nicht zugestellte Nachrichten an die Warteschlange für unzustellbare Nachrichten verschieben verweist.</param>
        <summary>Führt den Vorgang des End-Warteschlange für unzustellbare Nachrichten des Nachrichtenempfängers.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected override void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDefer : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDefer result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Anhalten der Verarbeitung von Nachrichten verweist.</param>
        <summary>Führt das Ende des Nachrichtenempfängers Vorgang aufschieben.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetState">
      <MemberSignature Language="C#" Value="protected abstract System.IO.Stream OnEndGetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnEndGetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndGetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetState (result As IAsyncResult) As Stream" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetState : IAsyncResult -&gt; System.IO.Stream" Usage="messageSession.OnEndGetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status der meldungssitzung verweist.</param>
        <summary>Führt beim Aufrufen des Vorgangs OnGetState oder EndGetState.</summary>
        <returns>Der Stream, aus dem Informationen über den Zustand beibehalten wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="messageSession.OnEndOpen result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um ein Kommunikationsobjekt zu öffnen, für die nachrichtensitzung verweist.</param>
        <summary>Beendet den asynchronen Vorgang, um ein Kommunikationsobjekt für die Message-Sitzung zu öffnen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="override this.OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageSession.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Einsehen einer Kommunikation der meldungssitzung verweist.</param>
        <summary>Führt beim Aufrufen des EndPeek-Vorgangs.</summary>
        <returns>Die Liste der Nachricht aus der Sitzung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewLock">
      <MemberSignature Language="C#" Value="protected abstract DateTime OnEndRenewLock (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnEndRenewLock(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewLock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewLock (result As IAsyncResult) As DateTime" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewLock : IAsyncResult -&gt; DateTime" Usage="messageSession.OnEndRenewLock result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen des Status der meldungssitzung verweist.</param>
        <summary>Führt den Vorgang EndRenewLock des Nachrichtenempfängers an.</summary>
        <returns>Das Datum und Uhrzeit, zu das Erneuerung der Sperre endet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="override this.OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageSession.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis des Vorgangs.</param>
        <summary>Führt eine Aktion EndRenew für nachrichtensperren.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> von gesperrten Nachrichten...</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSetState">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndSetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSetState (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSetState : IAsyncResult -&gt; unit" Usage="messageSession.OnEndSetState result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Festlegen des Status der meldungssitzung verweist.</param>
        <summary>Beendet den asynchronen Vorgang zum Festlegen des Status der meldungssitzung an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um zu versuchen, Nachrichten zu empfangen verweist.</param>
        <param name="messages">Wenn diese Methode zurückgibt, enthält die empfangene Nachricht-Auflistung.</param>
        <summary>Führt das Ende wiederholen Sie den Vorgang, der den Empfänger einer Nachricht zu empfangen.</summary>
        <returns>"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang, um zu versuchen, Nachrichten zu empfangen verweist.</param>
        <param name="messages">Wenn diese Methode zurückgibt, enthält die empfangene Nachricht-Auflistung.</param>
        <summary>Führt das Ende wiederholen Sie den Vorgang, der den Empfänger einer Nachricht zu empfangen.</summary>
        <returns>"true", wenn er erfolgreich abgeschlossen wurde; "false", wenn ein Fehler auftritt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetState">
      <MemberSignature Language="C#" Value="protected virtual System.IO.Stream OnGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream&#xA;override this.OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream" Usage="messageSession.OnGetState (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  Die TrackingContext verwenden. </param>
        <param name="timeout"> Das Timeout. </param>
        <summary> Führt die Aktion zum Abrufen des Status an. </summary>
        <returns> zu erstellen und zu verwalten. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLock">
      <MemberSignature Language="C#" Value="protected virtual DateTime OnRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime&#xA;override this.OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime" Usage="messageSession.OnRenewLock (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> Die Kontextinformationen zusammenhängen, indem Sie eine Transaktion, die diesen Vorgang nachverfolgen.</param>
        <param name="timeout"> Die Zeitspanne Intervall der Vorgang wartet, bevor ein Timeout eintritt.</param>
        <summary>Führt eine Aktion RenewLock für nachrichtensperren.</summary>
        <returns>Die Zeitspanne des Vorgangs warten soll, bevor ein Timeout eintritt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetState">
      <MemberSignature Language="C#" Value="protected virtual void OnSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream stream, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream stream, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit&#xA;override this.OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit" Usage="messageSession.OnSetState (trackingContext, stream, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  Die TrackingContext verwenden. </param>
        <param name="stream">  Der Stream (Datenstrom). </param>
        <param name="timeout"> Das Timeout. </param>
        <summary> Führt die Aktion an. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, receipts, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="receipts"> Die eingehenden Bestätigungen. </param>
        <param name="timeout">  Das Timeout. </param>
        <param name="messages"> die Ausgabenachricht (ausgehend)</param>
        <summary> Wiederholen Sie dann führt Empfangsaktion. </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">TrackingContext verwenden.</param>
        <param name="messageCount"> Die Anzahl der Meldungen. </param>
        <param name="serverWaitTime">  Der Server-Wartezeit aus, bevor ein Timeout eintritt. </param>
        <param name="messages">  zurückgegebenen Nachrichten. </param>
        <summary> Wiederholen Sie dann führt Empfangsaktion. </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public override string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Pfad der Warteschlange bzw. Thema relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</summary>
        <value>Eine Zeichenfolge, die den Pfad der Warteschlange bzw. Thema darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public override int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessException">
      <MemberSignature Language="C#" Value="protected Exception ProcessException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Exception ProcessException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.ProcessException(System.Exception)" />
      <MemberSignature Language="F#" Value="member this.ProcessException : Exception -&gt; Exception" Usage="messageSession.ProcessException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="messageSession.RenewLock " />
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
        <summary>Gibt den Zeitraum fest, innerhalb dessen der Host seine Sperre für eine Nachricht erneuert.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> ist "true", können Sie den Vorgang sofort wiederholen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Sie können sofort den Vorgang wiederholen.</exception>
        <exception cref="T:System.TimeoutException">Sie können sofort den Vorgang wiederholen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wird ausgelöst, anstelle von <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> ist die Nachricht aus einer <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageSession.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt den Zeitraum fest, innerhalb dessen der Host seine Sperre für eine Nachricht erneuert.</summary>
        <returns>Der Host, der gesperrt wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public virtual string SessionId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder festlegen den Nachricht Sitzungsbezeichner.</summary>
        <value>Die Sitzungs-ID der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetState">
      <MemberSignature Language="C#" Value="public void SetState (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetState(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetState(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetState (sessionState As Stream)" />
      <MemberSignature Language="F#" Value="member this.SetState : System.IO.Stream -&gt; unit" Usage="messageSession.SetState sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState">Der Stream, in dem Informationen über den Zustand beibehalten wird.</param>
        <summary>Legt den Zustand der meldungssitzung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetStateAsync(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetStateAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.SetStateAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="messageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState">Der Stream, in dem Informationen über den Zustand beibehalten wird.</param>
        <summary>Legt asynchron den Status der meldungssitzung fest.</summary>
        <returns>Der Status der meldungssitzung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal override bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>