<Type Name="EventHubsConnectionStringBuilder" FullName="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubsConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type EventHubsConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EventHubsConnectionStringBuilder kann verwendet werden, um eine Verbindungszeichenfolge erstellen. diese Kommunikation mit Event Hubs Entitäten herstellen können.
            Sie können auch die grundlegende Validierung auf eine vorhandene Verbindungszeichenfolge verwendet werden.
            <para />Eine Verbindungszeichenfolge ist im Grunde eine Zeichenfolge von Schlüssel-Wert-Paar senkrechter umfasste ";". Grundlegende Format ist "&lt;Schlüssel&gt;=&lt;Wert&gt;[;&lt; Schlüssel&gt;=&lt;Wert&gt;] ", in dem unterstützten Schlüsselname lautet wie folgt: <para /> Endpunkt - URL, die der Event Hubs-Namespace enthält <para /> EntityPath - den Pfad an den Event Hub Entität <para /> SharedAccessKeyName - der entsprechenden freigegebenen Zugriffsrichtlinie im Schlüsselnamen für den Namespace oder Entität.
            <para />SharedAccessKey - Schlüssel für die entsprechenden SAS-Richtlinienregel des Namespace oder der Entität.
            </summary>
    <remarks>To be added.</remarks>
    <example>
            Beispielcode:
            <code>
            var connectionStringBuiler = new EventHubsConnectionStringBuilder(
                "amqps://EventHubsNamespaceName.servicebus.windows.net", 
                "EventHubsEntityName", // Event Hub Name 
                "SharedAccessSignatureKeyName", 
                "SharedAccessSignatureKey");
             string connectionString = connectionStringBuiler.ToString();
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">"ConnectionString" Ereignis-Hubs</param>
        <summary>
            ConnectionString-Format: Endpunkt = Sb: / / Namespace_DNS_Name; EntityPath = EVENT_HUB_NAME; SharedAccessKeyName = SHARED_ACCESS_KEY_NAME; SharedAccessKey = SHARED_ACCESS_KEY
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Pfad der Entität oder Event Hub-Name.</param>
        <param name="sharedAccessKeyName">Freigegebene Zugriffsschlüssel-name</param>
        <param name="sharedAccessKey">SAS-Schlüssel</param>
        <summary>
            Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessSignature, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessSignature, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessSignature As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessSignature, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Pfad der Entität oder Event Hub-Name.</param>
        <param name="sharedAccessSignature">Shared Access Signature (SAS)</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge</param>
        <summary>
            Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress">Vollständig qualifizierten Domänennamen für Event Hubs. Sehr wahrscheinlich {ihrnamespace}. servicebus.windows .net</param>
        <param name="entityPath">Pfad der Entität oder Event Hub-Name.</param>
        <param name="sharedAccessKeyName">Freigegebene Zugriffsschlüssel-name</param>
        <param name="sharedAccessKey">SAS-Schlüssel</param>
        <param name="operationTimeout">Timeout des Vorgangs für Event Hubs-Vorgänge</param>
        <summary>
            Erstellen Sie eine Verbindungszeichenfolge Ereignisformat<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventHubsConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="eventHubsConnectionStringBuilder.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt ein geklontes Objekt des aktuellen <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />.
            </summary>
        <returns>Ein neues<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Event Hubs-Endpunkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
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
            Der Pfadwert Entität aus der Verbindungszeichenfolge abrufen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            OperationTimeout ist in fehlerhaften Situationen auf, die den Aufrufer über die relevanten benachrichtigen angewendet.<see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
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
            Den Schlüsselwert der SAS-Richtlinie aus der Verbindungszeichenfolge abrufen
            </summary>
        <value>Freigegebenen SAS-Schlüssel</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
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
            Die SAS-Richtliniennamen Besitzer aus der Verbindungszeichenfolge abrufen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
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
            Ermittelt oder definiert das SAS-Zugriffstoken.
            </summary>
        <value>Shared Access Signature (SAS)</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="eventHubsConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine interoperable Verbindungszeichenfolge, die zur Verbindung mit Event Hubs-Namespace verwendet werden können
            </summary>
        <returns>die Verbindungszeichenfolge</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.EventHubs.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.EventHubs.TransportType with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Transporttyp für die Clientverbindung.
            Verfügbaren Optionen sind Amqp und AmqpWebSockets.
            Der Standardwert ist Amqp, wenn nicht angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>