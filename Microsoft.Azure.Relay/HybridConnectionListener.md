<Type Name="HybridConnectionListener" FullName="Microsoft.Azure.Relay.HybridConnectionListener">
  <TypeSignature Language="C#" Value="public class HybridConnectionListener : Microsoft.Azure.Relay.IConnectionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionListener extends System.Object implements class Microsoft.Azure.Relay.IConnectionStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionListener" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionListener&#xA;Implements IConnectionStatus" />
  <TypeSignature Language="F#" Value="type HybridConnectionListener = class&#xA;    interface IConnectionStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Relay.IConnectionStatus</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt einen Listener für das Akzeptieren von HybridConnections von Remoteclients bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : string -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.  Diese Verbindungszeichenfolge muss die EntityPath-Eigenschaft enthalten.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> Instanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener (connectionString, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die verwendete Verbindungszeichenfolge. Diese Verbindungszeichenfolge muss die EntityPath-Eigenschaft nicht enthalten.</param>
        <param name="path">Der Pfad zu der HybridConnection.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> eine Verbindungszeichenfolge sowie der angegebenen HybridConection Pfad. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.Relay.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die Adresse, an der HybridConnections überwacht werden soll.  Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".</param>
        <param name="tokenProvider">Für die Verbindung von diesem Listener mit Service Bus die TokenProvider dar.</param>
        <summary>
            Erstellen Sie eine neue Instanz der HybridConnectionListener HybridConnections annimmt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; AcceptConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; AcceptConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.AcceptConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.AcceptConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionListener.AcceptConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Akzeptiert eine neue HybridConnection, die von einem Remoteclient und gibt den Stream initiiert wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext,System.Threading.Tasks.Task&lt;bool&gt;&gt; AcceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.Relay.RelayedHttpListenerContext, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; AcceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.AcceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptHandler As Func(Of RelayedHttpListenerContext, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.AcceptHandler : Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext, System.Threading.Tasks.Task&lt;bool&gt;&gt; with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionListener.AcceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht es, installieren einen benutzerdefinierten Ereignishandler, der Anforderungsheader überprüfen kann, Antwortheader steuern, entscheiden Sie, ob annehmen oder Ablehnen einer Aktualisierung WebSocket Anforderung, und die statusbeschreibung/Code zu steuern, wenn ablehnen.
            Die AcceptHandler sollte eine Clientanforderung oder "false" Ablehnen "true" zurückgeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionListener.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Adresse für das Abhören von HybridConnections ab.  Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> mithilfe der Standard-Timeoutwert.
            Es sei denn, in der Verbindungszeichenfolge angegeben ist der Standardwert 1 Minute.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein Abbruchtoken, das überwacht werden soll.</param>
        <summary>
            Schließt die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> mithilfe der bereitgestellte CancellationToken.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : TimeSpan -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;CloseAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">Ein Timeout berücksichtigt.</param>
        <summary>
            Schließt die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> mithilfe des angegebenen Timeouts.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connecting">
      <MemberSignature Language="C#" Value="public event EventHandler Connecting;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Connecting" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Connecting" />
      <MemberSignature Language="VB.NET" Value="Public Event Connecting As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Connecting : EventHandler " Usage="member this.Connecting : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Connecting</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Wird ausgelöst, wenn der Listener versucht wird, nach einer unterbrochenen Verbindung eine Verbindung mit Service Bus.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionListener.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;GetRuntimeInformationAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> für diese HybridConnection-Entität mithilfe der Standard-Timeoutwert.
            Es sei denn, in der Verbindungszeichenfolge angegeben ist der Standardwert 1 Minute.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionListener.GetRuntimeInformationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein Abbruchtoken, das überwacht werden soll.</param>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> für diese mithilfe der bereitgestellten CancellationToken HybridConnection-Entität.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOnline">
      <MemberSignature Language="C#" Value="public bool IsOnline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOnline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.IsOnline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOnline As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOnline : bool" Usage="Microsoft.Azure.Relay.HybridConnectionListener.IsOnline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der bestimmt, ob die Verbindung online ist.</summary>
        <value>"true", wenn die Verbindung aktiv und online ist; "false", wenn keine Verbindung zu Azure Service Bus aus dem aktuellen Netzwerkort besteht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastError">
      <MemberSignature Language="C#" Value="public Exception LastError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception LastError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.LastError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastError As Exception" />
      <MemberSignature Language="F#" Value="member this.LastError : Exception" Usage="Microsoft.Azure.Relay.HybridConnectionListener.LastError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, der letzte Fehler beim Versuch, die Verbindung aus dem offline-Zustand wiederherzustellen.</summary>
        <value>Gibt eine <see cref="T:System.Exception" /> , die den letzten Fehler enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="public event EventHandler Offline;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Offline" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Offline" />
      <MemberSignature Language="VB.NET" Value="Public Event Offline As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Offline : EventHandler " Usage="member this.Offline : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Offline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Wird ausgelöst, wenn der Listener nicht mehr versucht wird, (re) mit Service Bus zu verbinden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="public event EventHandler Online;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Online" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Online" />
      <MemberSignature Language="VB.NET" Value="Public Event Online As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Online : EventHandler " Usage="member this.Online : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Online</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Wird ausgelöst, wenn der Listener wurde erfolgreich mit ServiceBus verbunden ist
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Öffnet die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> und registriert ihn als einen Service Bus-Listener.
            Es sei denn, in der Verbindungszeichenfolge angegeben ist der Standardwert 1 Minute.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;OpenAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein Abbruchtoken, das überwacht werden soll.</param>
        <summary>
            Öffnet die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> und registriert ihn als einen Service Bus-Listener.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : TimeSpan -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;OpenAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">Ein Timeout berücksichtigt.</param>
        <summary>
            Öffnet die <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> und registriert ihn als einen Service Bus-Listener.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionListener.Proxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.IWebProxy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Proxyinformationen für die Verbindung mit Service Bus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.TokenProvider TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionListener.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die TokenProvider zum Authentifizieren von diesem Listener HybridConnection ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="hybridConnectionListener.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.  Enthält eine TrackingId für die End-to-End-Korrelation.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>