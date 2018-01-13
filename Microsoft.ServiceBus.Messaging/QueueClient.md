<Type Name="QueueClient" FullName="Microsoft.ServiceBus.Messaging.QueueClient">
  <TypeSignature Language="C#" Value="public abstract class QueueClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit QueueClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class QueueClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type QueueClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt das Clientobjekt Warteschlange dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="queueClient.Abandon lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <remarks>Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden. Service Bus erhöht die Übermittlungsanzahl der Nachricht. Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Abandon (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <remarks>Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden. Service Bus erhöht die Übermittlungsanzahl der Nachricht. Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <returns>Die Meldung wird verworfen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die für das Abbrechen der gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <returns>Die Meldung wird verworfen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion zuverlässigeren, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <summary>Akzeptiert eine nachrichtensitzung, die für die Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner Gruppierung verwandter Nachrichten ermöglicht.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <summary>Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="serverWaitTime" /> ist kein positiver TimeSpan-Wert.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <param name="serverWaitTime">Das Servertimeout für die Wartezeit</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion zuverlässigeren, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="lockToken">Das Sitzungstoken für die Sperre.</param>
        <summary>
            Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="serverWaitTime">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <summary>Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit dem angegebenen Bezeichner, und warten Sie Sitzungstimeout ermöglicht.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn SessionId Null, leer oder Leerzeichen enthalten ist.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="serverWaitTime" /> ist kein positiver TimeSpan-Wert.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <param name="serverWaitTime">Das Servertimeout für die Wartezeit</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="lockToken">Die Sitzung locktoken</param>
        <param name="serverWaitTime">Das Servertimeout für die Wartezeit</param>
        <summary>
            Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <summary>Asynchron akzeptiert eine Sitzung, die Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus, und warten Sie Zeit Gruppierung verwandter Nachrichten zulässt.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <summary>Asynchron akzeptiert eine Sitzung, die für die Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner Gruppierung verwandter Nachrichten ermöglicht.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <summary>Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <param name="serverWaitTime">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <summary>Asynchron akzeptiert eine Sitzung, die Verarbeitung in einer einzelnen Transaktion mit, ob im exklusiven Modus, und warten Sie Zeit Gruppierung verwandter Nachrichten zulässt.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="lockToken">Das Sitzungstoken für die Sperre.</param>
        <summary>
            Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.
            </summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="serverWaitTime">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <summary>Asynchron akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit dem angegebenen Bezeichner, und warten Sie Sitzungstimeout ermöglicht.</summary>
        <returns>Das Ergebnis eines asynchronen Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="isExclusiveMode">Erfassen, wenn der exklusive Modus, oder "false" nicht.</param>
        <param name="serverWaitTime">Das Servertimeout für die Wartezeit</param>
        <summary>
            Akzeptiert eine nachrichtensitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzigen Transaktion, die mit den angegebenen Sitzungsbezeichner mit, ob im exklusiven Modus ermöglicht.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="lockToken">Die Sitzung locktoken</param>
        <param name="serverWaitTime">Das Servertimeout für die Wartezeit</param>
        <summary>
            Akzeptiert eine gesperrte Nachricht nichtexklusiven-Sitzung, die Verarbeitung in einer einzelnen Transaktion unter Verwendung des angegebenen Sitzungs-ID und die Sitzung Sperrtoken Gruppierung verwandter Nachrichten ermöglicht.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="queueClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Bei der Planung einer Nachricht zurückgegeben.</param>
        <summary>
            Bricht eine geplante Nachricht
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="queueClient.Complete lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Complete(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Schließt die Verarbeitung einer Nachricht.</summary>
        <remarks> Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet. Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Schließt asynchron verarbeiten einer Nachricht ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="queueClient.CompleteBatch lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens">Die Lock-Token mit gesperrten Nachrichten im Batch verknüpft ist.</param>
        <summary>Schließt die Verarbeitung eines Nachrichtenbatches an.</summary>
        <remarks> Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet. Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteBatchAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens">Die Lock-Token mit gesperrten Nachrichten im Batch verknüpft ist.</param>
        <summary>Schließt die Verarbeitung eines Nachrichtenbatches asynchron ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mit dem angegebenen Pfad.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen. Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben. Das Format des Abschnitts lautet wie folgt:
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad.</param>
        <param name="mode">Der Modus.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mit dem angegebenen Pfad und Modus.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen. Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben. Das Format des Abschnitts lautet wie folgt:
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Sercvice Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="userPasswordCredential">Die Kennwort-Anmeldeinformationen des Benutzers.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedrectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Instanz.</returns>
        <remarks>Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.</param>
        <param name="mode">Die <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge und Empfangen von Modus.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Instanz.</returns>
        <remarks>Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die verwendete Verbindungszeichenfolge.</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Pfad. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="mode">Die <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Pfad und Modus. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity(System.Uri,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity (endpointAddress, path, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad der Warteschlange an.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="queueClient.DeadLetter lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.DeadLetter (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="queueClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="deadLetterReason">Der Grund für unzustellbare Nachrichten die Nachricht.</param>
        <param name="deadLetterErrorDescription">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</param>
        <summary>Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="deadLetterReason">Der Grund für unzustellbare Nachrichten die Nachricht.</param>
        <param name="deadLetterErrorDescription">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</param>
        <summary>Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="queueClient.Defer lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Wird die Verarbeitung einer Nachricht angehalten.</summary>
        <remarks>Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert. </remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht durch dargestellt die <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Defer (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Wird die Verarbeitung einer Nachricht angehalten.</summary>
        <remarks>Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert. </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Asynchron hält die Verarbeitung einer Nachricht ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht ändern.</param>
        <summary>Asynchron hält die Verarbeitung einer Nachricht ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath">Der Pfad an die Dead Letter-Warteschlange.</param>
        <summary>Erstellt einen Formatnamen aus dem Pfad der angegebenen Dead-Letter-Warteschlange an.</summary>
        <returns>Die <see cref="T:System.String" /> geführt haben, erstellen Sie für den Pfad der angegebenen Dead Letter-Warteschlange den Formatnamen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die nachrichtensitzungen aktivieren, Sitzungen auf Warteschlangen zu suchen.</summary>
        <returns>Die Message-Sitzung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</param>
        <summary>Ruft alle Nachrichten, deren Status der Sitzung, seit aktualisiert wurde, Sitzungen <paramref name="lastUpdatedTime" />.</summary>
        <returns>Die Message-Sitzungen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft asynchron den nachrichtensitzungen aktivieren, Suchen von Sitzungen auf Warteschlangen ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</param>
        <summary>Ruft asynchron alle nachrichtensitzungen, deren Status der Sitzung, seit aktualisiert wurde <paramref name="lastUpdatedTime" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die messagingfactory.</summary>
        <value>Der messaging-Factory.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Meldung ab Empfangsmodus beim Verarbeiten der empfangenen Nachricht.</summary>
        <value>Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> beim Verarbeiten der empfangenen Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="queueClient.OnAbort " />
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
        <summary>Führt beim Aufrufen der Abort-Ereignis.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int prefetchCount, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int32 prefetchCount, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Int32,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * int * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginAcceptMessageSession (sessionId, receiveMode, prefetchCount, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId"></param>
        <param name="receiveMode"></param>
        <param name="prefetchCount"></param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">Die maximale Zeit, bevor der schließen-Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird übergeben, um die EndClose delegieren, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Wird ausgeführt, wenn der schließende-Vorgang aufgerufen wird.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> Empfangsmodus.</param>
        <param name="timeout">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Führt die Begin Empfänger Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueueName">Der Name der untergeordneten Warteschlange.</param>
        <param name="receiveMode">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> Empfangsmodus.</param>
        <param name="timeout">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Führt die Begin Empfänger Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateSender (timeout, callback, state)" />
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
        <param name="timeout">Die maximale Zeit vor diesem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateSender(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Führt die Begin Absender Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime">Das Datum und die Uhrzeit der letzten Aktualisierung.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt die BeginGetMessageSessions-Aktion an.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Abrufen der nachrichtensitzungen verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="queueClient.OnClose timeout" />
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
        <param name="timeout">Die maximale Zeit, bevor der schließen-Vorgang ein Timeout eintritt.</param>
        <summary>Führt beim Aufrufen der Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> zur Darstellung des Status des asynchronen Accept Nachricht Sitzung Vorgangs.</param>
        <summary>Führt beim Aufrufen des EndAcceptMessageSession-Vorgangs.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="queueClient.OnEndClose result" />
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
        <param name="result">Das Ergebnis des asynchronen übergeordneten Methode.</param>
        <summary>Führt die End-Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="queueClient.OnEndCreateReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis des asynchronen <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> Vorgang.</param>
        <summary>Führt das Ende Empfänger Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="queueClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen übergeordneten Methode verweist.</param>
        <summary>Führt das Ende Absender Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.OnEndGetMessageSessions result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis der Sitzung.</param>
        <summary>Führt die End Get-Nachrichtenaktion an.</summary>
        <returns> Die <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.OnMessage callback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="callback">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessage (callback, onMessageOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <param name="onMessageOptions">Gibt an, die <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen zur Instanziierung der Meldungsverteilschleife.</param>
        <summary>Verarbeitet eine Nachricht in ein ereignisgesteuertes Nachrichtensystem, mit dem angegebenen Satz von <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> Optionen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.OnMessageAsync callback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="callback">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Eine Nachricht verarbeitet asynchron.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessageAsync (callback, onMessageOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback">Die Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <param name="onMessageOptions">Ruft eine Option für die Nachricht an.</param>
        <summary>Eine Nachricht verarbeitet asynchron.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den vollständigen Pfadnamen der Warteschlange.</summary>
        <value>Der Warteschlangenpfad relativ zu den <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Basisadresse.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</summary>
        <returns>Einer brokernachricht. Gibt alle Eigenschaften und den Nachrichtentext.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</param>
        <summary>Gibt zurück, ohne die erste Nachricht in der Warteschlange entfernt.</summary>
        <returns>Die vermittelte Nachricht.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Die Sequenznummer, aus denen eine Nachricht einsehen.</param>
        <summary>Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Anzahl der Meldungen.</param>
        <summary>Liest einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch eingesehen werden. Gibt alle Eigenschaften und den Nachrichtentext.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</param>
        <param name="messageCount">Die Anzahl der Meldungen.</param>
        <summary>Liest einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch eingesehen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Nummer der Meldung.</param>
        <summary>Liest asynchron einen Batch von Nachrichten ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Die Sequenznummer ab dem einen Batch von Nachrichten einsehen.</param>
        <param name="messageCount">Die Nummer der Meldung.</param>
        <summary>Liest asynchron einen Batch von Nachrichten ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die die messagingsitzung gleichzeitig anfordern kann.</summary>
        <value>Die Anzahl der Nachrichten, die die messagingsitzung gleichzeitig anfordern kann.</value>
        <remarks> Wird für die nächste empfangsaufruf an den Server wirksam. </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt. Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn die Meldung Vorgang ein Timeout eintritt.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein e/a "oder" Security-Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn die messagingentität, die dem Vorgang zugeordnet nicht vorhanden ist oder wurde gelöscht.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Benutzercode hat einige unerwarteter Vorgänge ausgeführt, oder das Servicebus-Gateway nicht verfügbar ist. Überprüfen Sie die Ausnahmemeldung für den tatsächlichen Fehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Die Sequenznummer der zurückgestellte Nachricht zu empfangen. </param>
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt. Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</remarks>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt. Wenn keine Nachricht empfangen werden soll, verfügbar ist, gibt die Methode NULL zurück und können Sie den Vorgang zu einem späteren Zeitpunkt wiederholen.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die <paramref name="serverWaitTime" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn die Meldung Vorgang ein Timeout eintritt.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein e/a "oder" Security-Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn die messagingentität, die dem Vorgang zugeordnet nicht vorhanden ist oder wurde gelöscht.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn der Benutzercode hat einige unerwarteter Vorgänge ausgeführt, oder das Servicebus-Gateway nicht verfügbar ist. Überprüfen Sie die Ausnahmemeldung für den tatsächlichen Fehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</param>
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Die Zeitspanne der Server wartet, bis eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">Die Sequenznummern, die die Nachrichten im Batch zugeordnet wird.</param>
        <summary>Empfängt einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Anzahl der Nachrichten im Batch zurückzugeben. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</param>
        <summary>Empfängt einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Anzahl der Nachrichten in einem Batch zu empfangen. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</param>
        <param name="serverWaitTime">Die Zeitspanne, die der Server, für den Nachrichtenbatch gewartet wird eingehen, bevor ein Timeout eintritt.</param>
        <summary>Empfängt einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">Die Sequenznummern, die die Nachrichten im Batch zugeordnet wird.</param>
        <summary>Asynchron empfängt einen Nachrichtenbatch aus.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Anzahl der Nachrichten im Batch zurückzugeben. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</param>
        <summary>Asynchron empfängt einen Nachrichtenbatch aus.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount">Die Anzahl der Nachrichten im Batch zurückzugeben. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</param>
        <param name="serverWaitTime">Die Zeitspanne, die der Server, für den Nachrichtenbatch gewartet wird eingehen, bevor ein Timeout eintritt.</param>
        <summary>Asynchron empfängt einen Nachrichtenbatch aus.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="queueClient.RegisterSessionHandler handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType">Der Handlertyp.</param>
        <summary>Registriert den Ereignishandler für die Sitzung mit bestimmten Typ an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandler (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType">Der Handlertyp.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Registriert den Ereignishandler für die Sitzung mit spezifischen Typ und Ereignishandler.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType">Der Handlertyp.</param>
        <summary>Den Handler für die Sitzung registriert asynchron bestimmten Typ.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType">Der Handlertyp.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Den Handler für die Sitzung registriert asynchron bestimmte die Optionen Type und Handler.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Die Handlerfactory registriert werden.</param>
        <param name="options">Die Ereignishandleroptionen.</param>
        <summary>Registriert eine Handlerfactory für Message-Sitzung mit der angegebenen Optionen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Die Handlerfactory registriert werden.</param>
        <param name="options">Die Ereignishandleroptionen.</param>
        <summary>Registriert eine Handlerfactory für Message-Sitzung mit der angegebenen Optionen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Die Handlerfactory registriert werden.</param>
        <param name="options">Die Ereignishandleroptionen.</param>
        <summary>Asynchron registriert eine Handlerfactory für Message-Sitzung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory">Die Handlerfactory registriert werden.</param>
        <param name="options">Die Ereignishandleroptionen.</param>
        <summary>Asynchron registriert eine Handlerfactory für Message-Sitzung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="queueClient.RenewMessageLock lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewMessageLockAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewMessageLockAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="queueClient.RenewMessageLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="queueClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message">Nachricht geplant werden</param>
        <param name="scheduleEnqueueTimeUtc">Zeitpunkt der in die Warteschlange einreihen</param>
        <summary>
            Sendet eine Nachricht geplante
            </summary>
        <returns>Die Sequenznummer, die für den Abbruch erforderlich ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="queueClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">die zu sendende Meldung.</param>
        <summary>Sendet eine Nachricht über die <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> müssen möglicherweise erhöhen den Wert der <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist. </exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die <paramref name="message" /> ist null.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn das Thema/Abonnement unterstützt nicht den Sendevorgang verweist. D. h. für unzustellbare Nachrichten, die Warteschlange nicht unterstützt-Transportsendevorgängen.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein e/a oder Sicherheit Fehler vorliegt.</exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException">Wird ausgelöst, wenn bei der Serialisierung oder Deserialisierung ein Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn die Warteschlange nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein Messagingfehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">die zu sendende Meldung.</param>
        <summary>Sendet asynchron eine Meldung mit der <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">Die Auflistung der brokernachrichten zu senden.</param>
        <summary>Sendet eine Reihe von brokernachrichten (für die Batchverarbeitung).</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">Die Auflistung der brokernachrichten zu senden.</param>
        <summary>Sendet asynchron eine Reihe von brokernachrichten (für die Batchverarbeitung).</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>