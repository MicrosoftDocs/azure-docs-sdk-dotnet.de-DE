<Type Name="PhoenixLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService">
  <TypeSignature Language="C#" Value="public class PhoenixLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PhoenixLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class PhoenixLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type PhoenixLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Phoenix")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c102e-101">Phoenix verknüpfter Dienst.</span><span class="sxs-lookup"><span data-stu-id="c102e-101">Phoenix server linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoenixLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c102e-102">Initialisiert eine neue Instanz der PhoenixLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c102e-102">Initializes a new instance of the PhoenixLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoenixLinkedService (object host, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, object httpPath = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, object httpPath, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.#ctor(System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional httpPath As Object = null, Optional username As Object = null, Optional password As SecretBase = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService : obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService (host, authenticationType, additionalProperties, connectVia, description, port, httpPath, username, password, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="httpPath" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="c102e-103">IP-Adresse oder Hostname des Phoenix-Servers.</span><span class="sxs-lookup"><span data-stu-id="c102e-103">The IP address or host name of the Phoenix server.</span></span> <span data-ttu-id="c102e-104">(z.B. 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="c102e-104">(i.e. 192.168.222.160)</span></span></param>
        <param name="authenticationType"><span data-ttu-id="c102e-105">Der Authentifizierungsmechanismus, der für die Verbindung mit dem Phoenix-Server verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c102e-105">The authentication mechanism used to connect to the Phoenix server.</span></span> <span data-ttu-id="c102e-106">Folgende Werte sind möglich: "Anonymous", "UsernameAndPassword", "WindowsAzureHDInsightService"</span><span class="sxs-lookup"><span data-stu-id="c102e-106">Possible values include: 'Anonymous', 'UsernameAndPassword', 'WindowsAzureHDInsightService'</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="c102e-107">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="c102e-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="c102e-108">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="c102e-108">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="c102e-109">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="c102e-109">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="c102e-110">Der TCP-Port, den der Phoenix-Server verwendet, um auf Clientverbindungen zu lauschen.</span><span class="sxs-lookup"><span data-stu-id="c102e-110">The TCP port that the Phoenix server uses to listen for client connections.</span></span> <span data-ttu-id="c102e-111">Der Standardwert ist 8765.</span><span class="sxs-lookup"><span data-stu-id="c102e-111">The default value is 8765.</span></span></param>
        <param name="httpPath"><span data-ttu-id="c102e-112">Die Teil-URL, die dem Phoenix-Server entspricht.</span><span class="sxs-lookup"><span data-stu-id="c102e-112">The partial URL corresponding to the Phoenix server.</span></span> <span data-ttu-id="c102e-113">(d. h. /gateway/sandbox/phoenix/version).</span><span class="sxs-lookup"><span data-stu-id="c102e-113">(i.e. /gateway/sandbox/phoenix/version).</span></span> <span data-ttu-id="c102e-114">Der Standardwert ist Hbasephoenix auf, wenn WindowsAzureHDInsightService verwenden.</span><span class="sxs-lookup"><span data-stu-id="c102e-114">The default value is hbasephoenix if using WindowsAzureHDInsightService.</span></span></param>
        <param name="username"><span data-ttu-id="c102e-115">Der Benutzername, der für die Verbindung mit dem Phoenix-Server verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c102e-115">The user name used to connect to the Phoenix server.</span></span></param>
        <param name="password"><span data-ttu-id="c102e-116">Das Kennwort, das zum Benutzernamen gehört.</span><span class="sxs-lookup"><span data-stu-id="c102e-116">The password corresponding to the user name.</span></span></param>
        <param name="enableSsl"><span data-ttu-id="c102e-117">Gibt an, ob die Verbindungen mit dem Server mit SSL verschlüsselt werden.</span><span class="sxs-lookup"><span data-stu-id="c102e-117">Specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="c102e-118">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-118">The default value is false.</span></span></param>
        <param name="trustedCertPath"><span data-ttu-id="c102e-119">Der vollständige Pfad der PEM-Datei mit vertrauenswürdigen Zertifizierungsstellenzertifikaten zur Überprüfung des Servers beim Verbindungsaufbau über SSL.</span><span class="sxs-lookup"><span data-stu-id="c102e-119">The full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span> <span data-ttu-id="c102e-120">Diese Eigenschaft kann nur festgelegt werden, wenn SSL in einer selbstgehostetem IR verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c102e-120">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="c102e-121">Der Standardwert ist die Datei „cacerts.pem“, die mit der IR installiert wird.</span><span class="sxs-lookup"><span data-stu-id="c102e-121">The default value is the cacerts.pem file installed with the IR.</span></span></param>
        <param name="useSystemTrustStore"><span data-ttu-id="c102e-122">Gibt an, ob ein Zertifizierungsstellenzertifikat aus dem Vertrauensspeicher des Systems oder aus einer angegebenen PEM-Datei verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c102e-122">Specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="c102e-123">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-123">The default value is false.</span></span></param>
        <param name="allowHostNameCNMismatch"><span data-ttu-id="c102e-124">Gibt an, ob ein von der Zertifizierungsstelle ausgestellter SSL-Zertifikatsname erforderlich ist, der mit dem Hostnamen des Servers übereinstimmt, wenn eine Verbindung über SSL hergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c102e-124">Specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="c102e-125">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-125">The default value is false.</span></span></param>
        <param name="allowSelfSignedServerCert"><span data-ttu-id="c102e-126">Gibt an, ob vom Server selbstsignierte Zertifikate zugelassen werden.</span><span class="sxs-lookup"><span data-stu-id="c102e-126">Specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="c102e-127">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-127">The default value is false.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="c102e-128">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="c102e-128">The encrypted credential used for authentication.</span></span> <span data-ttu-id="c102e-129">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="c102e-129">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="c102e-130">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="c102e-130">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="c102e-131">Initialisiert eine neue Instanz der PhoenixLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c102e-131">Initializes a new instance of the PhoenixLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AllowHostNameCNMismatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowHostNameCNMismatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-132">Gibt an, ob eine Zertifizierungsstelle ausgestelltes SSL-Zertifikatsnamen entsprechend den Hostnamen des Servers Verbindungsaufbau über SSL erforderlich ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c102e-132">Gets or sets specifies whether to require a CA-issued SSL certificate name to match the host name of the server when connecting over SSL.</span></span> <span data-ttu-id="c102e-133">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-133">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AllowSelfSignedServerCert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.allowSelfSignedServerCert")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-134">Gibt an, ob selbstsignierte Zertifikate vom Server zu ermöglichen, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c102e-134">Gets or sets specifies whether to allow self-signed certificates from the server.</span></span> <span data-ttu-id="c102e-135">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-135">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-136">Ruft ab, oder legt ihn fest zur Verbindung mit dem Server Phoenix Authentifizierungsmechanismus.</span><span class="sxs-lookup"><span data-stu-id="c102e-136">Gets or sets the authentication mechanism used to connect to the Phoenix server.</span></span> <span data-ttu-id="c102e-137">Folgende Werte sind möglich: "Anonymous", "UsernameAndPassword", "WindowsAzureHDInsightService"</span><span class="sxs-lookup"><span data-stu-id="c102e-137">Possible values include: 'Anonymous', 'UsernameAndPassword', 'WindowsAzureHDInsightService'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.EnableSsl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableSsl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-138">Gibt an, ob die Verbindungen mit dem Server mit SSL verschlüsselt werden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c102e-138">Gets or sets specifies whether the connections to the server are encrypted using SSL.</span></span> <span data-ttu-id="c102e-139">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-139">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-140">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="c102e-140">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="c102e-141">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="c102e-141">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="c102e-142">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="c102e-142">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-143">Ruft ab oder legt die IP-Adresse oder den Hostnamen der Name des Servers Phoenix.</span><span class="sxs-lookup"><span data-stu-id="c102e-143">Gets or sets the IP address or host name of the Phoenix server.</span></span>
            <span data-ttu-id="c102e-144">(z.B. 192.168.222.160)</span><span class="sxs-lookup"><span data-stu-id="c102e-144">(i.e. 192.168.222.160)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.HttpPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.httpPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-145">Ruft ab, oder legt ihn fest mit dem Server Phoenix entsprechende partielle URL.</span><span class="sxs-lookup"><span data-stu-id="c102e-145">Gets or sets the partial URL corresponding to the Phoenix server.</span></span>
            <span data-ttu-id="c102e-146">(d. h. /gateway/sandbox/phoenix/version).</span><span class="sxs-lookup"><span data-stu-id="c102e-146">(i.e. /gateway/sandbox/phoenix/version).</span></span> <span data-ttu-id="c102e-147">Der Standardwert ist Hbasephoenix auf, wenn WindowsAzureHDInsightService verwenden.</span><span class="sxs-lookup"><span data-stu-id="c102e-147">The default value is hbasephoenix if using WindowsAzureHDInsightService.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-148">Ruft ab oder legt das Kennwort für den Benutzernamen fest.</span><span class="sxs-lookup"><span data-stu-id="c102e-148">Gets or sets the password corresponding to the user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-149">Ruft ab oder legt den TCP-Port, den die Phoenix-Server verwendet, um Clientverbindungen.</span><span class="sxs-lookup"><span data-stu-id="c102e-149">Gets or sets the TCP port that the Phoenix server uses to listen for client connections.</span></span> <span data-ttu-id="c102e-150">Der Standardwert ist 8765.</span><span class="sxs-lookup"><span data-stu-id="c102e-150">The default value is 8765.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.TrustedCertPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trustedCertPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-151">Ruft ab oder legt den vollständigen Pfad der PEM-Datei, die zum Überprüfen des Servers über SSL Verbindungsaufbau vertrauenswürdige Zertifikate der Zertifizierungsstelle enthält.</span><span class="sxs-lookup"><span data-stu-id="c102e-151">Gets or sets the full path of the .pem file containing trusted CA certificates for verifying the server when connecting over SSL.</span></span>
            <span data-ttu-id="c102e-152">Diese Eigenschaft kann nur festgelegt werden, wenn SSL in einer selbstgehostetem IR verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c102e-152">This property can only be set when using SSL on self-hosted IR.</span></span> <span data-ttu-id="c102e-153">Der Standardwert ist die Datei „cacerts.pem“, die mit der IR installiert wird.</span><span class="sxs-lookup"><span data-stu-id="c102e-153">The default value is the cacerts.pem file installed with the IR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-154">Ruft ab oder legt den Benutzernamen für die Verbindung mit dem Server Phoenix verwendet.</span><span class="sxs-lookup"><span data-stu-id="c102e-154">Gets or sets the user name used to connect to the Phoenix server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.UseSystemTrustStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.useSystemTrustStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c102e-155">Gibt an, ob ein Zertifikat aus dem System Trust Store oder aus einer angegebenen PEM-Datei verwenden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c102e-155">Gets or sets specifies whether to use a CA certificate from the system trust store or from a specified PEM file.</span></span> <span data-ttu-id="c102e-156">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="c102e-156">The default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PhoenixLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="phoenixLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c102e-157">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c102e-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c102e-158">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c102e-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>