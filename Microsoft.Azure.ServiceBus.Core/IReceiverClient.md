<Type Name="IReceiverClient" FullName="Microsoft.Azure.ServiceBus.Core.IReceiverClient">
  <TypeSignature Language="C#" Value="public interface IReceiverClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReceiverClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReceiverClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type IReceiverClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IClientEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine Schnittstelle, die zum beschreiben allgemeine Funktionen zum Empfangen von Nachrichten aus <see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" /> und <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />.
            </summary>
    <remarks>Verwendung <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> für erweiterten Satz von Funktionen.</remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht zu verwerfen.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, während die Nachricht aufzugeben.</param>
        <summary>
            Verwirft eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit einem Sperrtoken. Dadurch wird die Nachricht erneut für die Verarbeitung zur Verfügung.
            </summary>
        <returns>To be added.</returns>
        <remarks>Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Aufgeben einer Nachricht, erhöhen Sie die Übermittlungsanzahl der Nachricht.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.CompleteAsync lockToken" />
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
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht abgeschlossen.</param>
        <summary>
            Schließt eine <see cref="T:Microsoft.Azure.ServiceBus.Message" /> mit dem Sperrtoken. Hierdurch wird die Nachricht aus der Warteschlange gelöscht.
            </summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">Das Sperrtoken der entsprechenden Nachricht an eine Warteschlange für unzustellbare Nachrichten.</param>
        <param name="propertiesToModify">Die Eigenschaften der Nachricht zu ändern, wenn zum untergeordneten Warteschlange verschoben werden.</param>
        <summary>
            Wird eine Nachricht in die Unterwarteschlange für unzustellbare Nachrichten verschoben.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
            Eine Sperrtoken finden Sie im <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, nur wenn <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> festgelegt ist, um <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.
            Um eine Nachricht aus der Warteschlange für unzustellbare Nachrichten empfangen zu können, benötigen Sie ein neues <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, durch den entsprechenden Pfad.
            Sie können <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> , dazu verwenden können.
            Dieser Vorgang kann nur für Nachrichten ausgeführt werden, die von dieser Empfänger empfangen wurden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
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
            Ruft den Pfad der ab dem <see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />. Dies ist entweder der Name der Warteschlange oder den vollständigen Pfad des Abonnements.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <value>To be added.</value>
        <remarks>
          <para>
            Wenn Sie Prefetch aktiviert ist, wird der Empfänger – abrufen Nachrichten mehr anzeigt, maximal der Größe PrefetchCount als was die Anwendung sofort anfordert. Ein einzelner Aufruf der ursprünglichen Receive/ReceiveAsync wird daher eine Nachricht abrufen, für sofortigen Verbrauch, die so bald wie verfügbaren zurückgegeben werden, und der Client zum Abrufen von weiterer Nachrichten zum Ausfüllen des Prefetch-Puffers im Hintergrund fortgesetzt wird.
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
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
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
            Verwendung <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> zum Konfigurieren der Einstellungen der Datapump.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>