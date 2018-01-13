<Type Name="QueueClient" FullName="Microsoft.Azure.ServiceBus.QueueClient">
  <TypeSignature Language="C#" Value="public class QueueClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.QueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueClient&#xA;Inherits ClientEntity&#xA;Implements IQueueClient" />
  <TypeSignature Language="F#" Value="type QueueClient = class&#xA;    inherit ClientEntity&#xA;    interface IQueueClient&#xA;    interface IReceiverClient&#xA;    interface IClientEntity&#xA;    interface ISenderClient" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.IQueueClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             QueueClient kann für alle grundlegenden Interaktionen mit Service Bus-Warteschlange verwendet werden.
             </summary>
    <remarks>Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" /> oder <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> für erweiterten Satz von Funktionen.
             Für die Kommunikation mit Service Bus verwendet AMQP-Protokolls.</remarks>
    <example>
             Erstellen Sie eine neue QueueClient
             <code>
             IQueueClient queueClient = new QueueClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             Senden einer Nachricht an die Warteschlange:
             <code>
             byte[] data = GetData();
             await queueClient.SendAsync(data);
             </code>
            
             Registrieren Sie einen Message-Handler, die aufgerufen wird, jedes Mal, wenn eine Nachricht empfangen wird.
             <code>
             queueClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the queueClient is opened in ReceiveMode.PeekLock mode.
                        await queueClient.CompleteAsync(message.SystemProperties.LockToken);
                    },
                    async (exceptionEvent) =&gt;
                    {
                        // Process the exception
                        Console.WriteLine("Exception = " + exceptionEvent.Exception);
                        return Task.CompletedTask;
                    });
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (connectionStringBuilder, receiveMode, retryPolicy)" />
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
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />HAVING-Namespace und die Warteschlange an.</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Warteschlangenvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> für Vorgänge in einer Warteschlange.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit der Warteschlange, die während des ersten Vorgangs von senden/empfangen geöffnet ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (connectionString, entityPath, receiveMode, retryPolicy)" />
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
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace-Verbindungszeichenfolge. Darf keine Warteschlangeninformationen enthalten.</param>
        <param name="entityPath">Name der Warteschlange</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Warteschlangenvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> für Vorgänge in einer Warteschlange.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit der Warteschlange, die während des ersten Vorgangs von senden/empfangen geöffnet ist.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (string endpoint, string entityPath, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (endpoint, entityPath, tokenProvider, transportType, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Pfad der Warteschlange.</param>
        <param name="tokenProvider">Tokenanbieter, der Sicherheitstoken für die Autorisierung zu generieren, wird.</param>
        <param name="transportType">Transporttyp aus.</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Warteschlangenvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Erstellt eine neue Instanz der Anwendungswarteschlangen-Client, die mit den angegebenen Endpunkt, der Entität Pfad und der Tokenanbieter.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht zu verwerfen.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, während die Nachricht aufzugeben.</param>
        <summary>
            Verwirft eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einem Sperrtoken. Dadurch wird die Nachricht erneut für die Verarbeitung zur Verfügung.
            </summary>
        <returns>To be added.</returns>
        <remarks>Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von diesem Client empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="queueClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.CancelScheduledMessageAsync(System.Int64)</InterfaceMember>
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
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Die <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> der Nachricht werden abgebrochen.</param>
        <summary>
            Bricht eine Nachricht, die geplant wurde.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteAsync lockToken" />
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
            Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken. Hierdurch wird die Nachricht aus der Warteschlange gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von diesem Client empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, wenn zum untergeordneten Warteschlange verschoben werden.</param>
        <summary>
            Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
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
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="queueClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.QueueClient/&lt;OnClosingAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.QueueClient.OperationTimeout" />
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
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.QueueClient.Path" />
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
        <summary>
            Ruft den Namen der Warteschlange ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.QueueClient.PrefetchCount" />
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
        <value>Die Anzahl der Nachrichten, die der warteschlangenclient gleichzeitig anfordern kann.</value>
        <remarks>
          <para>
            Wenn Prefetch aktiviert ist, wird der Client im stillen Modus abgerufen werden weitere Nachrichten, bis die Beschränkung der PrefetchCount als was die Anwendung sofort anfordert. Die Meldungsverteilschleife wird daher eine Nachricht zum sofortigen Verbrauch, die so bald wie verfügbaren zurückgegeben werden erwerben, und der Client wird fortgesetzt, Nachrichten, die zum Füllen des Prefetch-Puffers im Hintergrund weiter abzurufen.
            </para>
          <para>
            Während der Nachrichten im Puffer Prefetch verfügbar sind, alle nachfolgenden ReceiveAsync-Aufrufe werden sofort aus dem Puffer erfüllt, und wie Speicherplatz verfügbar ist, wird der Puffer im Hintergrund aufgefüllt. Keine Nachrichten für die Übermittlung verfügbar sind, wird der Empfangsvorgang und dann warten, oder blockieren wie erwartet ausgleichen den Puffer.
            </para>
          <para>Updates für diesen Wert wirksam, auf die nächste empfangsaufruf an den Dienst.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueName">
      <MemberSignature Language="C#" Value="public string QueueName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueueName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.QueueName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueName As String" />
      <MemberSignature Language="F#" Value="member this.QueueName : string" Usage="Microsoft.Azure.ServiceBus.QueueClient.QueueName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IQueueClient.QueueName</InterfaceMember>
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
        <summary>
            Ruft den Namen der Warteschlange ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode</InterfaceMember>
      </Implements>
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
            Ruft die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> für die QueueClient.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.QueueClient.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Liste der derzeit registrierten Plug-Ins für diese QueueClient ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="queueClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</param>
        <summary>
            Empfangen von Nachrichten dauerhaft aus der Entität. Registriert einen Nachrichtenhandler und einen neuen Thread zum Empfangen von Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`3" />) wird auf erwartet, jedes Mal, wenn eine neue Nachricht vom Empfänger empfangen wird.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="queueClient.RegisterPlugin serviceBusPlugin" />
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
            Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit diesem Anwendungswarteschlangen-Client verwendet werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)</InterfaceMember>
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="sessionHandlerOptions">Optionen zum Konfigurieren der Einstellungen der Datapump Sitzung verwendet.</param>
        <summary>
            Empfangen Sie sitzungsnachrichten fortlaufend aus der Warteschlange. Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch den warteschlangenclient auf erwartet.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen. </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</param>
        <summary>
            Empfangen Sie sitzungsnachrichten fortlaufend aus der Warteschlange. Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch den warteschlangenclient auf erwartet.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.Azure.ServiceBus.Message message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.Azure.ServiceBus.Message message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="queueClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message">Nachricht geplant werden</param>
        <param name="scheduleEnqueueTimeUtc">Die UTC-Zeit, an der die Nachricht zur Verarbeitung verfügbar sein sollen</param>
        <summary>
            Plant eine Meldung auf Service Bus zu einem späteren Zeitpunkt angezeigt werden.
            </summary>
        <returns>Die Sequenznummer der Nachricht, die geplant wurde.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.SendAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
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
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">Der <see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <summary>
            Sendet eine Nachricht an Service Bus.
            </summary>
        <returns>Ein asynchroner Vorgang</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; messageList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; messageList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (messageList As IList(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync messageList" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})</InterfaceMember>
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
        <Parameter Name="messageList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messageList">Die Liste der Nachrichten</param>
        <summary>
            Sendet eine Liste der Nachrichten in Service Bus.
            </summary>
        <returns>Ein asynchroner Vorgang</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="queueClient.UnregisterPlugin serviceBusPluginName" />
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
        <param name="serviceBusPluginName">Der Name <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> aufgehoben werden.</param>
        <summary>
            Hebt die Registrierung einer <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>