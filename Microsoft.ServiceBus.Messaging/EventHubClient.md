<Type Name="EventHubClient" FullName="Microsoft.ServiceBus.Messaging.EventHubClient">
  <TypeSignature Language="C#" Value="public abstract class EventHubClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EventHubClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EventHubClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubClient = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Eine Premium-Klasse verwendet, um Ereignisse zu und von einem Event Hub senden und empfangen.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Instanz unter Verwendung einer Verbindungszeichenfolge aus der Einstellungen für die Anwendungskonfiguration.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>Diese Methode versucht, die Verbindungszeichenfolgeninformationen von "App.config" oder "Web.config"-Dateien abrufen. Benutzer muss die Verbindungszeichenfolge mithilfe des Abschnitts "AppSettings" der Konfiguration angeben. Das Format des Abschnitts lautet wie folgt:
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="enableLinkRedirect">Der Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientCredential, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="enableLinkRedirect">Der Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="userPasswordCredential">Die Kennwort-Anmeldeinformationen des Benutzers.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="enableLinkRedirect">Der Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
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
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedrectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="enableLinkRedirect">Der Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> mithilfe des Kontexts für Azure Active Directory-Authentifizierung.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="eventHubClient.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt einen Batch, in denen Daten von Ereignisobjekten für späteren Aufruf von SendBatch oder SendBatchAsync hinzugefügt werden kann.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die zu verwendende Verbindungszeichenfolge.</param>
        <summary>Erstellt eine neue Instanz des Event Hubs-Clients, die mithilfe der angegebenen Verbindungszeichenfolge. Sie können Auffüllen der <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft mit dem Namen des Event Hubs.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Objekt.</returns>
        <remarks>Die Verbindung entweder aus dem Azure-Portal abgerufen oder erstellt eine <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> Instanz.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der Parameter "ConnectionString" falsch ist.</exception>
        <example> Beispiel, das zum Auffüllen der EntityPath in "ConnectionString"<code>
            var connectionStringBuilder = new ServiceBusConnectionStringBuilder(connectionString);
            connectionStringBuilder.EntityPath = eventHubDescription.Path;
            
            Var EventHubClient = EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString());
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungszeichenfolge verwendet werden.</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt eine neue Instanz des Event Hubs-Clients, die mithilfe der angegebenen Verbindungszeichenfolge. Verwenden Sie diese Überladung nur, wenn die Verbindungszeichenfolge nicht verwendet die <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> Eigenschaft.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Objekt.</returns>
        <remarks>Die Verbindung entweder aus dem Azure-Portal abgerufen oder erstellt eine <see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" /> Instanz.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn das Format der Parameter falsch ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionedSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubSender CreatePartitionedSender (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubSender CreatePartitionedSender(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionedSender (partitionId As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionedSender : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="eventHubClient.CreatePartitionedSender partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die ID der Partition.</param>
        <summary>Erstellt einen Event Hubs-Sender für die angegebene Partition des Event Hubs.</summary>
        <returns>Gibt die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionedSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreatePartitionedSenderAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreatePartitionedSenderAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePartitionedSenderAsync (partitionId As String) As Task(Of EventHubSender)" />
      <MemberSignature Language="F#" Value="member this.CreatePartitionedSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;" Usage="eventHubClient.CreatePartitionedSenderAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die ID der Partition.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreatePartitionedSender(System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubSender CreateSender (string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubSender CreateSender(string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSender (publisher As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="member this.CreateSender : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="eventHubClient.CreateSender publisher" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Der Bezeichner des Verlegers.</param>
        <summary>Erstellt einen Sender Event Hubs für den angegebenen Verleger.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSenderAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateSenderAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateSenderAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSenderAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateSenderAsync () As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="abstract member CreateSenderAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="eventHubClient.CreateSenderAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt den Absender Event Hubs. Diese Methode ist für den internen Gebrauch und nicht aus Benutzercode heraus aufgerufen werden sollen.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreateSenderAsync (string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubSender&gt; CreateSenderAsync(string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSenderAsync (publisher As String) As Task(Of EventHubSender)" />
      <MemberSignature Language="F#" Value="member this.CreateSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;" Usage="eventHubClient.CreateSenderAsync publisher" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publisher">Der Bezeichner des Verlegers.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateSender(System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Nullable&lt;TimeSpan&gt; operationTimeout = null, bool enableLinkRedirect = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, bool enableLinkRedirect) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.Nullable{System.TimeSpan},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWithManagedServiceIdentity (endpointAddress As Uri, path As String, Optional operationTimeout As Nullable(Of TimeSpan) = null, Optional enableLinkRedirect As Boolean = true) As EventHubClient" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Nullable&lt;TimeSpan&gt; * bool -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.CreateWithManagedServiceIdentity (endpointAddress, path, operationTimeout, enableLinkRedirect)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enableLinkRedirect" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <param name="operationTimeout">
          <see cref="T:System.TimeSpan" />die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt</param>
        <param name="enableLinkRedirect">Der Wert, der angibt, ob dieser Transport an die Back-End-Server-umgeleitet werden kann.</param>
        <summary>Erstellt eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> mithilfe von Azure verwaltet Dienstidentität-Authentifizierung.</summary>
        <returns>Das neu erstellte Objekt der Event Hub-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableEntityLevelPerformanceCounters">
      <MemberSignature Language="C#" Value="public bool DisableEntityLevelPerformanceCounters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableEntityLevelPerformanceCounters As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableEntityLevelPerformanceCounters : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.DisableEntityLevelPerformanceCounters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert anzugeben, ob die Entität auf Leistungsindikatoren im Arbeitsspeicher gesammelt werden sollen. Beachten Sie, dass dies nur Einfluss auf die Entität auf Leistungsindikatoren und Namespace-Ebene Leistungsindikatoren werden immer gesammelt.
            </summary>
        <value>To be added.</value>
        <remarks>Dies ist standardmäßig auf "false" festgelegt: Standardmäßig bedeutet wir Entität Ebene Leistungsindikatoren sammeln. Das Festlegen dieses Werts wirkt sich nicht auf vorhandene erfassten Leistungsindikatoren und hält sich nur auf neue Entität erfassten Leistungsindikatoren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetConsumerGroup (string groupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetConsumerGroup(string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetConsumerGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroup (groupName As String) As EventHubConsumerGroup" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroup : string -&gt; Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" Usage="eventHubClient.GetConsumerGroup groupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName">Der Name der Gruppe.</param>
        <summary>Gibt die consumergruppe mit dem angegebenen Namen für das Empfangen von Ereignisdaten.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> Instanz, die consumergruppe entspricht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefaultConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetDefaultConsumerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubConsumerGroup GetDefaultConsumerGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetDefaultConsumerGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDefaultConsumerGroup () As EventHubConsumerGroup" />
      <MemberSignature Language="F#" Value="member this.GetDefaultConsumerGroup : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" Usage="eventHubClient.GetDefaultConsumerGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt die standardconsumergruppe, für das Empfangen von Ereignisdaten.</summary>
        <returns>Der standardmäßige <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</returns>
        <remarks>Standard-ConsumerGroup Prüfpunktvorgängen nicht möglich. Zum Ausführen von Checkpoint-Vorgängen sollten Benutzer eine explizite ConsumerGroup erstellen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation GetPartitionRuntimeInformation (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation GetPartitionRuntimeInformation(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionRuntimeInformation (partitionId As String) As PartitionRuntimeInformation" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionRuntimeInformation : string -&gt; Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&#xA;override this.GetPartitionRuntimeInformation : string -&gt; Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" Usage="eventHubClient.GetPartitionRuntimeInformation partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die Partitions-ID.</param>
        <summary>Ruft die Laufzeitinformationen für die angegebene Partition des Event Hubs ab.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt; GetPartitionRuntimeInformationAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionRuntimeInformationAsync (partitionId As String) As Task(Of PartitionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;&#xA;override this.GetPartitionRuntimeInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;" Usage="eventHubClient.GetPartitionRuntimeInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die Partitions-ID.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetPartitionRuntimeInformation(System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation GetRuntimeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation GetRuntimeInformation() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRuntimeInformation () As EventHubRuntimeInformation" />
      <MemberSignature Language="F#" Value="abstract member GetRuntimeInformation : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&#xA;override this.GetRuntimeInformation : unit -&gt; Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" Usage="eventHubClient.GetRuntimeInformation " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die Event Hubs-Laufzeitinformationen, die zum Erstellen erforderlich ist <see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /> oder <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> Objekte.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRuntimeInformationAsync () As Task(Of EventHubRuntimeInformation)" />
      <MemberSignature Language="F#" Value="abstract member GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;&#xA;override this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;" Usage="eventHubClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetRuntimeInformation" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubClient.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubClient.OnBeginClose (timeout, callback, state)" />
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
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubClient.OnBeginOpen (timeout, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält. Dieses Objekt wird übergeben, um die EndOpen delegieren, wenn der Vorgang abgeschlossen ist.</param>
        <summary>Führt die Begin-öffnen-Aktion an.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Öffnungsvorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubClient.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubClient.OnEndClose result" />
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
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubClient.OnEndOpen result" />
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
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Öffnungsvorgang verweist.</param>
        <summary>Führt die End-öffnen-Aktion an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Pfad des Event Hubs.</summary>
        <value>Der Pfad des Event Hubs.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, werden die Anzahl der Ereignisse, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert. Dieser Wert wird standardmäßig von geerbt <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> bei der Erstellung der aktuellen Instanz von der Factory-Methode. Der Standardwert ist, andernfalls 10.000.</summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks> Beachten Sie, dass die Anzahl die zu niedrig festlegen beeinflussen die Wirksamkeit des Event Hubs Aufruf empfangen wird.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Wert kleiner als der erforderliche Mindestwert von 10 ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, werden die maximale Größe (in Bytes), insgesamt, die eine transaktive Empfangsvorgänge aktiv zwischengespeichert. Die Größe der einzelnen Ereignisdaten richtet sich nach der <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> Eigenschaft.</summary>
        <value>Gibt <see cref="T:System.Int64" />zurück.</value>
        <remarks>Das Größenlimit für nicht absolut Grenze ist, und wechseln Sie mit der können von Maße wie (PrefetchSizeInBytes/256kBytes) Anzahl der Bytes Ereignis hinzukommen.
            Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> erstellt, die von dieser Instanz wird dieser Wert standardmäßig erben. Änderungen an dieser Wert wird nicht für bereits erstellte consumergruppe übernommen, aber verwendet werden, indem Sie neue <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> nach der Änderung erstellt wurden. Wenn auch dieser Wert auf Null-Wert wird festgelegt, <see cref="P:Microsoft.ServiceBus.Messaging.EventHubClient.PrefetchCount" /> auf 0 (null).
            Beachten Sie, dass die Größe zu niedrig festlegen beeinflussen die Wirksamkeit des Event Hubs Aufruf empfangen wird.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Größenwert kleiner als der erforderliche Mindestwert von 260 KB ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Send(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.Send(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (data As EventData)" />
      <MemberSignature Language="F#" Value="member this.Send : Microsoft.ServiceBus.Messaging.EventData -&gt; unit" Usage="eventHubClient.Send data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">Die Ereignisdaten.</param>
        <summary>Sendet Daten an einen Event Hub.</summary>
        <remarks>Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Instanz senden, die mit dieser Methode müssen die <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> festgelegt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendAsync(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (data As EventData) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">Der zu sendende <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />.</param>
        <summary>Sendet die Daten asynchron an einen Event Hub.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>Alle <see cref="T:Microsoft.ServiceBus.Messaging.EventData" /> Instanz senden, die mit dieser Methode müssen die <see cref="P:Microsoft.ServiceBus.Messaging.EventData.PartitionKey" /> festgelegt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (eventDataList As IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; unit" Usage="eventHubClient.SendBatch eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">Ein IEnumerable-Objekt, das mit Daten von Ereignisinstanzen ist.</param>
        <summary>Sendet einen Batch von Ereignisdaten.</summary>
        <remarks>Benutzer sollten sicherstellen, dass die Summe serialisierte Größe des <paramref name="eventDataList" /> sollte die maximale Größe der Datenübertragung ein Ereignis, also 256 k standardmäßig sein. Beachten Sie außerdem, dass sich einige Aufwand für den Batch zu bilden.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">Wird ausgelöst, wenn die Summe der Größe serialisiert <paramref name="eventDataList" /> überschreitet die maximale zulässige Größe für ein Ereignis Übertragung (256 k standardmäßig).</exception>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (eventDataList As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubClient.SendBatchAsync eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">Ein IEnumerable-Objekt, das mit Daten von Ereignisinstanzen ist.</param>
        <summary>Asynchron sendet einen Batch von Ereignisdaten.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</returns>
        <remarks>Benutzer sollten sicherstellen, dass die Summe serialisierte Größe des <paramref name="eventDataList" /> sollte die maximale Größe der Datenübertragung ein Ereignis, also 256 k standardmäßig sein. Beachten Sie außerdem, dass sich einige Aufwand für den Batch zu bilden.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">Wird ausgelöst, wenn die Summe der Größe serialisiert <paramref name="eventDataList" /> überschreitet die maximale zulässige Größe für ein Ereignis Übertragung (256 k standardmäßig).</exception>
      </Docs>
    </Member>
  </Members>
</Type>