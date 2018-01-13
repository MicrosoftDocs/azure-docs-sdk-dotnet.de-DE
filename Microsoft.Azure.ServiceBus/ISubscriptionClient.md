<Type Name="ISubscriptionClient" FullName="Microsoft.Azure.ServiceBus.ISubscriptionClient">
  <TypeSignature Language="C#" Value="public interface ISubscriptionClient : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscriptionClient implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscriptionClient&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type ISubscriptionClient = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IReceiverClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             SubscriptionClient kann für alle grundlegenden Interaktionen mit einem Service Bus-Abonnement verwendet werden.
             </summary>
    <remarks>Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> für erweiterten Satz von Funktionen.</remarks>
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
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync description" />
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
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Eine Beschreibung der Regel, die die Regel hinzuzufügende bereitstellt.</param>
        <summary>
            Fügt eine Regel auf das aktuelle Abonnement zum Filtern der Nachrichten im Thema zum Abonnement erreicht.
            </summary>
        <returns>Eine Taskinstanz, die den asynchronen Hinzufügevorgang für die Regel darstellt.</returns>
        <remarks>
            Sie können Regeln für das Abonnement hinzufügen, die Filter entscheiden wird, welche Nachrichten aus dem Thema kann das Abonnement erreichen.
            Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.
            Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.
            Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren. d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync (ruleName, filter)" />
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
            Sie können Regeln für das Abonnement hinzufügen, die Filter entscheiden wird, welche Nachrichten aus dem Thema kann das Abonnement erreichen.
            Eine standardmäßige <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> Regel namens <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> wird immer während der Erstellung des Abonnements hinzugefügt.
            Sie können mehrere Regeln mit unterschiedlichen Namen zum selben Abonnement hinzufügen.
            Mehrere Filter mit logischen OR-Bedingung miteinander kombinieren. d. h., wenn ein beliebiger anzuwendender Filter erfolgreich ist, wird die Nachricht an das Abonnement übergeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="iSubscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="sessionHandlerOptions">Optionen zum Konfigurieren der Einstellungen der Datapump Sitzung verwendet.</param>
        <summary>
            Empfangen Sie sitzungsnachrichten fortlaufend aus dem Abonnement. Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen. </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler">Ein <see cref="T:System.Func`4" /> , Meldungen verarbeitet.
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />enthält die Sitzung, und muss verwendet werden, um auf Fertig stellen/Abandon/Deadletter oder andere Operationen mit solchen Ausführen der<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</param>
        <summary>
            Empfangen Sie sitzungsnachrichten fortlaufend aus dem Abonnement. Registriert einen Meldungshandler und einen neuen Thread zum Empfangen von Sitzung Nachrichten beginnt.
            Dieser Handler (<see cref="T:System.Func`4" />) wird jedes Mal, wenn eine neue Nachricht empfangen wird, durch die abonnementclient auf erwartet.
            </summary>
        <remarks>Aktivieren Sie Prefetch, um die Empfangsrate zu beschleunigen.
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.RemoveRuleAsync ruleName" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
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
            Ruft den Namen des Abonnements ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
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
            Ruft den Pfad des Themas für dieses Abonnement ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>