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
            Einen verknüpften Dienst für einen SSH File Transfer Protocol (SFTP)-Server.
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
            Initialisiert eine neue Instanz der SftpServerLinkedService-Klasse.
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
        <param name="host">Der Hostname der SFTP-Server. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="connectVia">Der Integration Common Language Runtime-Verweis.</param>
        <param name="description">Beschreibung des verknüpften Diensts.</param>
        <param name="port">Der TCP-Portnummer, die der SFTP-Server verwendet, um für Verbindungen mit Clients zu lauschen. Standardwert ist 22. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</param>
        <param name="authenticationType">Der Authentifizierungstyp für die Verbindung mit dem FTP-Server verwendet werden. Folgende Werte sind möglich: "Basic", "SshPublicKey"</param>
        <param name="userName">Den Benutzernamen zur Anmeldung auf des SFTP-Servers. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="password">Kennwort zum Anmelden der SFTP-Server für die Standardauthentifizierung.</param>
        <param name="encryptedCredential">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet. Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="privateKeyPath">Der SSH-Privatschlüsseldatei Pfad für die SshPublicKey Authentifizierung. Nur gültig für die lokale Kopie. Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden. Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="privateKeyContent">Base64-codierte SSH-private Key-Inhalte für die Authentifizierung SshPublicKey. Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden. Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.</param>
        <param name="passPhrase">Das Kennwort für die private SSH-Schlüssel zu entschlüsseln, wenn der private SSH-Schlüssel verschlüsselt wird.</param>
        <param name="skipHostKeyValidation">Bei "true", überspringen Sie die SSH-Host-Key-Überprüfung. Der Standardwert ist „false“. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).</param>
        <param name="hostKeyFingerprint">Der Host-Taste Fingerabdruck des SFTP-Servers. Wenn SkipHostKeyValidation auf "false" festgelegt ist, sollte die HostKeyFingerprint angegeben werden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der SftpServerLinkedService-Klasse.
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
            Ruft ab oder legt den Authentifizierungstyp an, für die Verbindung mit dem FTP-Server verwendet werden. Folgende Werte sind möglich: "Basic", "SshPublicKey"
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
            Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.
            Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab oder legt den Hostnamen des SFTP-Server fest. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Abrufen oder Festlegen der Host Key-Fingerabdruck des SFTP-Servers. Wenn SkipHostKeyValidation auf "false" festgelegt ist, sollte die HostKeyFingerprint angegeben werden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab oder legt das Kennwort fest, den privaten SSH-Schlüssel zu entschlüsseln, wenn der private SSH-Schlüssel verschlüsselt wird.
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
            Ruft ab oder legt das Kennwort für die Standardauthentifizierung auf die SFTP-Server anmelden.
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
            Ruft ab, oder legt ihn fest die TCP-Portnummer, die der SFTP-Server verwendet, um für Verbindungen mit Clients zu lauschen. Standardwert ist 22. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.
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
            Ruft ab oder legt base64-codierte SSH-privaten Schlüssel für die Authentifizierung SshPublicKey. Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden. Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.
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
            Ruft ab, oder legt den SSH-Privatschlüsseldatei-Pfad für die Authentifizierung SshPublicKey. Nur gültig für die lokale Kopie. Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden. Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Ruft ab oder legt fest, ob "true", überspringen die SSH-Host-Key-Überprüfung. Der Standardwert ist „false“. Typ: Boolesch (oder einen Ausdruck mit ResultType boolean).
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
            Ruft ab oder legt den Benutzernamen zur Anmeldung auf des SFTP-Servers. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>