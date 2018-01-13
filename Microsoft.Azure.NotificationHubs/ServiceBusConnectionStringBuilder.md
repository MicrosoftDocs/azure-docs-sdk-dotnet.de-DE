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
    <summary><span data-ttu-id="00c42-101">Bietet eine einfache Möglichkeit zum Erstellen und verwalten den Inhalt von Verbindungszeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="00c42-101">Provides a simple way to create and manage the contents of connection strings.</span></span> <span data-ttu-id="00c42-102">Sie können diese Klasse verwenden, um eine Verbindungszeichenfolge für das Erstellen von Client-messaging-Entitäten zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="00c42-102">You can use this class to construct a connection string for creating client messaging entities.</span></span> <span data-ttu-id="00c42-103">Sie können auch die grundlegende Validierung auf eine vorhandene Verbindungszeichenfolge verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="00c42-103">It can also be used to perform basic validation on an existing connection string.</span></span></summary>
    <remarks>To be added.</remarks>
    <code>
                <span data-ttu-id="00c42-104">Der folgende Code gibt es ein vorhandenes / / Connection string, ändern Sie den Transporttyp zur Verwendung von Amqp, / / und die neue Verbindungszeichenfolge in der Zeichenfolge Formular Var Bulider zurückgeben = neue ServiceBusConnectionStringBuilder(connectionString); Bulider. TransportType = TransportType.Amqp; Console.WriteLine (Bulider. ToString());</span><span class="sxs-lookup"><span data-stu-id="00c42-104">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
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
        <summary><span data-ttu-id="00c42-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00c42-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> class.</span></span></summary>
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
        <param name="connectionString"><span data-ttu-id="00c42-106">Die Verbindungszeichenfolge, die Sie aus dem Azure-Verwaltungsportal erhalten können.</span><span class="sxs-lookup"><span data-stu-id="00c42-106">The connection string, which you can obtain from the Azure Management Portal.</span></span></param>
        <summary><span data-ttu-id="00c42-107">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> Klasse mit einer angegebenen vorhandenen Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="00c42-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> class with a specified existing connection string.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException"><span data-ttu-id="00c42-108">Löst aus, wenn die Verbindungszeichenfolge der Endpunkte nicht vorhanden ist. Die Verbindungszeichenfolge besitzt nicht genügend Informationen, um einen Tokenanbieter bilden.</span><span class="sxs-lookup"><span data-stu-id="00c42-108">Throws if The connection string is missing endpoints.The connection string does not have enough information to form a token provider.</span></span> <span data-ttu-id="00c42-109">Dies kann z. B. der Fall sein, wenn Sie eine SasIssuer-Namen, aber kein SasIssuer Schlüssel angegeben. Die <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" /> Wert ist nicht in einen gültigen <see cref="T:System.TimeSpan" /> Format. Die <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" /> oder <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" /> Werte sind nicht in einem Integer-Format.</span><span class="sxs-lookup"><span data-stu-id="00c42-109">For example, this can happen if you supplied a SasIssuer name but not a SasIssuer key.The <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" /> value is not in a valid <see cref="T:System.TimeSpan" /> format.The <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" /> or <see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" /> values are not in an integer format.</span></span></exception>
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
        <param name="endpoints"><span data-ttu-id="00c42-110">Die Gruppe von Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-110">The set of endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="00c42-111">Der Satz von token Dienstendpunkte Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="00c42-111">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="00c42-112">Die Common Language Runtime-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-112">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="00c42-113">Der Management-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-113">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="00c42-114">Die Domäne, in dem die Verbindung hergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="00c42-114">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="00c42-115">Die Authentication-Benutzer.</span><span class="sxs-lookup"><span data-stu-id="00c42-115">The authentication user.</span></span></param>
        <param name="password"><span data-ttu-id="00c42-116">Das Authentifizierungskennwort.</span><span class="sxs-lookup"><span data-stu-id="00c42-116">The authentication password.</span></span></param>
        <summary><span data-ttu-id="00c42-117">Erstellt eine Verbindungszeichenfolge mit Anmeldeinformationen für die Authentifizierung an.</span><span class="sxs-lookup"><span data-stu-id="00c42-117">Creates a connection string using authentication credentials.</span></span></summary>
        <returns><span data-ttu-id="00c42-118">Die erstellte Servicebus-Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="00c42-118">The created service bus connection string.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="00c42-119">Endpunkte oder Benutzer oder Kennwort</span><span class="sxs-lookup"><span data-stu-id="00c42-119">endpoints or user or password</span></span>
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
        <param name="endpoint"><span data-ttu-id="00c42-120">Der Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="00c42-120">The endpoint.</span></span></param>
        <param name="keyName"><span data-ttu-id="00c42-121">Der Name des SAS-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="00c42-121">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="00c42-122">Der SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-122">The shared access key.</span></span></param>
        <summary><span data-ttu-id="00c42-123">Erstellen Sie eine Verbindungszeichenfolge mit dem SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-123">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="00c42-124">Die erstellte Verbindung mit dem SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-124">The created connection using the shared access key.</span></span></returns>
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
        <param name="endpoints"><span data-ttu-id="00c42-125">Die Gruppe von Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-125">The set of endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="00c42-126">Die Common Language Runtime-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-126">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="00c42-127">Der Management-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-127">The management port.</span></span></param>
        <param name="keyName"><span data-ttu-id="00c42-128">Der Name des SAS-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="00c42-128">The name of the shared access key.</span></span></param>
        <param name="key"><span data-ttu-id="00c42-129">Der SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="00c42-129">The shared access key</span></span></param>
        <summary><span data-ttu-id="00c42-130">Erstellen Sie eine Verbindungszeichenfolge mit dem SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-130">Create a connection string using the shared access key.</span></span></summary>
        <returns><span data-ttu-id="00c42-131">Die erstellte Verbindung mit dem SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-131">The created connection using the shared access key.</span></span></returns>
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
        <param name="endpoint"><span data-ttu-id="00c42-132">Der Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="00c42-132">The endpoint.</span></span></param>
        <param name="issuer"><span data-ttu-id="00c42-133">Der Aussteller</span><span class="sxs-lookup"><span data-stu-id="00c42-133">The issuer</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="00c42-134">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-134">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="00c42-135">Erstellt eine Verbindungszeichenfolge mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="00c42-135">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="00c42-136">Die erstellte Verbindung mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-136">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="00c42-137">Endpunkt "oder" Issuer "oder" issuerSecret</span><span class="sxs-lookup"><span data-stu-id="00c42-137">endpoint or issuer or issuerSecret</span></span>
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
        <param name="endpoints"><span data-ttu-id="00c42-138">Die Endpunkte.</span><span class="sxs-lookup"><span data-stu-id="00c42-138">The endpoints.</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="00c42-139">Der Satz von token Dienstendpunkte Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="00c42-139">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="00c42-140">Die Common Language Runtime-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-140">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="00c42-141">Der Management-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-141">The management port.</span></span></param>
        <param name="issuer"><span data-ttu-id="00c42-142">Der Aussteller.</span><span class="sxs-lookup"><span data-stu-id="00c42-142">The issuer.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="00c42-143">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-143">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="00c42-144">Erstellt eine Verbindungszeichenfolge mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="00c42-144">Creates a connection string using the shared secret credentials.</span></span></summary>
        <returns><span data-ttu-id="00c42-145">Die erstellte Verbindung mit den freigegebenen geheimen Schlüssel gehörenden Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-145">The created connection using the shared secret credentials.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="00c42-146">Endpunkte oder Aussteller oder issuerSecret</span><span class="sxs-lookup"><span data-stu-id="00c42-146">endpoints or issuer or issuerSecret</span></span>
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
        <param name="endpoints"><span data-ttu-id="00c42-147">Die Gruppe von Endpunkten</span><span class="sxs-lookup"><span data-stu-id="00c42-147">The set of endpoints</span></span></param>
        <param name="stsEndpoints"><span data-ttu-id="00c42-148">Der Satz von token Dienstendpunkte Sicherheit.</span><span class="sxs-lookup"><span data-stu-id="00c42-148">The set of security token service endpoints.</span></span></param>
        <param name="runtimePort"><span data-ttu-id="00c42-149">Die Common Language Runtime-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-149">The runtime port.</span></span></param>
        <param name="managementPort"><span data-ttu-id="00c42-150">Der Management-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-150">The management port.</span></span></param>
        <param name="domain"><span data-ttu-id="00c42-151">Die Domäne, in dem die Verbindung hergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="00c42-151">The domain where the connection will be established.</span></span></param>
        <param name="user"><span data-ttu-id="00c42-152">Der Benutzer.</span><span class="sxs-lookup"><span data-stu-id="00c42-152">The user.</span></span></param>
        <param name="password"><span data-ttu-id="00c42-153">Das Windows-Kennwort.</span><span class="sxs-lookup"><span data-stu-id="00c42-153">The windows password.</span></span></param>
        <summary><span data-ttu-id="00c42-154">Erstellt eine Verbindungszeichenfolge, die mit Windows-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="00c42-154">Creates a connection string using Windows credentials.</span></span></summary>
        <returns><span data-ttu-id="00c42-155">Die erstellte Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="00c42-155">The created connection string.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="00c42-156">Endpunkte oder Benutzer oder Kennwort</span><span class="sxs-lookup"><span data-stu-id="00c42-156">endpoints or user or password</span></span>
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
        <summary><span data-ttu-id="00c42-157">Ruft eine Auflistung von Dienstendpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-157">Gets a collection of service endpoints.</span></span> <span data-ttu-id="00c42-158">Jeder Endpunkt muss es sich um dieselbe Service Bus-Namespace verweisen.</span><span class="sxs-lookup"><span data-stu-id="00c42-158">Each endpoint must reference the same Service Bus namespace.</span></span></summary>
        <value><span data-ttu-id="00c42-159">Eine Sammlung von Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-159">A set of endpoints.</span></span></value>
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
        <summary><span data-ttu-id="00c42-160">Ruft die absolute verwaltungsendpunkte ab.</span><span class="sxs-lookup"><span data-stu-id="00c42-160">Retrieves the absolute management endpoints.</span></span></summary>
        <returns><span data-ttu-id="00c42-161">Der absolute-Endpunkte</span><span class="sxs-lookup"><span data-stu-id="00c42-161">The absolute management endpoints</span></span></returns>
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
        <summary><span data-ttu-id="00c42-162">Ruft die absolute Runtime Endpunkte ab.</span><span class="sxs-lookup"><span data-stu-id="00c42-162">Retrieves the absolute runtime endpoints.</span></span></summary>
        <returns><span data-ttu-id="00c42-163">Die absolute Common Language Runtime-Endpunkte.</span><span class="sxs-lookup"><span data-stu-id="00c42-163">The absolute runtime endpoints.</span></span></returns>
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
        <summary><span data-ttu-id="00c42-164">Ruft ab oder legt die TCP-Portnummer für Verwaltungsvorgänge.</span><span class="sxs-lookup"><span data-stu-id="00c42-164">Gets or sets the TCP port number for management operations.</span></span></summary>
        <value><span data-ttu-id="00c42-165">Der Management-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-165">The management port.</span></span></value>
        <remarks><span data-ttu-id="00c42-166">Dies ist nur in Serverszenario verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="00c42-166">This is only used in server scenario.</span></span> <span data-ttu-id="00c42-167">Wenn die Verbindungszeichenfolge für Azure-Dienst zu generieren, sollte dies auf ihrem Standardwert bleiben;.</span><span class="sxs-lookup"><span data-stu-id="00c42-167">When generating connection string for azure service, this should be left at its default value;.</span></span></remarks>
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
        <summary><span data-ttu-id="00c42-168">Ruft ab oder legt die Authentifizierungsdomäne für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="00c42-168">Gets or sets the authentication domain for the connection.</span></span></summary>
        <value><span data-ttu-id="00c42-169">Die Authentifizierungsdomäne für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="00c42-169">The authentication domain for the connection.</span></span></value>
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
        <summary><span data-ttu-id="00c42-170">Ruft ab oder legt das Authentifizierungskennwort für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="00c42-170">Gets or sets the authentication password for the connection.</span></span></summary>
        <value><span data-ttu-id="00c42-171">Das Authentifizierungskennwort für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="00c42-171">The authentication password for the connection.</span></span></value>
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
        <summary><span data-ttu-id="00c42-172">Ruft ab oder legt den Benutzernamen der Authentifizierung für die Verbindung fest.</span><span class="sxs-lookup"><span data-stu-id="00c42-172">Gets or sets the authentication user name for the connection.</span></span></summary>
        <value><span data-ttu-id="00c42-173">Der Benutzername des Authentifizierung für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="00c42-173">The authentication user name for the connection.</span></span></value>
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
        <summary><span data-ttu-id="00c42-174">Ruft ab oder legt die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="00c42-174">Gets or sets the <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out.</span></span></summary>
        <value><span data-ttu-id="00c42-175">Die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt. Der Standardwert ist eine Minute.</span><span class="sxs-lookup"><span data-stu-id="00c42-175">The <see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out. The default value is one minute.</span></span></value>
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
        <summary><span data-ttu-id="00c42-176">Ruft ab oder legt die TCP-Portnummer für Common Language Runtime-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="00c42-176">Gets or sets the TCP port number for runtime operation.</span></span></summary>
        <value><span data-ttu-id="00c42-177">Die Common Language Runtime-Port.</span><span class="sxs-lookup"><span data-stu-id="00c42-177">The runtime port.</span></span></value>
        <remarks><span data-ttu-id="00c42-178">Dies ist nur in Serverszenario verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="00c42-178">This is only used in server scenario.</span></span> <span data-ttu-id="00c42-179">Wenn die Verbindungszeichenfolge für Azure-Dienst zu generieren, sollte dies auf ihrem Standardwert bleiben;.</span><span class="sxs-lookup"><span data-stu-id="00c42-179">When generating connection string for azure service, this should be left at its default value;.</span></span></remarks>
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
        <summary><span data-ttu-id="00c42-180">Ruft ab oder legt den SAS-Schlüssel für die Verbindungsauthentifizierung fest.</span><span class="sxs-lookup"><span data-stu-id="00c42-180">Gets or sets the shared access key for the connection authentication.</span></span></summary>
        <value><span data-ttu-id="00c42-181">Der SAS-Schlüssel für die Verbindungsauthentifizierung.</span><span class="sxs-lookup"><span data-stu-id="00c42-181">The shared access key for the connection authentication.</span></span></value>
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
        <summary><span data-ttu-id="00c42-182">Ruft ab oder legt den Namen des SAS-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="00c42-182">Gets or sets the name of the shared access key.</span></span></summary>
        <value><span data-ttu-id="00c42-183">Der Name des SAS-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="00c42-183">The name of the shared access key.</span></span></value>
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
        <summary><span data-ttu-id="00c42-184">Ruft ab oder legt den freigegebenen geheimen Ausstellernamen.</span><span class="sxs-lookup"><span data-stu-id="00c42-184">Gets or sets the shared secret issuer name.</span></span></summary>
        <value><span data-ttu-id="00c42-185">Der Ausstellername des freigegebenen geheimen.</span><span class="sxs-lookup"><span data-stu-id="00c42-185">The shared secret issuer name.</span></span></value>
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
        <summary><span data-ttu-id="00c42-186">Ruft ab oder legt den freigegebenen geheimen Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-186">Gets or sets the shared secret issuer secret.</span></span></summary>
        <value><span data-ttu-id="00c42-187">Die freigegebenen geheimen Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="00c42-187">The shared secret issuer secret.</span></span></value>
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
        <summary><span data-ttu-id="00c42-188">Ruft einen Satz von STS-Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-188">Gets a set of STS endpoints.</span></span></summary>
        <value><span data-ttu-id="00c42-189">Ein Satz von STS-Endpunkten.</span><span class="sxs-lookup"><span data-stu-id="00c42-189">A set of STS endpoints.</span></span></value>
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
        <summary><span data-ttu-id="00c42-190">Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt.</span><span class="sxs-lookup"><span data-stu-id="00c42-190">Returns a string that represents the current object.</span></span></summary>
        <returns><span data-ttu-id="00c42-191">Eine Zeichenfolge, die das aktuelle Objekt darstellt.</span><span class="sxs-lookup"><span data-stu-id="00c42-191">A string that represents the current object.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="00c42-192">Der folgende Code gibt es ein vorhandenes / / Connection string, ändern Sie den Transporttyp zur Verwendung von Amqp, / / und die neue Verbindungszeichenfolge in der Zeichenfolge Formular Var Bulider zurückgeben = neue ServiceBusConnectionStringBuilder(connectionString); Bulider. TransportType = TransportType.Amqp; Console.WriteLine (Bulider. ToString());</span><span class="sxs-lookup"><span data-stu-id="00c42-192">// The following sample code takes an existing // connection string, change the transport type to use Amqp, // and return the new connection string in string form var bulider = new ServiceBusConnectionStringBuilder(connectionString); bulider.TransportType = TransportType.Amqp; Console.WriteLine(bulider.ToString());</span></span>
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
        <summary><span data-ttu-id="00c42-193">Ruft ab oder legt die Domäne der Windows-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-193">Gets or sets the Windows credential domain.</span></span></summary>
        <value><span data-ttu-id="00c42-194">Die Domäne des Windows-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-194">The Windows credential domain.</span></span></value>
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
        <summary><span data-ttu-id="00c42-195">Ruft ab oder legt das Kennwort des Windows-Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="00c42-195">Gets or sets the Windows credential password.</span></span></summary>
        <value><span data-ttu-id="00c42-196">Das Kennwort für den Windows-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-196">The Windows credential password.</span></span></value>
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
        <summary><span data-ttu-id="00c42-197">Ruft ab oder legt den Benutzernamen des Windows-Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="00c42-197">Gets or sets the Windows credential user name.</span></span></summary>
        <value><span data-ttu-id="00c42-198">Der Benutzername des Windows-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="00c42-198">The Windows credential user name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>