<Type Name="ISubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription">
  <TypeSignature Language="C#" Value="public interface ISubscription : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscription implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscription&#xA;Implements IGroupableResource(Of IServiceBusManager, SubscriptionInner), IHasInner(Of SubscriptionInner), IHasManager(Of IServiceBusManager), IIndependentChild(Of IServiceBusManager), IIndependentChildResource(Of IServiceBusManager, SubscriptionInner), IRefreshable(Of ISubscription), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ISubscription = interface&#xA;    interface IIndependentChildResource&lt;IServiceBusManager, SubscriptionInner&gt;&#xA;    interface IGroupableResource&lt;IServiceBusManager, SubscriptionInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;SubscriptionInner&gt;&#xA;    interface IIndependentChild&lt;IServiceBusManager&gt;&#xA;    interface IRefreshable&lt;ISubscription&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Der Typ, Servicebus-Thema Subscription darstellt.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zuletzt es eine empfangsanforderung, um dieses Abonnement wurde ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl aktiver Nachrichten im Abonnement.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten in der unzustellbare-Abonnement.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTtlDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTtlDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTtlDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DefaultMessageTtlDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMessageTtlDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTtlDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DefaultMessageTtlDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Dauer, die nach der die Nachricht abläuft, beginnend ab dem Zeitpunkt der Nachricht zum Abonnement gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public long DeleteOnIdleDurationInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteOnIdleDurationInMinutes As Long" />
      <MemberSignature Language="F#" Value="member this.DeleteOnIdleDurationInMinutes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeleteOnIdleDurationInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Leerlaufdauer nach der das Abonnement automatisch gelöscht wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBatchedOperationsEnabled">
      <MemberSignature Language="C#" Value="public bool IsBatchedOperationsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBatchedOperationsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsBatchedOperationsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBatchedOperationsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBatchedOperationsEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsBatchedOperationsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt an, ob serverseitige Batchvorgänge aktiviert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeadLetteringEnabledForExpiredMessages">
      <MemberSignature Language="C#" Value="public bool IsDeadLetteringEnabledForExpiredMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDeadLetteringEnabledForExpiredMessages As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDeadLetteringEnabledForExpiredMessages : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt an, ob dieses Abonnement unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeadLetteringEnabledForFilterEvaluationFailedMessages">
      <MemberSignature Language="C#" Value="public bool IsDeadLetteringEnabledForFilterEvaluationFailedMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDeadLetteringEnabledForFilterEvaluationFailedMessages As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDeadLetteringEnabledForFilterEvaluationFailedMessages : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt an, ob Abonnement dead Letter auf Ausnahmen unterstützt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSessionEnabled">
      <MemberSignature Language="C#" Value="public bool IsSessionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSessionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsSessionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSessionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSessionEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsSessionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft angibt, ob das Abonnement Sitzungen unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDurationInSeconds">
      <MemberSignature Language="C#" Value="public long LockDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LockDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.LockDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LockDurationInSeconds : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.LockDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Dauer eines Peek / Lock also den Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCountBeforeDeadLetteringMessage">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCountBeforeDeadLetteringMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDeliveryCountBeforeDeadLetteringMessage As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCountBeforeDeadLetteringMessage : int" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Anzahl von einem Nachrichtenübermittlung bevor es als Warteschlange für unzustellbare Nachrichten Zustellungsversuche kennzeichnen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten im Abonnement.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten an das Abonnement, die noch für Verbrauch veröffentlicht werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den aktuellen Status des Abonnements ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten, die in der unzustellbare Nachrichten übertragen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
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