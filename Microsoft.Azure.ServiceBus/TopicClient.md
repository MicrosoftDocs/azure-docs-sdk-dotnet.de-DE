<Type Name="TopicClient" FullName="Microsoft.Azure.ServiceBus.TopicClient">
  <TypeSignature Language="C#" Value="public class TopicClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.TopicClient" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicClient&#xA;Inherits ClientEntity&#xA;Implements ITopicClient" />
  <TypeSignature Language="F#" Value="type TopicClient = class&#xA;    inherit ClientEntity&#xA;    interface ITopicClient&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.ITopicClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             TopicClient kann für alle grundlegenden Interaktionen mit einem Service Bus-Thema verwendet werden.
             </summary>
    <remarks>Für die Kommunikation mit Service Bus verwendet AMQP-Protokolls.</remarks>
    <example>
             Erstellen Sie eine neue TopicClient
             <code>
             ITopicClient topicClient = new TopicClient(
                 namespaceConnectionString,
                 topicName,
                 RetryExponential);
             </code>
            
             Senden einer Nachricht an das Thema:
             <code>
             byte[] data = GetData();
             await topicClient.SendAsync(data);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (connectionStringBuilder, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />Namespace und Thema Dateien mit.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für das Thema Vorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.TopicClient" /> Vorgänge für ein Thema ausgeführt.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit dem Thema, das sich während des ersten Sendevorgangs geöffnet wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : string * string * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (connectionString, entityPath, retryPolicy)" />
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
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace-Verbindungszeichenfolge. Darf keine Thema Informationen enthalten.</param>
        <param name="entityPath">Pfad zu dem Thema</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für das Thema Vorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.TopicClient" /> Vorgänge für ein Thema ausgeführt.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit dem Thema, das sich während des ersten Sendevorgangs geöffnet wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (string endpoint, string entityPath, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (endpoint, entityPath, tokenProvider, transportType, retryPolicy)" />
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
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Themenpfad.</param>
        <param name="tokenProvider">Tokenanbieter, der Sicherheitstoken für die Autorisierung zu generieren, wird.</param>
        <param name="transportType">Transporttyp aus.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für das Thema Vorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Erstellt eine neue Instanz des Clients Thema mit den angegebenen Endpunkt, der Entität Pfad und der Tokenanbieter.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="topicClient.CancelScheduledMessageAsync sequenceNumber" />
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
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="topicClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.TopicClient/&lt;OnClosingAsync&gt;d__34))</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.TopicClient.OperationTimeout" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.TopicClient.Path" />
      <MemberType>Property</MemberType>
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
            Ruft den Namen des Themas.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.TopicClient.RegisteredPlugins" />
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
            Ruft eine Liste der derzeit registrierten Plug-Ins für diese TopicClient ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="topicClient.RegisterPlugin serviceBusPlugin" />
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
            Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit diesem Thema Client verwendet werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.Azure.ServiceBus.Message message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.Azure.ServiceBus.Message message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="topicClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
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
        <param name="message">Die <see cref="T:Microsoft.Azure.ServiceBus.Message" /> , muss geplant werden.</param>
        <param name="scheduleEnqueueTimeUtc">Die UTC-Zeit, an der die Nachricht zur Verarbeitung verfügbar sein sollen.</param>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.SendAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync message" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (messageList As IList(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync messageList" />
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
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string" Usage="Microsoft.Azure.ServiceBus.TopicClient.TopicName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ITopicClient.TopicName</InterfaceMember>
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
            Ruft den Namen des Themas.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="topicClient.UnregisterPlugin serviceBusPluginName" />
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