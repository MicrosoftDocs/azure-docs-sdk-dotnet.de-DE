<Type Name="HybridConnectionClient" FullName="Microsoft.Azure.Relay.HybridConnectionClient">
  <TypeSignature Language="C#" Value="public class HybridConnectionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionClient" />
  <TypeSignature Language="F#" Value="type HybridConnectionClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Client für das neue Sendeseite HybridConnections initiieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient connectionString" />
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
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> Instanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">Die Adresse, an der HybridConnections überwacht werden soll.  Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".</param>
        <summary>
            Erstellen Sie eine neue Instanz der HybridConnectionClient zum Initiieren von HybridConnections, in denen keine Clientauthentifizierung erforderlich ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (connectionString, path)" />
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
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> eine Verbindungszeichenfolge sowie der angegebenen HybridConection Pfad. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der <paramref name="connectionString" /> Parameter ist falsch.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (address, tokenProvider)" />
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
        <param name="tokenProvider">Zum Herstellen einer Verbindung mit Service Bus die TokenProvider dar.</param>
        <summary>
            Erstellen Sie eine neue Instanz der HybridConnectionClient zum Initiieren von HybridConnections mit Clientauthentifizierung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Address" />
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
            Ruft die Adresse dieser HybridConnection Herstellen einer Verbindung über ab. Die Adresse, an der HybridConnections überwacht werden soll.
            Diese Adresse muss im Format "sb://contoso.servicebus.windows.net/yourhybridconnection".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.CreateConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.CreateConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionClient.CreateConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;CreateConnectionAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellt eine neue Sendeseite HybridConnection her und gibt den Stream zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;GetRuntimeInformationAsync&gt;d__28))</AttributeName>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync cancellationToken" />
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
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Timeouts für eine HybridConnection Verbindungen verwendet.  Standardwert ist 70 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
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
            Ruft die TokenProvider zum Authentifizieren von HybridConnections ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>