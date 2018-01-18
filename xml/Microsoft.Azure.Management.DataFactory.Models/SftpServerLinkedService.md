<Type Name="SftpServerLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService">
  <TypeSignature Language="C#" Value="public class SftpServerLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SftpServerLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SftpServerLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SftpServerLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Sftp")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="14ccc-101">Einen verknüpften Dienst für einen SSH File Transfer Protocol (SFTP)-Server.</span><span class="sxs-lookup"><span data-stu-id="14ccc-101">A linked service for an SSH File Transfer Protocol (SFTP) server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpServerLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.#ctor" />
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
            <span data-ttu-id="14ccc-102">Initialisiert eine neue Instanz der SftpServerLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14ccc-102">Initializes a new instance of the SftpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpServerLinkedService (object host, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object port = null, string authenticationType = null, object userName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString password = null, object encryptedCredential = null, object privateKeyPath = null, Microsoft.Azure.Management.DataFactory.Models.SecureString privateKeyContent = null, Microsoft.Azure.Management.DataFactory.Models.SecureString passPhrase = null, object skipHostKeyValidation = null, object hostKeyFingerprint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object port, string authenticationType, object userName, class Microsoft.Azure.Management.DataFactory.Models.SecureString password, object encryptedCredential, object privateKeyPath, class Microsoft.Azure.Management.DataFactory.Models.SecureString privateKeyContent, class Microsoft.Azure.Management.DataFactory.Models.SecureString passPhrase, object skipHostKeyValidation, object hostKeyFingerprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional port As Object = null, Optional authenticationType As String = null, Optional userName As Object = null, Optional password As SecureString = null, Optional encryptedCredential As Object = null, Optional privateKeyPath As Object = null, Optional privateKeyContent As SecureString = null, Optional passPhrase As SecureString = null, Optional skipHostKeyValidation As Object = null, Optional hostKeyFingerprint As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService (host, additionalProperties, connectVia, description, port, authenticationType, userName, password, encryptedCredential, privateKeyPath, privateKeyContent, passPhrase, skipHostKeyValidation, hostKeyFingerprint)" />
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
        <Parameter Name="privateKeyPath" Type="System.Object" />
        <Parameter Name="privateKeyContent" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="passPhrase" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="skipHostKeyValidation" Type="System.Object" />
        <Parameter Name="hostKeyFingerprint" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host"><span data-ttu-id="14ccc-103">Der Hostname der SFTP-Server.</span><span class="sxs-lookup"><span data-stu-id="14ccc-103">The SFTP server host name.</span></span> <span data-ttu-id="14ccc-104">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="14ccc-105">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="14ccc-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="14ccc-106">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="14ccc-106">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="14ccc-107">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="14ccc-107">Linked service description.</span></span></param>
        <param name="port"><span data-ttu-id="14ccc-108">Der TCP-Portnummer, die der SFTP-Server verwendet, um für Verbindungen mit Clients zu lauschen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-108">The TCP port number that the SFTP server uses to listen for client connections.</span></span> <span data-ttu-id="14ccc-109">Standardwert ist 22.</span><span class="sxs-lookup"><span data-stu-id="14ccc-109">Default value is 22.</span></span> <span data-ttu-id="14ccc-110">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="14ccc-110">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="authenticationType"><span data-ttu-id="14ccc-111">Der Authentifizierungstyp für die Verbindung mit dem FTP-Server verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-111">The authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="14ccc-112">Folgende Werte sind möglich: "Basic", "SshPublicKey"</span><span class="sxs-lookup"><span data-stu-id="14ccc-112">Possible values include: 'Basic', 'SshPublicKey'</span></span></param>
        <param name="userName"><span data-ttu-id="14ccc-113">Den Benutzernamen zur Anmeldung auf des SFTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="14ccc-113">The username used to log on to the SFTP server.</span></span> <span data-ttu-id="14ccc-114">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="14ccc-115">Kennwort zum Anmelden der SFTP-Server für die Standardauthentifizierung.</span><span class="sxs-lookup"><span data-stu-id="14ccc-115">Password to logon the SFTP server for Basic authentication.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="14ccc-116">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="14ccc-116">The encrypted credential used for authentication.</span></span> <span data-ttu-id="14ccc-117">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="14ccc-117">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="14ccc-118">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="privateKeyPath"><span data-ttu-id="14ccc-119">Der SSH-Privatschlüsseldatei Pfad für die SshPublicKey Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="14ccc-119">The SSH private key file path for SshPublicKey authentication.</span></span> <span data-ttu-id="14ccc-120">Nur gültig für die lokale Kopie.</span><span class="sxs-lookup"><span data-stu-id="14ccc-120">Only valid for on-premises copy.</span></span> <span data-ttu-id="14ccc-121">Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-121">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span> <span data-ttu-id="14ccc-122">Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-122">SSH private key should be OpenSSH format.</span></span> <span data-ttu-id="14ccc-123">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-123">Type: string (or Expression with resultType string).</span></span></param>
        <param name="privateKeyContent"><span data-ttu-id="14ccc-124">Base64-codierte SSH-private Key-Inhalte für die Authentifizierung SshPublicKey.</span><span class="sxs-lookup"><span data-stu-id="14ccc-124">Base64 encoded SSH private key content for SshPublicKey authentication.</span></span> <span data-ttu-id="14ccc-125">Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-125">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span> <span data-ttu-id="14ccc-126">Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-126">SSH private key should be OpenSSH format.</span></span></param>
        <param name="passPhrase"><span data-ttu-id="14ccc-127">Das Kennwort für die private SSH-Schlüssel zu entschlüsseln, wenn der private SSH-Schlüssel verschlüsselt wird.</span><span class="sxs-lookup"><span data-stu-id="14ccc-127">The password to decrypt the SSH private key if the SSH private key is encrypted.</span></span></param>
        <param name="skipHostKeyValidation"><span data-ttu-id="14ccc-128">Bei "true", überspringen Sie die SSH-Host-Key-Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="14ccc-128">If true, skip the SSH host key validation.</span></span> <span data-ttu-id="14ccc-129">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="14ccc-129">Default value is false.</span></span> <span data-ttu-id="14ccc-130">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="14ccc-130">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="hostKeyFingerprint"><span data-ttu-id="14ccc-131">Der Host-Taste Fingerabdruck des SFTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="14ccc-131">The host key finger-print of the SFTP server.</span></span> <span data-ttu-id="14ccc-132">Wenn SkipHostKeyValidation auf "false" festgelegt ist, sollte die HostKeyFingerprint angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-132">When SkipHostKeyValidation is false, HostKeyFingerprint should be specified.</span></span> <span data-ttu-id="14ccc-133">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-133">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="14ccc-134">Initialisiert eine neue Instanz der SftpServerLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14ccc-134">Initializes a new instance of the SftpServerLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.AuthenticationType" />
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
            <span data-ttu-id="14ccc-135">Ruft ab oder legt den Authentifizierungstyp an, für die Verbindung mit dem FTP-Server verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-135">Gets or sets the authentication type to be used to connect to the FTP server.</span></span> <span data-ttu-id="14ccc-136">Folgende Werte sind möglich: "Basic", "SshPublicKey"</span><span class="sxs-lookup"><span data-stu-id="14ccc-136">Possible values include: 'Basic', 'SshPublicKey'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="14ccc-137">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="14ccc-137">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="14ccc-138">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="14ccc-138">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="14ccc-139">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-139">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public object Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Host" />
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
            <span data-ttu-id="14ccc-140">Ruft ab oder legt den Hostnamen des SFTP-Server fest.</span><span class="sxs-lookup"><span data-stu-id="14ccc-140">Gets or sets the SFTP server host name.</span></span> <span data-ttu-id="14ccc-141">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-141">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostKeyFingerprint">
      <MemberSignature Language="C#" Value="public object HostKeyFingerprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HostKeyFingerprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.HostKeyFingerprint" />
      <MemberSignature Language="VB.NET" Value="Public Property HostKeyFingerprint As Object" />
      <MemberSignature Language="F#" Value="member this.HostKeyFingerprint : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.HostKeyFingerprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hostKeyFingerprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14ccc-142">Abrufen oder Festlegen der Host Key-Fingerabdruck des SFTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="14ccc-142">Gets or sets the host key finger-print of the SFTP server.</span></span> <span data-ttu-id="14ccc-143">Wenn SkipHostKeyValidation auf "false" festgelegt ist, sollte die HostKeyFingerprint angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-143">When SkipHostKeyValidation is false, HostKeyFingerprint should be specified.</span></span> <span data-ttu-id="14ccc-144">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-144">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassPhrase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString PassPhrase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString PassPhrase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PassPhrase" />
      <MemberSignature Language="VB.NET" Value="Public Property PassPhrase As SecureString" />
      <MemberSignature Language="F#" Value="member this.PassPhrase : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PassPhrase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.passPhrase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14ccc-145">Ruft ab oder legt das Kennwort fest, den privaten SSH-Schlüssel zu entschlüsseln, wenn der private SSH-Schlüssel verschlüsselt wird.</span><span class="sxs-lookup"><span data-stu-id="14ccc-145">Gets or sets the password to decrypt the SSH private key if the SSH private key is encrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Password" />
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
            <span data-ttu-id="14ccc-146">Ruft ab oder legt das Kennwort für die Standardauthentifizierung auf die SFTP-Server anmelden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-146">Gets or sets password to logon the SFTP server for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Port" />
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
            <span data-ttu-id="14ccc-147">Ruft ab, oder legt ihn fest die TCP-Portnummer, die der SFTP-Server verwendet, um für Verbindungen mit Clients zu lauschen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-147">Gets or sets the TCP port number that the SFTP server uses to listen for client connections.</span></span> <span data-ttu-id="14ccc-148">Standardwert ist 22.</span><span class="sxs-lookup"><span data-stu-id="14ccc-148">Default value is 22.</span></span> <span data-ttu-id="14ccc-149">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="14ccc-149">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyContent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString PrivateKeyContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString PrivateKeyContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PrivateKeyContent" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyContent As SecureString" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyContent : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PrivateKeyContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.privateKeyContent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14ccc-150">Ruft ab oder legt base64-codierte SSH-privaten Schlüssel für die Authentifizierung SshPublicKey.</span><span class="sxs-lookup"><span data-stu-id="14ccc-150">Gets or sets base64 encoded SSH private key content for SshPublicKey authentication.</span></span> <span data-ttu-id="14ccc-151">Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-151">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span> <span data-ttu-id="14ccc-152">Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-152">SSH private key should be OpenSSH format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyPath">
      <MemberSignature Language="C#" Value="public object PrivateKeyPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PrivateKeyPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PrivateKeyPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyPath As Object" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.PrivateKeyPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.privateKeyPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14ccc-153">Ruft ab, oder legt den SSH-Privatschlüsseldatei-Pfad für die Authentifizierung SshPublicKey.</span><span class="sxs-lookup"><span data-stu-id="14ccc-153">Gets or sets the SSH private key file path for SshPublicKey authentication.</span></span> <span data-ttu-id="14ccc-154">Nur gültig für die lokale Kopie.</span><span class="sxs-lookup"><span data-stu-id="14ccc-154">Only valid for on-premises copy.</span></span> <span data-ttu-id="14ccc-155">Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="14ccc-155">For on-premises copy with SshPublicKey authentication, either PrivateKeyPath or PrivateKeyContent should be specified.</span></span> <span data-ttu-id="14ccc-156">Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.</span><span class="sxs-lookup"><span data-stu-id="14ccc-156">SSH private key should be OpenSSH format.</span></span> <span data-ttu-id="14ccc-157">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-157">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipHostKeyValidation">
      <MemberSignature Language="C#" Value="public object SkipHostKeyValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SkipHostKeyValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.SkipHostKeyValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHostKeyValidation As Object" />
      <MemberSignature Language="F#" Value="member this.SkipHostKeyValidation : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.SkipHostKeyValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.skipHostKeyValidation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14ccc-158">Ruft ab oder legt fest, ob "true", überspringen die SSH-Host-Key-Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="14ccc-158">Gets or sets if true, skip the SSH host key validation.</span></span> <span data-ttu-id="14ccc-159">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="14ccc-159">Default value is false.</span></span> <span data-ttu-id="14ccc-160">Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</span><span class="sxs-lookup"><span data-stu-id="14ccc-160">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public object UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As Object" />
      <MemberSignature Language="F#" Value="member this.UserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.UserName" />
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
            <span data-ttu-id="14ccc-161">Ruft ab oder legt den Benutzernamen zur Anmeldung auf des SFTP-Servers.</span><span class="sxs-lookup"><span data-stu-id="14ccc-161">Gets or sets the username used to log on to the SFTP server.</span></span> <span data-ttu-id="14ccc-162">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="14ccc-162">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SftpServerLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sftpServerLinkedService.Validate " />
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
            <span data-ttu-id="14ccc-163">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="14ccc-163">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="14ccc-164">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="14ccc-164">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>