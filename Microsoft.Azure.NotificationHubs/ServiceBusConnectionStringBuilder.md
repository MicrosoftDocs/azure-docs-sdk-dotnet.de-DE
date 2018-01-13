<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Bietet eine einfache Möglichkeit zum Erstellen und verwalten den Inhalt von Verbindungszeichenfolgen. Sie können diese Klasse verwenden, um eine Verbindungszeichenfolge für das Erstellen von Client-messaging-Entitäten zu erstellen. Sie können auch die grundlegende Validierung auf eine vorhandene Verbindungszeichenfolge verwendet werden.</summary>
    <remarks>To be added.</remarks>
    <code>
                Der folgende Code gibt es ein vorhandenes / / Connection string, ändern Sie den Transporttyp zur Verwendung von Amqp, / / und die neue Verbindungszeichenfolge in der Zeichenfolge Formular Var Bulider zurückgeben = neue ServiceBusConnectionStringBuilder(connectionString); Bulider. TransportType = TransportType.Amqp; Console.WriteLine (Bulider. ToString());
                </code>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungszeichenfolge, die Sie aus dem Azure-Verwaltungsportal erhalten können.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> Klasse mit einer angegebenen vorhandenen Verbindungszeichenfolge.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException">Löst aus, wenn die Verbindungszeichenfolge der Endpunkte nicht vorhanden ist. Die Verbindungszeichenfolge besitzt nicht genügend Informationen, um einen Tokenanbieter bilden. Dies kann z. B. der Fall sein, wenn Sie eine SasIssuer-Namen, aber kein SasIssuer Schlüssel angegeben. Die <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" /> Wert ist nicht in einen gültigen <see cref="T:System.TimeSpan" /> Format. Die <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" /> oder <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" /> Werte sind nicht in einem Integer-Format.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingOAuthCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingOAuthCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingOAuthCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingOAuthCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingOAuthCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints">Die Gruppe von Endpunkten.</param>
        <param name="stsEndpoints">Der Satz von token Dienstendpunkte Sicherheit.</param>
        <param name="runtimePort">Die Common Language Runtime-Port.</param>
        <param name="managementPort">Der Management-Port.</param>
        <param name="domain">Die Domäne, in dem die Verbindung hergestellt wird.</param>
        <param name="user">Die Authentication-Benutzer.</param>
        <param name="password">Das Authentifizierungskennwort.</param>
        <summary>Erstellt eine Verbindungszeichenfolge mit Anmeldeinformationen für die Authentifizierung an.</summary>
        <returns>Die erstellte Servicebus-Verbindungszeichenfolge.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Endpunkte oder Benutzer oder Kennwort
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (Uri endpoint, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Uri endpoint, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoint As Uri, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoint, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt.</param>
        <param name="keyName">Der Name des SAS-Schlüssels.</param>
        <param name="key">Der SAS-Schlüssel.</param>
        <summary>Erstellen Sie eine Verbindungszeichenfolge mit dem SAS-Schlüssel.</summary>
        <returns>Die erstellte Verbindung mit dem SAS-Schlüssel.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, int runtimePort, int managementPort, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, int32 runtimePort, int32 managementPort, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoints, runtimePort, managementPort, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints">Die Gruppe von Endpunkten.</param>
        <param name="runtimePort">Die Common Language Runtime-Port.</param>
        <param name="managementPort">Der Management-Port.</param>
        <param name="keyName">Der Name des SAS-Schlüssels.</param>
        <param name="key">Der SAS-Schlüssel</param>
        <summary>Erstellen Sie eine Verbindungszeichenfolge mit dem SAS-Schlüssel.</summary>
        <returns>Die erstellte Verbindung mit dem SAS-Schlüssel.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (Uri endpoint, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Uri endpoint, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoint As Uri, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoint, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">Der Endpunkt.</param>
        <param name="issuer">Der Aussteller</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <summary>Erstellt eine Verbindungszeichenfolge mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen an.</summary>
        <returns>Die erstellte Verbindung mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Endpunkt "oder" Issuer "oder" issuerSecret
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoints, stsEndpoints, runtimePort, managementPort, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints">Die Endpunkte.</param>
        <param name="stsEndpoints">Der Satz von token Dienstendpunkte Sicherheit.</param>
        <param name="runtimePort">Die Common Language Runtime-Port.</param>
        <param name="managementPort">Der Management-Port.</param>
        <param name="issuer">Der Aussteller.</param>
        <param name="issuerSecret">Der geheime Ausstellerschlüssel.</param>
        <summary>Erstellt eine Verbindungszeichenfolge mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen an.</summary>
        <returns>Die erstellte Verbindung mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Endpunkte oder Aussteller oder issuerSecret
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingWindowsCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingWindowsCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingWindowsCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingWindowsCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingWindowsCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints">Die Gruppe von Endpunkten</param>
        <param name="stsEndpoints">Der Satz von token Dienstendpunkte Sicherheit.</param>
        <param name="runtimePort">Die Common Language Runtime-Port.</param>
        <param name="managementPort">Der Management-Port.</param>
        <param name="domain">Die Domäne, in dem die Verbindung hergestellt wird.</param>
        <param name="user">Der Benutzer.</param>
        <param name="password">Das Windows-Kennwort.</param>
        <summary>Erstellt eine Verbindungszeichenfolge, die mit Windows-Anmeldeinformationen an.</summary>
        <returns>Die erstellte Verbindungszeichenfolge.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Endpunkte oder Benutzer oder Kennwort
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine Auflistung von Dienstendpunkten. Jeder Endpunkt muss es sich um dieselbe Service Bus-Namespace verweisen.</summary>
        <value>Eine Sammlung von Endpunkten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteManagementEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteManagementEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteManagementEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteManagementEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteManagementEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die absolute verwaltungsendpunkte ab.</summary>
        <returns>Der absolute-Endpunkte</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteRuntimeEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteRuntimeEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteRuntimeEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteRuntimeEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteRuntimeEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die absolute Runtime Endpunkte ab.</summary>
        <returns>Die absolute Common Language Runtime-Endpunkte.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementPort">
      <MemberSignature Language="C#" Value="public int ManagementPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ManagementPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ManagementPort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die TCP-Portnummer für Verwaltungsvorgänge.</summary>
        <value>Der Management-Port.</value>
        <remarks>Dies ist nur in Serverszenario verwendet werden. Wenn die Verbindungszeichenfolge für Azure-Dienst zu generieren, sollte dies auf ihrem Standardwert bleiben;.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthDomain">
      <MemberSignature Language="C#" Value="public string OAuthDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthDomain As String" />
      <MemberSignature Language="F#" Value="member this.OAuthDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Authentifizierungsdomäne für die Verbindung.</summary>
        <value>Die Authentifizierungsdomäne für die Verbindung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString OAuthPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString OAuthPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.OAuthPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Authentifizierungskennwort für die Verbindung.</summary>
        <value>Das Authentifizierungskennwort für die Verbindung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthUsername">
      <MemberSignature Language="C#" Value="public string OAuthUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthUsername As String" />
      <MemberSignature Language="F#" Value="member this.OAuthUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Benutzernamen der Authentifizierung für die Verbindung fest.</summary>
        <value>Der Benutzername des Authentifizierung für die Verbindung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt.</summary>
        <value>Die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt. Der Standardwert ist eine Minute.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimePort">
      <MemberSignature Language="C#" Value="public int RuntimePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RuntimePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimePort As Integer" />
      <MemberSignature Language="F#" Value="member this.RuntimePort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die TCP-Portnummer für Common Language Runtime-Vorgang.</summary>
        <value>Die Common Language Runtime-Port.</value>
        <remarks>Dies ist nur in Serverszenario verwendet werden. Wenn die Verbindungszeichenfolge für Azure-Dienst zu generieren, sollte dies auf ihrem Standardwert bleiben;.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den SAS-Schlüssel für die Verbindungsauthentifizierung fest.</summary>
        <value>Der SAS-Schlüssel für die Verbindungsauthentifizierung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen des SAS-Schlüssels.</summary>
        <value>Der Name des SAS-Schlüssels.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerName">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerName As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den freigegebenen geheimen Ausstellernamen.</summary>
        <value>Der Ausstellername des freigegebenen geheimen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerSecret">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den freigegebenen geheimen Ausstellerschlüssel.</summary>
        <value>Die freigegebenen geheimen Ausstellerschlüssel.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; StsEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; StsEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StsEndpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.StsEndpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Satz von STS-Endpunkten.</summary>
        <value>Ein Satz von STS-Endpunkten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.</summary>
        <returns>Eine Zeichenfolge, die das aktuelle Objekt darstellt.</returns>
        <remarks>To be added.</remarks>
        <code>
                Der folgende Code gibt es ein vorhandenes / / Connection string, ändern Sie den Transporttyp zur Verwendung von Amqp, / / und die neue Verbindungszeichenfolge in der Zeichenfolge Formular Var Bulider zurückgeben = neue ServiceBusConnectionStringBuilder(connectionString); Bulider. TransportType = TransportType.Amqp; Console.WriteLine (Bulider. ToString());
                </code>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialDomain">
      <MemberSignature Language="C#" Value="public string WindowsCredentialDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialDomain As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Domäne der Windows-Anmeldeinformationen.</summary>
        <value>Die Domäne des Windows-Anmeldeinformationen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString WindowsCredentialPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString WindowsCredentialPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Kennwort des Windows-Anmeldeinformationen fest.</summary>
        <value>Das Kennwort für den Windows-Anmeldeinformationen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialUsername">
      <MemberSignature Language="C#" Value="public string WindowsCredentialUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialUsername As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Benutzernamen des Windows-Anmeldeinformationen fest.</summary>
        <value>Der Benutzername des Windows-Anmeldeinformationen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>