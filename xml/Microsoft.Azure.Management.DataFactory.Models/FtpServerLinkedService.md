<Type Name="FtpServerLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService">
  <TypeSignature Language="C#" Value="public class FtpServerLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FtpServerLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class FtpServerLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type FtpServerLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
      <AttributeName>Newtonsoft.Json.JsonObject("FtpServer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3d162-101">Ein FTP-Server des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="3d162-101">A FTP server Linked Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FtpServerLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3d162-102">Initialisiert eine neue Instanz der FtpServerLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d162-102">Initializes a new instance of the FtpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FtpServerLinkedService (object host, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, string authenticationType = null, object userName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null, object enableSsl = null, object enableServerCertificateValidation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, string authenticationType, object userName, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential, object enableSsl, object enableServerCertificateValidation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional authenticationType As String = null, Optional userName As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null, Optional enableSsl As Object = null, Optional enableServerCertificateValidation As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService (host, additionalProperties, connectVia, description, port, authenticationType, userName, password, encryptedCredential, enableSsl, enableServerCertificateValidation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="userName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="enableServerCertificateValidation" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="3d162-103">Der Hostname des FTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="3d162-103">Host name of the FTP server.</span></span> <span data-ttu-id="3d162-104">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="3d162-105">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="3d162-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="3d162-106">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="3d162-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="3d162-107">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="3d162-107">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="3d162-108">Der TCP-Portnummer, die der FTP-Server verwendet, um für Verbindungen mit Clients zu lauschen.</span><span class="sxs-lookup"><span data-stu-id="3d162-108">The TCP port number that the FTP server uses to listen for client connections.</span></span> <span data-ttu-id="3d162-109">Standardwert ist 21.</span><span class="sxs-lookup"><span data-stu-id="3d162-109">Default value is 21.</span></span> <span data-ttu-id="3d162-110">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="3d162-110">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="3d162-111">Der Authentifizierungstyp für die Verbindung mit dem FTP-Server verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d162-111">The authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="3d162-112">Folgende Werte sind möglich: "Basic", "Anonymous"</span><span class="sxs-lookup"><span data-stu-id="3d162-112">Possible values include: 'Basic', 'Anonymous'</span></span></param>
        <param name="userName"><span data-ttu-id="3d162-113">Der Benutzername, der FTP-Server anmelden.</span><span class="sxs-lookup"><span data-stu-id="3d162-113">Username to logon the FTP server.</span></span> <span data-ttu-id="3d162-114">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="3d162-115">Kennwort für den FTP-Server anmelden.</span><span class="sxs-lookup"><span data-stu-id="3d162-115">Password to logon the FTP server.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="3d162-116">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="3d162-116">The encrypted credential used for authentication.</span></span> <span data-ttu-id="3d162-117">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="3d162-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="3d162-118">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="enableSsl"><span data-ttu-id="3d162-119">Bei "true", verbinden Sie mit dem FTP-Server über SSL/TLS-Kanal.</span><span class="sxs-lookup"><span data-stu-id="3d162-119">If true, connect to the FTP server over SSL/TLS channel.</span></span> <span data-ttu-id="3d162-120">Standardwert ist "true".</span><span class="sxs-lookup"><span data-stu-id="3d162-120">Default value is true.</span></span> <span data-ttu-id="3d162-121">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="3d162-121">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="enableServerCertificateValidation"><span data-ttu-id="3d162-122">Überprüfen Sie das FTP-Server SSL-Zertifikat, bei "true", wenn die Verbindung über SSL/TLS-Kanal.</span><span class="sxs-lookup"><span data-stu-id="3d162-122">If true, validate the FTP server SSL certificate when connect over SSL/TLS channel.</span></span>
            <span data-ttu-id="3d162-123">Standardwert ist "true".</span><span class="sxs-lookup"><span data-stu-id="3d162-123">Default value is true.</span></span> <span data-ttu-id="3d162-124">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="3d162-124">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="3d162-125">Initialisiert eine neue Instanz der FtpServerLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3d162-125">Initializes a new instance of the FtpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="3d162-126">Ruft ab oder legt den Authentifizierungstyp an, für die Verbindung mit dem FTP-Server verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="3d162-126">Gets or sets the authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="3d162-127">Folgende Werte sind möglich: "Basic", "Anonymous"</span><span class="sxs-lookup"><span data-stu-id="3d162-127">Possible values include: 'Basic', 'Anonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableServerCertificateValidation">
      <MemberSignature Language="C#" Value="public object EnableServerCertificateValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableServerCertificateValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableServerCertificateValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableServerCertificateValidation As Object" />
      <MemberSignature Language="F#" Value="member this.EnableServerCertificateValidation : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableServerCertificateValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.enableServerCertificateValidation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d162-128">Der FTP-Server SSL-Zertifikat zu überprüfen Ruft ab oder legt fest, ob "true", wenn die Verbindung über SSL/TLS-Kanal.</span><span class="sxs-lookup"><span data-stu-id="3d162-128">Gets or sets if true, validate the FTP server SSL certificate when connect over SSL/TLS channel.</span></span> <span data-ttu-id="3d162-129">Standardwert ist "true".</span><span class="sxs-lookup"><span data-stu-id="3d162-129">Default value is true.</span></span> <span data-ttu-id="3d162-130">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="3d162-130">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EnableSsl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="3d162-131">Ruft ab oder legt fest, ob "true" Verbinden mit dem FTP-Server über SSL/TLS-Kanal.</span><span class="sxs-lookup"><span data-stu-id="3d162-131">Gets or sets if true, connect to the FTP server over SSL/TLS channel.</span></span> <span data-ttu-id="3d162-132">Standardwert ist "true".</span><span class="sxs-lookup"><span data-stu-id="3d162-132">Default value is true.</span></span> <span data-ttu-id="3d162-133">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="3d162-133">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="3d162-134">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="3d162-134">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="3d162-135">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="3d162-135">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="3d162-136">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-136">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="3d162-137">Ruft ab, oder legt ihn fest Hostnamen des FTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="3d162-137">Gets or sets host name of the FTP server.</span></span> <span data-ttu-id="3d162-138">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-138">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d162-139">Ruft ab oder legt das Kennwort auf den FTP-Server anmelden.</span><span class="sxs-lookup"><span data-stu-id="3d162-139">Gets or sets password to logon the FTP server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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
            <span data-ttu-id="3d162-140">Ruft ab, oder legt ihn fest die TCP-Portnummer, die der FTP-Server verwendet, um für Verbindungen mit Clients zu lauschen.</span><span class="sxs-lookup"><span data-stu-id="3d162-140">Gets or sets the TCP port number that the FTP server uses to listen for client connections.</span></span> <span data-ttu-id="3d162-141">Standardwert ist 21.</span><span class="sxs-lookup"><span data-stu-id="3d162-141">Default value is 21.</span></span> <span data-ttu-id="3d162-142">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="3d162-142">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public object UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As Object" />
      <MemberSignature Language="F#" Value="member this.UserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.userName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3d162-143">Abrufen oder Festlegen der Benutzername, der den FTP-Server anmelden.</span><span class="sxs-lookup"><span data-stu-id="3d162-143">Gets or sets username to logon the FTP server.</span></span> <span data-ttu-id="3d162-144">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="3d162-144">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FtpServerLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="ftpServerLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3d162-145">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3d162-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3d162-146">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3d162-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>