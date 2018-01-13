<Type Name="TopicClient" FullName="Microsoft.ServiceBus.Messaging.TopicClient">
  <TypeSignature Language="C#" Value="public abstract class TopicClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TopicClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TopicClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type TopicClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Eine Premium-Klasse, die zur Verwendung für den Zugriff auf eine <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> laufzeitvorgänge ausführen.</summary>
    <remarks>To be added.</remarks>
    <altmember cref="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
    <example>
      <code>
             Erstellen von Einstellungen für die MessagingFactory (für Rutime Vorgänge) MessagingFactorySettings FactorySettings neue MessagingFactorySettings() = {NetMessagingTransportSettings = neue NetMessagingTransportSettings(), Anmeldeinformationen = TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName, IssuerKey)};
             
             Erstellen der Factory MessagingFactory MessagingFactory = MessagingFactory.Create (MyServiceBusNamespace, FactorySettings);
                
                / / Senden von Nachrichten an ein Thema / / ***
             
            Erstellen von Thema Client TopicClient MyTopicClient = Factory. CreateTopicClient(myTopic);
             
             Erstellen Sie einen Sender //MessageSender MyMessageSender = myTopicClient.CreateSender(SendMode.Default);
             
            Senden von Nachrichten Liste &lt;Objekt&gt; Probleme = neue Liste &lt;Objekt&gt;(); Foreach (Var Problem Punkte) {myMessageSender.Send (neue BrokeredMessage(issue));}
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="topicClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Bei der Planung einer Nachricht zurückgegeben.</param>
        <summary>
            Bricht eine geplante Nachricht
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad.</param>
        <summary>Erstellt eine neue Instanz von <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen. Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben. Das Format des Abschnitts lautet wie folgt:
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Sercvice Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zum Thema.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zum Thema.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zum Thema.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="userPasswordCredential">Die Kennwort-Anmeldeinformationen des Benutzers.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zum Thema.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedrectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> unter Verwendung der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />zurück.</returns>
        <remarks>Diese Methode erwartet die bereitgestellte Verbindungszeichenfolge Ebene Entitätsinformationen z. B. den Pfad für die Entität und Authentifizierungsinformationen angegeben wurde.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.</param>
        <param name="path">Der Pfad.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe der angegebenen Verbindungszeichenfolge und den Pfad zu dem Thema. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>Diese Methode sollte nur mit einer Verbindungszeichenfolge verwendet werden, der Namespace-Authentifizierung auf Datenbankebene besitzt, da die bereitgestellte Verbindungszeichenfolge keine Ebene Entitätsinformationen zugeordnet haben sollte.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der Parameter falsch ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.TopicClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="Microsoft.ServiceBus.Messaging.TopicClient.CreateWithManagedServiceIdentity (endpointAddress, path, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Service Bus. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zum Thema.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="transportType">Messaging-Transporttyp.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (topicPath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.FormatTransferDeadLetterPath topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname.</param>
        <summary>Eine Hilfsprogrammmethode, die einen vollständigen Pfad bildet, der an die Dead Letter-Warteschlange im Thema Übertragung Thema verweist, erhält der Themenname Pfad und Abonnements.</summary>
        <returns>Gibt eine <see cref="T:System.String" /> , einen vollständigen Pfad, der an die Dead Letter-Warteschlange des Themas Übertragung im angegebenen Thema zeigt darstellt. Dieser Pfad kann im Erstellen von remoteereignisempfängern oder URI-Informationen (z. B. einen REST-URI) verwendet werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSubQueue">
      <MemberSignature Language="C#" Value="protected bool IsSubQueue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSubQueue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property IsSubQueue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSubQueue : bool" Usage="Microsoft.ServiceBus.Messaging.TopicClient.IsSubQueue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob der Empfänger einer Nachricht aus einer Unterwarteschlange erstellt wird.</summary>
        <value>"true", wenn der Empfänger einer Nachricht aus einer Unterwarteschlange erstellt wird; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.TopicClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die messaging-Factory, die verwendet wurde, bei der Erstellung dieser <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Objekt.</summary>
        <value>Der messaging-Factory, die verwendet wurde, bei der Erstellung dieser <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="topicClient.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Führt die Aktion abbrechen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird übergeben, um die EndClose delegieren, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Führt die Aktion "Schließen" beginnen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Schließvorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="topicClient.OnBeginCreateSender (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird zum Übergeben der <see cref="M:Microsoft.ServiceBus.Messaging.TopicClient.EndCreateSender(System.IAsyncResult)" /> Wenn der Vorgang abgeschlossen ist.</param>
        <summary>Führt die Begin Absender Aktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="topicClient.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <summary>Führt die Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="topicClient.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Schließvorgang verweist.</param>
        <summary>Führt die End-Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="topicClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen übergeordneten Methode verweist.</param>
        <summary>Führt das Ende Absender Aktion zu erstellen.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.TopicClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den vollständigen Pfadnamen der Datei.</summary>
        <value>Der vollständige Pfadname der Datei.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary> Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema. </summary>
        <returns> Zurückgeben der eingesehenen "brokeredmessage". Null wird zurückgegeben, wenn der Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="topicClient.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"> Die Sequenznummer der Nachricht zum Starten von einsehen. </param>
        <summary> Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema. </summary>
        <returns> Zurückgeben der eingesehenen "brokeredmessage". Null wird zurückgegeben, wenn der Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"> Die maximale Anzahl von Nachrichten einsehen. </param>
        <summary> Liest eine "brokeredmessage" aus der aktuellen Warteschlange/Thema. </summary>
        <returns> eine Liste der eingesehenen BrokeredMessages zurückzugeben. Eine leere Liste wird zurückgegeben, wenn Lesevorgang der Nachricht erhalten kann <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</returns>
        <remarks>Ein NULL-Wert kann von dieser API zurückgegeben sein, wenn der Vorgang wurde das angegebene Timeout überschritten, oder die Vorgänge, die erfolgreich war, aber es sind keine weiteren Nachrichten mehr empfangen werden soll.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="topicClient.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="topicClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="topicClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message">Nachricht geplant werden</param>
        <param name="scheduleEnqueueTimeUtc">Zeitpunkt der in die Warteschlange einreihen</param>
        <summary>
            Sendet eine Nachricht geplante
            </summary>
        <returns>Die Sequenznummer, die für den Abbruch erforderlich ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="topicClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">die zu sendende Meldung.</param>
        <summary>Sendet eine Nachricht über die <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> ist null.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die <paramref name="message" /> wurde bereits gesendet wurden, durch eine <see cref="T:Microsoft.ServiceBus.Messaging.TopicClient" /> oder <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> noch einmal.</exception>
        <exception cref="T:System.OperationCanceledException">Wird ausgelöst, wenn die Cliententität geschlossen oder abgebrochen wurde.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn ein e/a oder Sicherheit Fehler vorliegt.</exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException">Wird ausgelöst, wenn bei der Serialisierung oder Deserialisierung ein Fehler auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn das Thema nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein Messagingfehler.</exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">die zu sendende Meldung.</param>
        <summary>Sendet asynchron eine Meldung mit der <see cref="P:Microsoft.ServiceBus.Messaging.TopicClient.InternalSender" />.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="topicClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">Der zu sendenden Nachrichten.</param>
        <summary>Sendet eine Reihe von brokernachrichten (für die Batchverarbeitung).</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">Der zu sendenden Nachrichten.</param>
        <summary>Sendet asynchron eine Reihe von brokernachrichten (für die Batchverarbeitung).</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>