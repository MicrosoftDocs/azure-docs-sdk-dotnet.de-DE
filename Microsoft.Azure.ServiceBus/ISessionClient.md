<Type Name="ISessionClient" FullName="Microsoft.Azure.ServiceBus.ISessionClient">
  <TypeSignature Language="C#" Value="public interface ISessionClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISessionClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISessionClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type ISessionClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
             Beschreibt einen Client für die Sitzung an. Ein Client für die Sitzung kann verwendet werden, um Sitzungsobjekte übernehmen, die Interaktion mit der alle Nachrichten mit der gleichen SessionId verwendet werden kann.
             </summary>
    <remarks>
             Sie können eine beliebige Sitzung oder einer bestimmten Sitzung übernehmen (identifiziert durch <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> mithilfe eines Sitzungsclients.
             Nachdem Sie eine Sitzung akzeptiert haben, können Sie es als ein <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> der nur Nachrichten, die mit derselben Sitzungs-Id empfängt. Finden Sie unter <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> für die Verwendung von Sitzungsobjekt.
             <example>So erstellen eine neue SessionClient
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
             </code></example></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SessionClient" />
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
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
        <param name="serverWaitTime">Zeitdauer für die der Aufruf für warten soll, um die nächste Sitzung abzurufen.</param>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
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
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">Die SessionId in allen Nachrichten vorhanden ist.</param>
        <param name="serverWaitTime">Zeitdauer für die der Aufruf für warten soll, um die nächste Sitzung abzurufen.</param>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberType>Property</MemberType>
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
  </Members>
</Type>