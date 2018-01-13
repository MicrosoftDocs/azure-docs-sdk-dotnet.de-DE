<Type Name="SubscriptionClient" FullName="Microsoft.Azure.ServiceBus.SubscriptionClient">
  <TypeSignature Language="C#" Value="public class SubscriptionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionClient&#xA;Inherits ClientEntity&#xA;Implements ISubscriptionClient" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISubscriptionClient&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.ISubscriptionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             SubscriptionClient kann für alle grundlegenden Interaktionen mit einem Service Bus-Abonnement verwendet werden.
             </summary>
    <remarks>Für die Kommunikation mit Servicebus verwendet AMQP-Protokolls. Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> für erweiterten Satz von Funktionen.</remarks>
    <example>
             Erstellen Sie eine neue SubscriptionClient
             <code>
             ISubscriptionClient subscriptionClient = new SubscriptionClient(
                 namespaceConnectionString,
                 topicName,
                 subscriptionName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             Registrieren Sie einen Message-Handler, die aufgerufen wird, jedes Mal, wenn eine Nachricht empfangen wird.
             <code>
             subscriptionClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the subscriptionClient is opened in ReceiveMode.PeekLock mode.
                        await subscriptionClient.CompleteAsync(message.SystemProperties.LockToken);
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
      <MemberSignature Language="C#" Value="public SubscriptionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionStringBuilder, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />Namespace und Thema Dateien mit.</param>
        <param name="subscriptionName">Name des Abonnements.</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Abonnementvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" /> Vorgänge in einem Abonnement durchzuführen.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit dem Abonnement während der ersten geöffnet wird Empfangsvorgang.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string connectionString, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string topicPath, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionString, topicPath, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace-Verbindungszeichenfolge. Thema oder Abonnement Informationen müssen nicht enthalten.</param>
        <param name="topicPath">Der Pfad zu dem Thema.</param>
        <param name="subscriptionName">Name des Abonnements.</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Abonnementvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Instanziiert eine neue <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" /> Vorgänge in einem Abonnement durchzuführen.
            </summary>
        <remarks>Erstellt eine neue Verbindung mit dem Abonnement während der ersten geöffnet wird Empfangsvorgang.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string endpoint, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string topicPath, string subscriptionName, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (endpoint, topicPath, subscriptionName, tokenProvider, transportType, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="topicPath">Themenpfad.</param>
        <param name="subscriptionName">Name des Abonnements.</param>
        <param name="tokenProvider">Tokenanbieter, der Sicherheitstoken für die Autorisierung zu generieren, wird.</param>
        <param name="transportType">Transporttyp aus.</param>
        <param name="receiveMode">Modus des empfangen von Nachrichten. Standardmäßig <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />. PeekLock.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie für Abonnementvorgänge. Der Standardwert ist<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            Erstellt eine neue Instanz der abonnementclient, die mit den angegebenen Endpunkt, der Entität Pfad und der Tokenanbieter.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <remarks>Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von diesem Client empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;AddRuleAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Eine Beschreibung der Regel, die die Regel hinzuzufügende bereitstellt.</param>
        <summary>
            Fügt eine Regel auf das aktuelle Abonnement zum Filtern der Nachrichten im Thema zum Abonnement erreicht.
            </summary>
        <returns>Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</returns>
        <remarks>
            Sie können Regeln für das Abonnement hinzufügen, die entscheidet, welche Nachrichten aus dem Thema erreichen kann das Abonnement.
            Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.
            Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.
            Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren. d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)</InterfaceMember>
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
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">To be added.</param>
        <param name="filter">Der Filterausdruck für den Nachrichten berücksichtigt werden.</param>
        <summary>
            Fügt eine Regel auf das aktuelle Abonnement zum Filtern der Nachrichten im Thema zum Abonnement erreicht.
            </summary>
        <returns>Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</returns>
        <remarks>
            Sie können Regeln für das Abonnement hinzufügen, die entscheidet, welche Nachrichten aus dem Thema erreichen kann das Abonnement.
            Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.
            Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.
            Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren. d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.
            Maximal zulässige Länge von Regelname ist 50 Zeichen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
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
            Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken. Hierdurch wird die Nachricht aus dem Abonnement gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von diesem Client empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</param>
        <summary>
            Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Unterwarteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> oder <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von diesem Client empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;&#xA;override this.GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="subscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;GetRulesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Rufen Sie aller Regeln, die dem Abonnement zugeordnet ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;OnClosingAsync&gt;d__61))</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
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
            Ruft den formatierten Pfad des Clients Abonnement ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
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
        <value>Die Anzahl der Nachrichten, die der abonnementclient gleichzeitig anfordern kann.</value>
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
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
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
            Ruft die <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> für die SubscriptionClient.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
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
            Ruft eine Liste der derzeit registrierten Plug-Ins für diese SubscriptionClient ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
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
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="subscriptionClient.RegisterPlugin serviceBusPlugin" />
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
            Registriert eine <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> zum Empfangen von Nachrichten von Service Bus verwendet werden soll.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)</InterfaceMember>
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
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen. </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
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
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.
            </summary>
        <remarks>  Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;RemoveRuleAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName">Der Name der Regel.</param>
        <summary>
            Entfernt die Regel für das Abonnement identifizierten <paramref name="ruleName" />.
            </summary>
        <returns>Eine Taskinstanz, die den asynchronen Entfernungsvorgang für die Regel darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName</InterfaceMember>
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
            Ruft den Namen des Abonnements ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath</InterfaceMember>
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
            Ruft den Pfad der im entsprechenden Thema.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="subscriptionClient.UnregisterPlugin serviceBusPluginName" />
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