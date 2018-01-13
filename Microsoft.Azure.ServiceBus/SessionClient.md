<Type Name="SessionClient" FullName="Microsoft.Azure.ServiceBus.SessionClient">
  <TypeSignature Language="C#" Value="public sealed class SessionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionClient&#xA;Inherits ClientEntity&#xA;Implements ISessionClient" />
  <TypeSignature Language="F#" Value="type SessionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISessionClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.ISessionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             Ein Client für die Sitzung kann verwendet werden, um Sitzungsobjekte übernehmen, die Interaktion mit der alle Nachrichten mit der gleichen SessionId verwendet werden kann.
             </summary>
    <remarks>
             Sie können eine beliebige Sitzung oder einer bestimmten Sitzung übernehmen (identifiziert durch <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> mithilfe eines Sitzungsclients.
             Nachdem Sie eine Sitzung akzeptiert haben, können Sie es als ein <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> der nur Nachrichten, die mit derselben Sitzungs-Id empfängt. Finden Sie unter <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> für die Verwendung von Sitzungsobjekt.
             Dabei wird AMQP-Protokolls, um mit dem Dienst kommunizieren.
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <example>
             So erstellen eine neue SessionClient
             <code>
             ISessionClient sessionClient = new SessionClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock);
             </code>
            
             Ein Sitzungsobjekt für einen bestimmten SessionId empfangen
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
            
             Eine beliebige Sitzung empfangen.
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="receiveMode">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden. Der Standardwert ist PeekLock-Modus.</param>
        <param name="retryPolicy">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> , die die Obergrenze von Nachrichten, die das Sitzungsobjekt wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt. Der Standardwert ist 0.</param>
        <summary>
            Erstellt eine neue SessionClient aus einem<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></summary>
        <remarks>Erstellt eine neue Verbindung mit der Entität, die für alle Sitzungen Objekte verwendet wird mit diesem Client akzeptiert.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="entityPath">Der Pfad der Entität für dieser Empfänger. Für Warteschlangen dies den Namen, aber für Abonnements wird dies den vollständigen Pfad sein.</param>
        <param name="receiveMode">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> verwendet, um anzugeben, wie Nachrichten empfangen werden. Der Standardwert ist PeekLock-Modus.</param>
        <param name="retryPolicy">Die <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> , bei der Kommunikation mit Service Bus verwendet werden. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount">Die <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> , die die Obergrenze von Nachrichten, die das Sitzungsobjekt wird aktiv empfängt, unabhängig davon, ob bei einem Empfangsvorgang ausstehende angibt. Der Standardwert ist 0.</param>
        <summary>
            Erstellt eine neue SessionClient aus einer angegebenen Zeichenfolge und Entität Verbindungspfad an.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit der Entität, die für alle Sitzungen Objekte verwendet wird mit diesem Client akzeptiert.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.
            Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die SessionId in allen Nachrichten vorhanden ist.</param>
        <summary>
            Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.
            Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Zeitspanne für den Aufruf warten soll, um die nächste Sitzung abzurufen.</param>
        <summary>
            Ruft ein Sitzungsobjekt aller <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.
            Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;AcceptMessageSessionAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die SessionId in allen Nachrichten vorhanden ist.</param>
        <param name="serverWaitTime">Zeitspanne für den Aufruf warten soll, um die nächste Sitzung abzurufen.</param>
        <summary>
            Ruft einen bestimmten Sitzungsobjekt identifizierten <paramref name="sessionId" /> , die zum Empfangen von Nachrichten für diese SessionId verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>Alle Plug-Ins auf registriert <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> gelten für jede <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> übernommen wird.
            Einzelne Sitzungen können zusätzliche Plug-Ins weitere registrieren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Pfad der Entität ab. Dies ist entweder der Name der Warteschlange oder den vollständigen Pfad des Abonnements.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="sessionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;OnClosingAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
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
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
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
            Ruft eine Liste der derzeit registrierten Plug-Ins ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="sessionClient.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
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
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin">Die zu registrierende <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</param>
        <summary>
            Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> mit dieser Empfänger verwendet werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="sessionClient.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
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