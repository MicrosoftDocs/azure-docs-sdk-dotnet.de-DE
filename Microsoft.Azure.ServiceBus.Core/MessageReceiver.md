<Type Name="MessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.MessageReceiver">
  <TypeSignature Language="C#" Value="public class MessageReceiver : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageReceiver extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageReceiver&#xA;Inherits ClientEntity&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             Die MessageReceiver kann zum Empfangen von Nachrichten aus Warteschlangen und Abonnements, und bestätigen sie verwendet werden.
             </summary>
    <remarks>
             Die MessageReceiver bietet erweiterte Funktionalität, die nicht in der <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> oder <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />. Z. B. <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, dem können Sie zum Empfangen von Nachrichten bei Bedarf, erfordert jedoch auch manuell mithilfe von Sperren erneuern <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.
             AMQP-Protokolls verwendet für die Kommunikation mit dem Dienst.
             </remarks>
    <example>
             Erstellen Sie eine neue MessageReceiver zum Empfangen einer Nachricht aus einem Abonnement
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             Eine Meldung aus dem Abonnement.
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">Die <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> Verbindungs-Entitätsdetails müssen.</param>
        <param name="receiveMode">Die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden. Der Standardwert ist PeekLock-Modus.</param>
        <param name="retryPolicy">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden. Wird standardmäßig auf <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /> festgelegt.</param>
        <param name="prefetchCount">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> , die die Obergrenze von Nachrichten, die dieser Empfänger wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt. Der Standardwert ist 0.</param>
        <summary>
            Erstellt eine neue MessageReceiver aus einem <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit der Entität, die während des ersten Vorgangs geöffnet ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace-Verbindungszeichenfolge für die Kommunikation mit Service Bus verwendet. Darf keine Entitätsdetails enthalten.</param>
        <param name="entityPath">Der Pfad der Entität für dieser Empfänger. Für Warteschlangen dies den Namen, aber für Abonnements wird dies den Pfad sein.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />, um diesen Pfad zu erstellen.</param>
        <param name="receiveMode">Die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden. Der Standardwert ist PeekLock-Modus.</param>
        <param name="retryPolicy">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> , die die Obergrenze von Nachrichten, die dieser Empfänger wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt. Der Standardwert ist 0.</param>
        <summary>
            Erstellt eine neue MessageReceiver aus einer angegebenen Zeichenfolge und Entität Verbindungspfad an.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit der Entität, die während des ersten Vorgangs geöffnet ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;AbandonAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht zu verwerfen.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, während die Nachricht aufzugeben.</param>
        <summary>
            Verwirft eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einem Sperrtoken. Dadurch wird die Nachricht erneut für die Verarbeitung zur Verfügung.
            </summary>
        <returns>To be added.</returns>
        <remarks>Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;CompleteAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> mit den Token sperren die entsprechenden Nachrichten abgeschlossen.</param>
        <summary>
            Schließt eine Reihe von <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einer Liste von Token der Sperre. Hierdurch wird die Nachricht vom Dienst gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht abgeschlossen.</param>
        <summary>
            Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken. Hierdurch wird die Nachricht vom Dienst gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, wenn zum untergeordneten Warteschlange verschoben werden.</param>
        <summary>
            Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</param>
        <param name="deadLetterReason">Der Grund für unzustellbare Nachrichten die Nachricht.</param>
        <param name="deadLetterErrorDescription">Die fehlerbeschreibung für unzustellbare Nachrichten die Nachricht.</param>
        <summary>
            Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeferAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken des der <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, während die Nachricht verzögern.</param>
        <summary>Gibt an, dass der Empfänger die Verarbeitung für die Nachricht verzögern möchte.</summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um diese Meldung erneut in der Zukunft Sie benötigen zum Speichern der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> und empfangen mit <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.
            Verzögern von Nachrichten wirkt sich nicht der Nachricht Ablauf, was bedeutet, dass die verzögerte Nachrichten weiterhin ablaufen können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Sequenznummer der letzten eingesehenen Nachricht ab.</summary>
        <value>Die Sequenznummer der letzten eingesehenen Nachricht.</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="OnAbandonAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnAbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnAbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnAbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnAbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnAbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnClosingAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCompleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnCompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnCompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"></param>
        <summary />
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetterAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null, string deadLetterReason = null, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null, Optional deadLetterReason As String = null, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeadLetterAsync (lockToken, propertiesToModify, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeferAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageHandler">
      <MemberSignature Language="C#" Value="protected virtual void OnMessageHandler (Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnMessageHandler(class Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnMessageHandler(Microsoft.Azure.ServiceBus.MessageHandlerOptions,System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnMessageHandler (registerHandlerOptions As MessageHandlerOptions, callback As Func(Of Message, CancellationToken, Task))" />
      <MemberSignature Language="F#" Value="abstract member OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.OnMessageHandler (registerHandlerOptions, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="registerHandlerOptions">To be added.</param>
        <param name="callback">To be added.</param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeekAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync (long fromSequenceNumber, int messageCount = 1);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnPeekAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnPeekAsync (fromSequenceNumber As Long, Optional messageCount As Integer = 1) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnPeekAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnPeekAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveAsync (maxMessageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveAsync (maxMessageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="serverWaitTime"></param>
        <summary />
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync (long[] sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync(int64[] sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveDeferredMessageAsync(System.Int64[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveDeferredMessageAsync (sequenceNumbers As Long()) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveDeferredMessageAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Int64[]" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLockAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;DateTime&gt; OnRenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; OnRenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnRenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnRenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.OnRenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnRenewLockAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>Der Asynchronour-Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dauer, die nach der einzelnen Vorgänge Timeout erzwungen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public virtual string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Der Pfad der Entität für dieser Empfänger. Für Warteschlangen dies den Namen, aber für Abonnements wird dies den Pfad sein.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die nächste active Nachricht ohne Änderung des Zustands der Empfänger oder die Quelle der Meldung ab.
            </summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt. Gibt null zurück, wenn nichts einsehen.</returns>
        <remarks>
            Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger. Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.
            Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.
            Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">Die Anzahl der Meldungen.</param>
        <summary>
            Ruft den nächsten Batch aktiver Nachrichten ohne Ändern des Zustands der Empfänger oder die Quelle der Meldung ab.
            </summary>
        <returns>Liste der <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt. Gibt null zurück, wenn nichts einsehen.</returns>
        <remarks>
            Der erste Aufruf von <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> Ruft die erste aktive Nachricht für diesen Empfänger. Jeder nachfolgender Aufruf ruft die nachfolgende Meldung in der Entität ab.
            Im Gegensatz zu einer empfangenen Nachricht eingesehenen Nachricht keine Sperrtoken zugeordnet, und daher nicht abgeschlossen/abgebrochen/zurückgestellt/besaß/Renewed.
            Darüber hinaus im Gegensatz zu <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, diese Methode wird abgerufen, auch verzögerte Nachrichten (jedoch nicht die Nachrichten als unzustellbar gekennzeichnet)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Die Sequenznummer ab dem die Nachricht zu lesen.</param>
        <summary>
            Liest asynchron die nächste Nachricht, ohne den Zustand der Empfänger oder die Quelle der Meldung zu ändern.
            </summary>
        <returns>Den asynchronen Vorgang, die gibt die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , die die nächste zu lesende Nachricht darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">Der Ausgangspunkt, ab, der einen Nachrichtenbatch durchsucht wird.</param>
        <param name="messageCount">Die Anzahl der abzurufenden Nachrichten.</param>
        <summary>Liest einen Nachrichtenbatch an.</summary>
        <returns>Ein Nachrichtenbatch eingesehen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Prefetch beschleunigt den Nachrichtenfluss durch ins Leben gerufen, eine Nachricht, die für den lokalen Abruf unmittelbar verfügbar sein, wenn und vor der Anwendung, für eine aufgefordert Verwendung empfangen.
            Einen Wert ungleich Null festlegen, vorab PrefetchCount Anzahl der Nachrichten abruft.
            Festlegen des Werts auf 0 (null) wird Prefetch deaktiviert.
            Der Standardwert ist 0.
            </summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks>
          <para>
            Wenn Sie Prefetch aktiviert ist, wird der Empfänger – abrufen Nachrichten mehr anzeigt, maximal der Größe PrefetchCount als was die Anwendung sofort anfordert. Ein einzelner Aufruf der ursprünglichen Receive/ReceiveAsync wird daher eine Nachricht abrufen, für sofortigen Verbrauch, die so bald wie verfügbaren zurückgegeben werden, und der Client zum Abrufen von weiterer Nachrichten zum Ausfüllen des Prefetch-Puffers im Hintergrund fortgesetzt wird.
            </para>
          <para>
            Während der Nachrichten im Puffer Prefetch verfügbar sind, alle nachfolgenden ReceiveAsync-Aufrufe werden sofort aus dem Puffer erfüllt, und wie Speicherplatz verfügbar ist, wird der Puffer im Hintergrund aufgefüllt. Keine Nachrichten für die Übermittlung verfügbar sind, wird der Empfangsvorgang und dann warten, oder blockieren wie erwartet ausgleichen den Puffer.
            </para>
          <para>Prefetch funktioniert auch gleichwertig mit der <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> APIs.</para>
          <para>Updates für diesen Wert wirksam, auf die nächste empfangsaufruf an den Dienst.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.
            </summary>
        <returns>Die empfangene Nachricht. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Timeout nach der Dauer des Vorgangs<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">Die maximale Anzahl von Nachrichten, die empfangen werden.</param>
        <summary>
            Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.
            </summary>
        <returns>Liste der Nachrichten empfangen. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>
            Empfangen von Nachrichten aus der Entität definiert, indem <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.
            </summary>
        <returns>Die empfangene Nachricht. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>
            Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss). Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">Die maximale Anzahl von Nachrichten, die empfangen werden.</param>
        <param name="operationTimeout">Der Zeitraum der Client wartet, eine Nachricht empfängt, bevor ein Timeout eintritt.</param>
        <summary>
            Empfängt ein Maximum von <paramref name="maxMessageCount" /> Nachrichten aus der Entität, die durch definierten <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> mit <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> Modus.
            </summary>
        <returns>Liste der Nachrichten empfangen. Gibt null zurück, wenn keine Nachricht gefunden wird.</returns>
        <remarks>Empfangen von weniger als <paramref name="maxMessageCount" /> Nachrichten bildet kein Anzeichen für leere Entität.
            Der Parameter <paramref name="operationTimeout" /> enthält die Zeit, die vom Empfänger zum Herstellen einer Verbindungs (entweder beim ersten empfangen oder wenn die Verbindung erneut hergestellt werden muss). Wenn die Verbindung ein Timeout auftritt, löst dies <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> , enthält die Sequenznummern empfangen.</param>
        <summary>
            Empfängt eine <see cref="T:System.Collections.Generic.IList`1" /> verzögerte Nachrichten identifizierten <paramref name="sequenceNumbers" />.
            </summary>
        <returns>Nachrichten, die Sequenznummer identifizierte werden zurückgegeben. Gibt null zurück, wenn keine Nachrichten gefunden werden.
            Löst aus, wenn die Nachrichten, nicht verzögert wurde.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Die Sequenznummer der Nachricht, die empfangen werden.</param>
        <summary>
            Empfängt eine bestimmte verzögerte Nachricht erkennbar <paramref name="sequenceNumber" />.
            </summary>
        <returns>Nachricht erkennbar Sequenznummer <paramref name="sequenceNumber" />. Gibt null zurück, wenn keine solche Nachricht gefunden wird.
            Löst aus, wenn die Nachricht nicht verzögert wurde.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> des aktuellen Empfängers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Liste der derzeit registrierten Plug-Ins ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="messageHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</param>
        <param name="messageHandlerOptions">Die <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> Optionen zum Konfigurieren der Einstellungen der Datapump verwendet.</param>
        <summary>
            Empfangen von Nachrichten dauerhaft aus der Entität. Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`3" /> , Meldungen verarbeitet.</param>
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> wird, um Ausnahmen zu benachrichtigen.</param>
        <summary>
            Empfangen von Nachrichten dauerhaft aus der Entität. Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="messageReceiver.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin">Die <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> registrieren</param>
        <summary>
            Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit dieser Empfänger verwendet werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            Erneuert die Sperre für die Nachricht durch das Sperrtoken angegeben. Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).
            Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.
            Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Der Nachricht zugeordnete Sperrtoken.</param>
        <summary>
            Erneuert die Sperre für die Nachricht an. Die Sperre wird basierend auf der Einstellung für die Warteschlange angegeben erneuert werden.
            <returns>Neue Sperre token Ablaufdatum und die Uhrzeit in UTC-Format.</returns></summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Beim Empfang einer Nachricht im <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus wird die Nachricht ist für eine Dauer entsprechend den Angaben auf dem Server für diese Instanz Empfänger gesperrt, während der Erstellung der Warteschlange/Abonnement (LockDuration).
            Wenn die Verarbeitung der Nachricht länger als diese Dauer erforderlich ist, muss die Sperre erneuert werden.
            Bei jeder Verlängerung er setzt die Uhrzeit zurück, die Meldung durch die LockDuration, legen Sie für die Entität gesperrt ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="messageReceiver.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName">Die <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> des Plug-Ins zum aufgehoben werden.</param>
        <summary>
            Hebt die Registrierung einer <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>