<Type Name="EventHubClient" FullName="Microsoft.Azure.EventHubs.EventHubClient">
  <TypeSignature Language="C#" Value="public abstract class EventHubClient : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EventHubClient extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EventHubClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubClient = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Verankern Sie die Klasse – alle EventHub Client Vorgänge beginnen Sie hier.
            Siehe <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override sealed System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;CloseAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt und zugeordnete Ressourcen frei <see cref="T:Microsoft.Azure.EventHubs.EventHubClient" />.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.Azure.EventHubs.ITokenProvider tokenProvider, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.Azure.EventHubs.ITokenProvider,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.Azure.EventHubs.ITokenProvider * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, tokenProvider, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.EventHubs.ITokenProvider" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Event Hub-Pfad</param>
        <param name="tokenProvider">Tokenanbieter, der Sicherheitstoken für die Autorisierung zu generieren, wird.</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge.</param>
        <param name="transportType">Der Transporttyp für Verbindung.</param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die mit den angegebenen Endpunkt, der Entität Pfad und der Tokenanbieter.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Event Hub-Pfad</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge.</param>
        <param name="transportType">Der Transporttyp für Verbindung.</param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Event Hub-Pfad</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge.</param>
        <param name="transportType">Der Transporttyp für Verbindung.</param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient Create (Uri endpointAddress, string entityPath, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient Create(class System.Uri endpointAddress, string entityPath, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.Create (endpointAddress, entityPath, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Event Hub-Pfad</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedirectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge.</param>
        <param name="transportType">Der Transporttyp für Verbindung.</param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die mit dem angegebenen Endpunkt, Entität Pfad, der authentifizierungskontext AAD.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.Azure.EventHubs.EventDataBatch" Usage="eventHubClient.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt einen Batch, in denen Daten von Ereignisobjekten hinzugefügt werden können, für den späteren Aufruf von "SendAsync".</summary>
        <returns>Gibt <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, DateTime startTime, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.DateTime,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * DateTime * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startTime">das Datum-Uhrzeit instant, das Empfangsvorgänge erhalten Start Ereignisse aus. Empfangene Ereignisse verfügen über <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> nach diesem Zeitpunkt.</param>
        <param name="epoch">ein eindeutiger Bezeichner (Epoche Wert), den der Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>
            Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.
            Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.
            <para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.
            <para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.
            <para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.
            </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startingOffset">der Offset, starten Sie den Empfang von Ereignissen aus. Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="epoch">ein eindeutiger Bezeichner (Epoche Wert), den den Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>
            Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.
            Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.
            <para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.
            <para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.
            <para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.
            </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateEpochReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver (string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateEpochReceiver(string consumerGroupName, string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Boolean,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateEpochReceiver : string * string * string * bool * int64 * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateEpochReceiver (consumerGroupName, partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startingOffset">der Offset, starten Sie den Empfang von Ereignissen aus. Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="offsetInclusive">Bei "true", die StartingOffset als inklusive Offset - behandelt wird wird d. h. das erste Ereignis zurückgegeben, das den Anfangsoffset verfügt. Normalerweise die erste zurückgegebene Ereignis ist das Ereignis nach der Startoffset.</param>
        <param name="epoch">ein eindeutiger Bezeichner (Epoche Wert), den den Dienst verwendet, um die Partition/Lease des Besitzes zu erzwingen. </param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>
             Erstellen Sie eine Basis Epoche EventHub-Empfänger für die angegebenen Partitions-Id und vom Anfang des Datenstroms Partition empfangen.
             Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.
             <para />Es ist wichtig, beim Empfänger Epoche basierend auf Folgendes achten: <para />-Besitz Erzwingung: nach der Erstellung eines Epoche basierend Empfängers können nicht Sie einen nicht-Epoche-Empfänger für das Kombinationsfeld für den gleichen ConsumerGroup Partition erstellt, bis alle um das Kombinationsfeld für den Empfänger werden geschlossen.
             <para />-Besitz stehlen: Wenn ein Empfänger mit höheren Epoche-Wert für ein Kombinationsfeld ConsumerGroup Partition erstellt wird, werden alle älteren Epoche Empfänger diese Kombinationsfeld Force geschlossen.
             <para />– Beliebige Empfänger geschlossen aufgrund des Besitzes zu einem Kombinationsfeld ConsumerGroup Partition verloren erhalten ReceiverDisconnectedException für alle Vorgänge von diesem Empfänger.
             </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"></param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die mithilfe der angegebenen Verbindungszeichenfolge. Sie können die EntityPath-Eigenschaft mit dem Namen des Event Hubs auffüllen.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionSender">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionSender CreatePartitionSender(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreatePartitionSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionSender (partitionId As String) As PartitionSender" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionSender : string -&gt; Microsoft.Azure.EventHubs.PartitionSender" Usage="eventHubClient.CreatePartitionSender partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">PartitionId von EventHub zum Senden der <see cref="T:Microsoft.Azure.EventHubs.EventData" />des an.</param>
        <summary>
            Erstellen einer <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" /> die veröffentlichen können <see cref="T:Microsoft.Azure.EventHubs.EventData" />des direkt zu einer bestimmten Event Hub-Partition (Absender Typ Iii. in der folgenden Liste).
            <para />Es gibt 3 Muster/Möglichkeiten zum Senden an EventHubs: <para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para></summary>
        <returns>Die erstellte PartitionSender</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionSender" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, DateTime startTime, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, valuetype System.DateTime startTime, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.DateTime,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * DateTime * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startTime, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startTime">Ereignisse von empfangen werden der DateTime-Wert, der Zeitpunkt, das Empfangsvorgänge gestartet wird. Empfangene Ereignisse verfügen über <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" /> nach diesem Zeitpunkt.</param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>
            Erstellen den EventHub-Empfänger für die angegebenen Partitions-Id und aus dem angegebenen Startoffset empfangen.
            Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.
            </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startingOffset, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startingOffset, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startingOffset">der Offset, starten Sie den Empfang von Ereignissen aus. Empfangen von Anfang die Stream-Verwendung<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
        <summary>
            Erstellen Sie einen Empfänger für eine bestimmte EventHub-Partition aus der bestimmte consumergruppe.
            <para />Hinweis: Es kann eine maximale Anzahl von Empfängern, die pro ConsumerGroup pro Partition parallel ausgeführt werden kann. Das Limit wird vom Event Hub-Dienst erzwungen,-Aktueller Grenzwert ist 5 Empfänger parallel. Müssen mehrere Empfänger müssen das Lesen aus Offsets, die liegen weit auseinander auf die gleiche consumergruppe / Kombinationsfeld partitionieren erheblich auf die Leistung auswirken. 
            </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.PartitionReceiver CreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,System.Boolean,Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * string * bool * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.CreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName">der Name der consumergruppe, die dieser Empfänger unter gruppiert werden sollen.</param>
        <param name="partitionId">Die Partition-Id, der der Empfänger zu gehört. Von dieser Partition nur werden alle Daten empfangen werden.</param>
        <param name="startOffset">der Offset, starten Sie den Empfang von Ereignissen aus. So erhalten Sie vom Anfang von Streams verwendet wurde:<see cref="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" /></param>
        <param name="offsetInclusive">"true", die StartingOffset als inklusive Offset - behandelt, d. h. das erste Ereignis zurückgegeben wird, wenn die <param name="receiverOptions">Optionen für einen Hub-Ereignisempfänger verwenden.</param>
            eine, die den Anfangsoffset hat. Normalerweise die erste zurückgegebene Ereignis ist das Ereignis nach der Startoffset.</param>
        <param name="receiverOptions">To be added.</param>
        <summary>
            Erstellen den EventHub-Empfänger für die angegebenen Partitions-Id und aus dem angegebenen Startoffset empfangen.
            Der Empfänger ist für einen bestimmten Event Hub-Partition aus der bestimmte consumergruppe erstellt.
            </summary>
        <returns>Die erstellte PartitionReceiver</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity (Uri endpointAddress, string entityPath, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.Azure.EventHubs.TransportType transportType = Microsoft.Azure.EventHubs.TransportType.Amqp);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.EventHubs.EventHubClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string entityPath, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.Azure.EventHubs.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.Azure.EventHubs.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.EventHubs.TransportType -&gt; Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.EventHubClient.CreateWithManagedServiceIdentity (endpointAddress, entityPath, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.Azure.EventHubs.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Event Hub-Pfad</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge.</param>
        <param name="transportType">Der Transporttyp für Verbindung.</param>
        <summary>
            Erstellt eine neue Instanz des Event Hubs-Clients, die unter Verwendung des angegebenen Endpunkt, die Entität Pfad auf der Azure verwaltete Dienstidentität-Authentifizierung.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> Ruft ab oder legt einen Wert, der angibt, ob der Empfänger die Common Language Runtime-Metrik aktiviert ist. </summary>
        <value> "true", wenn ein Client zugreifen möchte <see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" /> mit <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />. </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string" Usage="Microsoft.Azure.EventHubs.EventHubClient.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der EventHub ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.GetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetPartitionRuntimeInformationAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die Partitions-ID.</param>
        <summary>Ruft die Laufzeitinformationen für die angegebene Partition des Event Hubs ab.</summary>
        <returns>Gibt <see cref="T:Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;GetRuntimeInformationAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die EventHub-Laufzeitinformationen ab
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCloseAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnCloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.OnCloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
    <Member MemberName="OnCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver (string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Nullable&lt;DateTime&gt; startTime, Nullable&lt;long&gt; epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.EventHubs.PartitionReceiver OnCreateReceiver(string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int64&gt; epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnCreateReceiver(System.String,System.String,System.String,System.Boolean,System.Nullable{System.DateTime},System.Nullable{System.Int64},Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateReceiver : string * string * string * bool * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="eventHubClient.OnCreateReceiver (consumerGroupName, partitionId, startOffset, offsetInclusive, startTime, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.PartitionReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="epoch" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="consumerGroupName"></param>
        <param name="partitionId"></param>
        <param name="startOffset"></param>
        <param name="offsetInclusive"></param>
        <param name="startTime"></param>
        <param name="epoch"></param>
        <param name="receiverOptions"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt; OnGetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of EventHubPartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;" Usage="eventHubClient.OnGetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubPartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt; OnGetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnGetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member OnGetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;" Usage="eventHubClient.OnGetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRetryPolicyUpdate">
      <MemberSignature Language="C#" Value="protected override void OnRetryPolicyUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnRetryPolicyUpdate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.OnRetryPolicyUpdate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnRetryPolicyUpdate ()" />
      <MemberSignature Language="F#" Value="override this.OnRetryPolicyUpdate : unit -&gt; unit" Usage="eventHubClient.OnRetryPolicyUpdate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Behandeln Sie hier richtlinienaktualisierungen versuchen Sie es erneut.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</param>
        <summary>
            Senden von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> an Event Hub. Die gesendeten EventData werden auf der nach dem Zufallsprinzip ausgewählte EventHubs Partition aufgenommen.
            <para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit der Überladung SendBatch) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii.  <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diese Methode, wenn senden: <para>a) die <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> Vorgang hoch verfügbar sein und</para><para>b) die Daten gleichmäßig verteilt werden müssen alle Partitionen; Ausnahme wird, wenn eine Teilmenge der Partitionen nicht verfügbar sind</para> <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> sendet die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> zu einem Dienst-Gateway, die wiederum die EventData in eines der EventHub-Partitionen leitet.
            Hier wird der Algorithmus für die nachrichtenweiterleitung: <para>ich.  Weiterleiten der EventDatas EventHub-Partitionen, indem gleichmäßig verteilt Daten über alle Partitionen (zum Beispiel: Roundrobin-Methode der EventDatas auf alle EventHub-Partitionen) </para> <para>Ii. Wenn eine der Partitionen EventHub für einen Moment nicht verfügbar ist, das Gateway-Dienst automatisch erkannt und leitet Sie an eine andere verfügbare Partition - Sendevorgang hoch verfügbar machen.</para></summary>
        <returns>Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync eventDatas" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDatas">Ein Batch von Ereignissen an Event Hub senden.</param>
        <summary>
            Senden ein Batches von <see cref="T:Microsoft.Azure.EventHubs.EventData" /> an Event Hub. Die gesendeten EventData werden auf der nach dem Zufallsprinzip ausgewählte EventHub Partition aufgenommen.
            Dies ist die am häufigsten empfohlene Methode zum Senden an Event Hub.
            
            <para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, der verwendet wird, senden Sie einzelne <see cref="T:Microsoft.Azure.EventHubs.EventData" />. Verwenden Sie diese Überladung, wenn Sie einen Batch senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</para>
            
            Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen, die an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden Sie mehrere <see cref="T:Microsoft.Azure.EventHubs.EventData" />des in einer Transaktion. Acheieve ACID-Eigenschaften der Gatewaydienst leitet alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des im Batch in einer einzelnen EventHub partitionieren.</para></summary>
        <returns>Eine Aufgabe, die beim Abschluss der Sendevorgänge erfolgt.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <example>
            Beispielcode:
            <code>
            var client = EventHubClient.Create("__connectionString__");
            while (true)
            {
                var events = new List&lt;EventData&gt;();
                for (int count = 1; count &lt; 11; count++)
                {
                    var payload = new PayloadEvent(count);
                    byte[] payloadBytes = Encoding.UTF8.GetBytes(JsonConvert.SerializeObject(payload));
                    var sendEvent = new EventData(payloadBytes);
                    var applicationProperties = new Dictionary&lt;string, string&gt;();
                    applicationProperties["from"] = "csharpClient";
                    sendEvent.Properties = applicationProperties;
                    events.Add(sendEvent);
                }
                    
                await client.SendAsync(events);
                Console.WriteLine("Sent Batch... Size: {0}", events.Count);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventData, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventData">die <see cref="T:Microsoft.Azure.EventHubs.EventData" /> gesendet werden.</param>
        <param name="partitionKey">der partitionkey-Werte werden Hashwert berechnet werden soll, um zu bestimmen, die PartitionId die EventData zu senden. Für die empfangene Nachricht dies möglich, die am <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</param>
        <summary>
             Sendet eine "<see cref="T:Microsoft.Azure.EventHubs.EventData" /> mit einem PartitionKey an Event Hub. Alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des mit einem PartitionKey ist sichergestellt, dass auf die gleiche Partition aufgenommen.
             Dieses Muster senden hervorheben Korrelation der Daten über die allgemeine Verfügbarkeit und die Latenz.
             <para>Es gibt 3 Arten zum Senden an EventHubs, jeweils als eine Methode (zusammen mit seiner im Batchmodus Überladung) verfügbar gemacht:</para><para>i. <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>Ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> oder <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>Iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> oder <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> verwenden Sie diesen Typ des Sendeports ein, wenn: <para>eine) besteht der Bedarf für die Korrelation der Ereignisse, die auf der Grundlage Absender Instanz; Der Absender kann eine eindeutige ID zu generieren, und legen Sie es als PartitionKey - die für die empfangene Nachricht für die Korrelation verwendet werden können</para><para>b) der Client möchte Kontrolle über die Verteilung der Daten auf Partitionen zu übernehmen.</para>
             Mehrere PartitionKeys könnte zu einer einzigen Partition zugeordnet werden. EventHubs-Dienst verwendet einen proprietären Hash-Algorithmus eine PartitionId PartitionKey zuzuordnen.
             Mit diesem Typ des Sendeports (senden, die mit einer bestimmten PartitionKey) konnte in einigen Fällen in Partitionen zurückgeben, was nicht gleichmäßig verteilt sind. 
             </summary>
        <returns>eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData), partitionKey As String) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; * string -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync (eventDatas, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.EventHubClient/&lt;SendAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventDatas">der Batch von Ereignissen an Event Hub senden.</param>
        <param name="partitionKey">der partitionkey-Werte werden Hashwert berechnet werden soll, um zu bestimmen, die PartitionId die EventData zu senden. Für die empfangene Nachricht dies möglich, die am <see cref="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />.</param>
        <summary>
            Senden einer "Batch <see cref="T:Microsoft.Azure.EventHubs.EventData" /> mit demselben PartitionKey" an Event Hub. Alle <see cref="T:Microsoft.Azure.EventHubs.EventData" />des mit einem PartitionKey ist sichergestellt, dass auf die gleiche Partition aufgenommen.
            Mehrere PartitionKey werden zu einer einzigen Partition zugeordnet.
            <para>Es gibt 3 Arten an EventHubs, senden, um diesen speziellen Typ des Sendeports zu verstehen, finden Sie in der Überladung <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />, die vom selben Typ des Sendeports und wird verwendet, um die einzelnen senden <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para>Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" />des ist in den folgenden Fällen nützlich: <para>ich.    Effiziente senden - Senden eines <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximiert den Gesamtdurchsatz optimal mit der Anzahl der Sitzungen an EventHubs-Dienst erstellt.</para> <para>Ii.   Senden mehrere Ereignisse in einer Transaktion. Dies ist der Grund, warum gesendet, alle Ereignisse in einem Batch muss denselben PartitionKey (sodass sie nur zu einer Partition gesendet werden).</para></summary>
        <returns>eine Aufgabe, die abgeschlossen wird, wenn der Sendevorgang abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
        <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.EventHubs.EventHubClient.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>