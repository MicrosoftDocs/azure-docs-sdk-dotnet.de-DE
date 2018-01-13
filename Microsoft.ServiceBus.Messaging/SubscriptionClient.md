<Type Name="SubscriptionClient" FullName="Microsoft.ServiceBus.Messaging.SubscriptionClient">
  <TypeSignature Language="C#" Value="public abstract class SubscriptionClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SubscriptionClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SubscriptionClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Anchor-Klasse, die in der Laufzeit-Vorgänge, die im Zusammenhang mit themaabonnements verwendet.</summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            Erstellen von Abonnements Client SubscriptionClient MySubscriptionClient = Factory. CreateSubscriptionClient(mySubscription);
            
            Empfangen von Nachrichten für (Int Count = 0; Anzahl &lt; MsgCount; Anzahl ++) {Var Message = mySubscriptionClient.Receive(); message.Complete(); }
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="subscriptionClient.Abandon lockToken" />
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
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Abandon (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Eine Auflistung von Property-Objekte geändert werden.</param>
        <summary>Verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <remarks>Wenn der Client nicht, um die Nachricht aus der Warteschlange/Thema, sollte diese Methode aufgerufen werden. Service Bus erhöht die Übermittlungsanzahl der Nachricht. Der Client kann nun entweder versucht die Meldung ein, oder verschieben Sie sie an die Dead Letter-Warteschlange.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync lockToken" />
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
        <returns>Eine Taskinstanz, die den asynchronen Abbruchvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Eine Auflistung von Property-Objekte geändert werden.</param>
        <summary>Asynchron verwirft die Nachricht und die Nachricht sperrbesitz aufgibt.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Abbruchvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession " />
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
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession isExclusiveMode" />
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
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession sessionId" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession serverWaitTime" />
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
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn ServerWaitTime nicht um ein positive TimeSpan-Wert ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
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
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken)" />
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
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, serverWaitTime)" />
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
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn ServerWaitTime nicht um ein positive TimeSpan-Wert ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <paramref name="serverWaitTime" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn der Client bereits geschlossen, abgebrochen oder verworfen wird.</exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync " />
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
        <summary>Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync isExclusiveMode" />
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
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync sessionId" />
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
        <summary>Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync serverWaitTime" />
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
        <returns>Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
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
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
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
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
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
        <summary>Asynchron akzeptiert eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion verwenden die Wartezeit für den angegebenen Server ermöglicht.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Accept Nachricht Sitzung Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRule (description As RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.AddRule : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; unit" Usage="subscriptionClient.AddRule description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</param>
        <summary>Fügt eine neue Regel, die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> mithilfe der angegebenen Beschreibung.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="description" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="description.Name.Name" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="description.Name.Name" /> Länge überschreitet das Limit von 50 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn versucht wird, eine andere Regel mit demselben Namen wie eine hinzufügen, die bereits hinzugefügt wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRule : string * Microsoft.ServiceBus.Messaging.Filter -&gt; unit" Usage="subscriptionClient.AddRule (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name der Regel hinzufügen.</param>
        <param name="filter">Der Filterausdruck für den Nachrichten berücksichtigt werden.</param>
        <summary>Fügt eine Regel auf das aktuelle Abonnement mit dem angegebenen Namen und die Filter-Ausdruck.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="filter" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="ruleName" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn <paramref name="ruleName" /> Länge überschreitet das Limit von 50 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn versucht wird, eine andere Regel mit demselben Namen wie eine hinzufügen, die bereits hinzugefügt wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</param>
        <summary>Fügt asynchron eine neue Regel, die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> mithilfe der angegebenen Beschreibung.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name der Regel hinzufügen.</param>
        <param name="filter">Der Filterausdruck für den Nachrichten berücksichtigt werden.</param>
        <summary>Fügt asynchron eine Regel auf das aktuelle Abonnement mit dem angegebenen Namen und den Filterausdruck an.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="subscriptionClient.Complete lockToken" />
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
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
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
        <returns>Eine Taskinstanz, die den asynchronen schließen-Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="subscriptionClient.CompleteBatch lockTokens" />
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
        <param name="lockTokens">Die Lock-Token, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Schließt die Verarbeitung eines Nachrichtenbatches an.</summary>
        <remarks> Diese Methode wird als ein Handshake zwischen dem Client und dem Service Bus für eine Zustellung der Nachricht verwendet. Wenn der Client, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteBatchAsync lockTokens" />
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
        <param name="lockTokens">Die Lock-Token, die an den gesperrten Nachrichteninstanz gebunden werden.</param>
        <summary>Asynchron schließt die Verarbeitung eines Batches.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Abschluss Batchvorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mit dem angegebenen Namen und Thema Pfad.</summary>
        <returns>Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="mode">Die Nachricht Empfangsmodus.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mit dem angegebenen Namen, themenpfad und Modus.</summary>
        <returns>Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Sercvice Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="userPasswordCredential">Die Kennwort-Anmeldeinformationen des Benutzers.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
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
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedrectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> von einer Verbindungszeichenfolge mit dem angegebenen Thema Pfad und Name.</summary>
        <returns>Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="mode">Die Nachricht Empfangsmodus.</param>
        <summary>Erstellt eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> von einer Verbindungszeichenfolge mit dem angegebenen themenpfad, Namen und Modus.</summary>
        <returns>Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity (Uri endpointAddress, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity (endpointAddress, topicPath, name, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="mode">Der Receive-Modus.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="subscriptionClient.DeadLetter lockToken" />
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
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Die Eigenschaften zu ändern.</param>
        <summary>Verschiebt die nicht zugestellte Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
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
        <returns>Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Die Eigenschaften zu ändern.</param>
        <summary>Verschiebt Sie die nicht zugestellte Nachricht asynchron an die Dead Letter-Warteschlange.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <returns>Eine Taskinstanz, die den asynchronen Deadletter Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="subscriptionClient.Defer lockToken" />
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
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert festlegen, indem überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Nachricht szenariobeschreibungen <paramref name="lockToken" /> hat die nachrichtensperre verloren.</exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Defer (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Die Eigenschaften zu ändern.</param>
        <summary>Wird die Verarbeitung einer Nachricht angehalten.</summary>
        <remarks>Vor dem verschieben, sollten Sie den Empfang der Nachricht für den späteren Abruf reserviert. </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync lockToken" />
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
        <returns>Eine Taskinstanz, die den asynchronen darstellt zurückstellen Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync (lockToken, propertiesToModify)" />
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
        <param name="propertiesToModify">Die Eigenschaften zu ändern.</param>
        <summary>Asynchron hält die Verarbeitung einer Nachricht ein.</summary>
        <returns>Eine Taskinstanz, die den asynchronen darstellt zurückstellen Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <summary>Erstellt einen Format Name für unzustellbare Nachrichten Pfad unter Verwendung des angegebenen Thema Pfad und Abonnements.</summary>
        <returns>Die <see cref="T:System.String" /> geführt hat, aus dem Pfad den Format für unzustellbare Nachrichten unter Verwendung des angegebenen Thema Pfad und Abonnements erstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatSubscriptionPath">
      <MemberSignature Language="C#" Value="public static string FormatSubscriptionPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatSubscriptionPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatSubscriptionPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatSubscriptionPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der vollständige Pfadname des Themas.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <summary>Erstellt einen Format Name Abonnement Pfad unter Verwendung des angegebenen Thema Pfad und Abonnements.</summary>
        <returns>Die <see cref="T:System.String" /> geführt hat, aus dem Pfad den Format-Abonnement unter Verwendung des angegebenen Thema Pfad und Abonnements erstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions " />
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
        <summary>Ruft die eine Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</summary>
        <returns>Eine Nachricht, die Gruppierung von ermöglicht sitzungsbezogene Nachrichten zur Verarbeitung in einer einzelnen Transaktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions lastUpdatedTime" />
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
        <returns>Eine Nachricht, die Gruppierung von ermöglicht sitzungsbezogene Nachrichten zur Verarbeitung in einer einzelnen Transaktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync " />
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
        <summary>Ruft die einer Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht asynchron ab.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Ladevorgang Nachricht Sitzungen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync lastUpdatedTime" />
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
        <summary>Ruft die einer Sitzung, die Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht asynchron ab.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Ladevorgang Nachricht Sitzungen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die messaging Factory, die für die Erstellung dieses Abonnement ab.</summary>
        <value>Der messaging-Factory für die Erstellung dieses Abonnement.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
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
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Namen des Abonnements ab.</summary>
        <value>Der Name des Abonnements.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="subscriptionClient.OnAbort " />
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
        <summary>Führt die Aktion abbrechen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAcceptMessageSession (sessionId, receiveMode, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
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
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die Sitzungs-ID der Sitzung angezeigt.</param>
        <param name="receiveMode">Den Empfangsmodus bei der Verarbeitung mit der Nachrichten empfängt.</param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime">Der Zeitraum für die Verarbeitung von Nachrichten vor dem Timeout der Server-Wartevorgänge</param>
        <param name="timeout">Der Zeitraum der Server wartet für die Verarbeitung von Nachrichten, bevor ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des BeginAcceptMessageSession-Vorgangs.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Annehmen einer Sitzungs verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAddRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAddRule (Microsoft.ServiceBus.Messaging.RuleDescription description, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginAddRule (description As RuleDescription, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAddRule : Microsoft.ServiceBus.Messaging.RuleDescription * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAddRule (description, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="description">Eine Beschreibung der Regel, die der Regel hinzuzufügenden Metadaten bereitstellt.</param>
        <param name="timeout">Die Zeitspanne, die diesen Vorgang wartet, bevor ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des BeginAddRule-Vorgangs.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird übergeben, um die BeginClose delegieren, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Führt die Aktion "Schließen" beginnen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" />, das auf den asynchronen BeginClose verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
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
        <param name="receiveMode">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Führt die Begin Empfänger Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueuePath, string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueuePath, string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (subQueuePath, subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueuePath" Type="System.String" />
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueuePath">Der Pfad der Unterwarteschlange.</param>
        <param name="subQueueName">Der Name der Unterwarteschlange.</param>
        <param name="receiveMode">Die Nachricht <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Führt die Begin Empfänger Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Async-Methode verweist. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
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
        <param name="lastUpdatedTime">Der Zeitpunkt, zu der Sitzung wurde zuletzt aktualisiert.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</param>
        <summary>Führt beim Aufrufen des BeginGetMessageSessions-Vorgangs.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetRules">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetRules (int top, int skip, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetRules(int32 top, int32 skip, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetRules(System.Int32,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetRules (top As Integer, skip As Integer, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetRules : int * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetRules (top, skip, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="top">To be added.</param>
        <param name="skip">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRule (string ruleName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRule(string ruleName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRule (ruleName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRule : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRule (ruleName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name des zu entfernenden Regel an.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />-Delegaten übergeben.</param>
        <summary>Beginnt, Entfernen einer <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> aus einer <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> durch die Laufzeit-Clientprotokoll.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> verweist, die auf den asynchronen <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRulesByTag">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRulesByTag (string tag, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRulesByTag(string tag, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRulesByTag(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRulesByTag (tag As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRulesByTag : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRulesByTag (tag, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="tag">Das Tag, die verwendet werden.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />-Delegaten übergeben.</param>
        <summary>Entfernen beginnt eine <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> aus einer <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> über die Laufzeit-Clientprotokoll mit einem Tag.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang zum Hinzufügen einer neuen Regel für das Abonnement verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="subscriptionClient.OnClose timeout" />
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
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <summary>Führt die Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.OnEndAcceptMessageSession result" />
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
    <Member MemberName="OnEndAddRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAddRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAddRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAddRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAddRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAddRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndAddRule result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> aus einem <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</param>
        <summary>Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndClose result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen BeginClose verweist.</param>
        <summary>Führt die End-Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="subscriptionClient.OnEndCreateReceiver result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> -Objekt, das verweist auf die <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />.</param>
        <summary>Führt das Ende Empfänger Aktion zu erstellen.</summary>
        <returns>Ein neu erstelltes <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.OnEndGetMessageSessions result" />
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
        <param name="result">Das Ergebnis der Nachricht.</param>
        <summary>Führt die End Get-Nachrichtenaktion an.</summary>
        <returns>Ende Nachrichtenaktion abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetRules">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetRules (result As IAsyncResult) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetRules : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="subscriptionClient.OnEndGetRules result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRule result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> aus einem <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</param>
        <summary>Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRules">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRules (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRules : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRules result" />
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
        <param name="result">Das Ergebnis der Asynchronization.</param>
        <summary>Den asynchronen Aufruf beendet <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="subscriptionClient.OnMessage callback" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessage (callback, onMessageOptions)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.OnMessageAsync callback" />
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
        <param name="callback">Die asynchrone Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Eine Nachricht verarbeitet asynchron.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessageAsync (callback, onMessageOptions)" />
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
        <param name="callback">Die asynchrone Methode, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</param>
        <param name="onMessageOptions">Die Optionen, die der Nachricht zugeordnet wird.</param>
        <summary>Eine Nachricht verarbeitet asynchron.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek " />
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
        <returns>Die zurückgegebene Meldung.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek fromSequenceNumber" />
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
        <returns>Die zurückgegebene Meldung.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync " />
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
        <returns>Eine Taskinstanz, die den asynchronen Lesevorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync fromSequenceNumber" />
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
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</param>
        <summary>Gibt asynchron zurück, ohne die erste Nachricht in der Warteschlange entfernt.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Lesevorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch messageCount" />
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
        <param name="messageCount">Die Anzahl der Nachrichten in einem Batch.</param>
        <summary>Gibt zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</summary>
        <returns>Die Auflistung der ersten Nachrichten in einem Batch.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</param>
        <param name="messageCount">Die Anzahl der Nachrichten in einem Batch.</param>
        <summary>Gibt zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</summary>
        <returns>Die Auflistung der ersten Nachrichten in einem Batch.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync messageCount" />
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
        <param name="messageCount">Die Anzahl der Nachrichten in einem Batch.</param>
        <summary>Gibt asynchron zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Lesevorgang für den Batch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der eine Nachricht durchsucht wird.</param>
        <param name="messageCount">Die Anzahl der Nachrichten in einem Batch.</param>
        <summary>Gibt asynchron zurück, ohne dass die ersten Nachrichten in einem Batch entfernt.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Lesevorgang für den Batch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
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
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks> Wird für die nächste empfangsaufruf an den Server wirksam. </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive " />
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
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn das Abonnement nicht vorhanden ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein Authentifizierungsfehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive sequenceNumber" />
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
        <param name="sequenceNumber">Die Sequenznummer der zurückgestellte Nachricht zu empfangen.</param>
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</remarks>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive serverWaitTime" />
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
        <summary>Empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , die die empfangene Nachricht darstellt.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die <paramref name="serverWaitTime" /> ist ein negativer Wert.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn das Abonnement nicht vorhanden ist.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang über festlegen Timeoutwert überschritten <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein Authentifizierungsfehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync " />
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
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync sequenceNumber" />
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
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync serverWaitTime" />
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
        <summary>Asynchron empfängt eine Nachricht mit der <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</summary>
        <returns>Eine Taskinstanz, die den asynchronen darstellt Empfangsvorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch sequenceNumbers" />
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
        <param name="sequenceNumbers">Die Sequenznummer.</param>
        <summary>Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</summary>
        <returns>Ein Batch nach Abschluss des asynchronen Vorgangs.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge erfolgreich ausgeführt wurde, aber die Nachricht mit der angeforderten SequenceNumber können nicht gefunden werden.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch messageCount" />
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
        <summary>Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</summary>
        <returns>Ein Batch nach Abschluss des asynchronen Vorgangs.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch (messageCount, serverWaitTime)" />
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
        <param name="messageCount">Die Anzahl der Nachrichten im Batch zurückzugeben. Wie eine Schätzung, weniger oder mehr Nachrichten als sieht <paramref name="messageCount" /> zurückgegeben werden.</param>
        <param name="serverWaitTime">Die Zeitspanne der Server wartet für die Verarbeitung von Nachrichten.</param>
        <summary>Ein Batch wird nach Abschluss des asynchronen Vorgangs empfangen.</summary>
        <returns>Ein Batch nach Abschluss des asynchronen Vorgangs.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync sequenceNumbers" />
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
        <param name="sequenceNumbers">Die Sequenznummer.</param>
        <summary>Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</summary>
        <returns>Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync messageCount" />
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
        <summary>Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</summary>
        <returns>Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
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
        <param name="serverWaitTime">Die Zeitspanne der Server wartet für die Verarbeitung von Nachrichten.</param>
        <summary>Asynchron empfängt einen Satz von Nachrichten (für die Batchverarbeitung).</summary>
        <returns>Eine Taskinstanz, die den asynchronen Empfangsvorgang für den Batch darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler handlerType" />
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
        <param name="handlerType">Der Typ des Handlers.</param>
        <summary>Registriert den Ereignishandler für die Clientsitzung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handlerType, options)" />
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
        <param name="handlerType">Der Typ des Handlers.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Registriert den Ereignishandler für die Clientsitzung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync handlerType" />
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
        <param name="handlerType">Der Typ des Handlers.</param>
        <summary>Asynchron registriert den Ereignishandler für die Clientsitzung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync (handlerType, options)" />
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
        <param name="handlerType">Der Typ des Handlers.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Asynchron registriert den Ereignishandler für die Clientsitzung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Registriert die Handlerfactory für die Clientsitzung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Registriert die Handlerfactory für die Clientsitzung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Für die Clientsitzung registriert die Handlerfactory asynchron.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory">Die Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</param>
        <param name="options">Der Handler Sitzungsoptionen.</param>
        <summary>Für die Clientsitzung registriert die Handlerfactory asynchron.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRule">
      <MemberSignature Language="C#" Value="public void RemoveRule (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveRule(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveRule (ruleName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveRule : string -&gt; unit" Usage="subscriptionClient.RemoveRule ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name der Regel.</param>
        <summary>Entfernt die Regel beschriebenen <paramref name="ruleName" />.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="ruleName" /> ist null, weiß Speicherplatz leer oder liegt nicht im richtigen Format vorliegt.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang den Timeoutwert, die mittels der OperationTimeout-Eigenschaft festgelegt wurde überschritten.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name der Regel.</param>
        <summary>Entfernt asynchron die Regel beschriebenen <paramref name="ruleName" />.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Entfernungsvorgang für die Regel darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="subscriptionClient.RenewMessageLock lockToken" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="subscriptionClient.RenewMessageLockAsync lockToken" />
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
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, der vollständige Pfadname des Themas.</summary>
        <value>Der vollständige Pfadname des Themas.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>