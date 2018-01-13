<Type Name="SparkLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService">
  <TypeSignature Language="C#" Value="public class SparkLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SparkLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SparkLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type SparkLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Spark")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Spark verknüpfter Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SparkLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SparkLinkedService (object host, object port, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, string serverType = null, string thriftTransportProtocol = null, object username = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object httpPath = null, object enableSsl = null, object trustedCertPath = null, object useSystemTrustStore = null, object allowHostNameCNMismatch = null, object allowSelfSignedServerCert = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object host, object port, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, string serverType, string thriftTransportProtocol, object username, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object httpPath, object enableSsl, object trustedCertPath, object useSystemTrustStore, object allowHostNameCNMismatch, object allowSelfSignedServerCert, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.#ctor(System.Object,System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.String,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As Object, port As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional serverType As String = null, Optional thriftTransportProtocol As String = null, Optional username As Object = null, Optional password As SecretBase = null, Optional httpPath As Object = null, Optional enableSsl As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional allowHostNameCNMismatch As Object = null, Optional allowSelfSignedServerCert As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService : obj * obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * string * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService (host, port, authenticationType, additionalProperties, connectVia, description, serverType, thriftTransportProtocol, username, password, httpPath, enableSsl, trustedCertPath, useSystemTrustStore, allowHostNameCNMismatch, allowSelfSignedServerCert, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="serverType" Type="System.String" />
        <Parameter Name="thriftTransportProtocol" Type="System.String" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="httpPath" Type="System.Object" />
        <Parameter Name="enableSsl" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="allowHostNameCNMismatch" Type="System.Object" />
        <Parameter Name="allowSelfSignedServerCert" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="host">IP-Adresse oder Hostname des Spark-Servers</param>
        <param name="port">Der TCP-Port, den der Spark-Server verwendet, um auf Clientverbindungen zu lauschen.</param>
        <param name="authenticationType">Die Authentifizierungsmethode für den Zugriff auf den Spark-Server. Folgende Werte sind möglich: "Anonymous", "Username", "UsernameAndPassword", "WindowsAzureHDInsightService"</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="connectVia">Der Integration Common Language Runtime-Verweis.</param>
        <param name="description">Beschreibung des verknüpften Diensts.</param>
        <param name="serverType">Der Typ des Spark-Servers. Folgende Werte sind möglich: "SharkServer", "SharkServer2", "SparkThriftServer"</param>
        <param name="thriftTransportProtocol">Das auf der Thrift-Ebene zu verwendende Transportprotokoll. Folgende Werte sind möglich: "Binary", "SASL", "HTTP"</param>
        <param name="username">Der Benutzername für den Zugriff auf den Spark-Server.</param>
        <param name="password">Das Kennwort, das dem Benutzernamen entspricht, den Sie im Feld „Username“ angegeben haben.</param>
        <param name="httpPath">Die Teil-URL, die dem Spark-Server entspricht.</param>
        <param name="enableSsl">Gibt an, ob die Verbindungen mit dem Server mit SSL verschlüsselt werden. Der Standardwert ist „false“.</param>
        <param name="trustedCertPath">Der vollständige Pfad der PEM-Datei mit vertrauenswürdigen Zertifizierungsstellenzertifikaten zur Überprüfung des Servers beim Verbindungsaufbau über SSL. Diese Eigenschaft kann nur festgelegt werden, wenn SSL in einer selbstgehostetem IR verwendet wird. Der Standardwert ist die Datei „cacerts.pem“, die mit der IR installiert wird.</param>
        <param name="useSystemTrustStore">Gibt an, ob ein Zertifizierungsstellenzertifikat aus dem Vertrauensspeicher des Systems oder aus einer angegebenen PEM-Datei verwendet werden soll. Der Standardwert ist „false“.</param>
        <param name="allowHostNameCNMismatch">Gibt an, ob ein von der Zertifizierungsstelle ausgestellter SSL-Zertifikatsname erforderlich ist, der mit dem Hostnamen des Servers übereinstimmt, wenn eine Verbindung über SSL hergestellt wird. Der Standardwert ist „false“.</param>
        <param name="allowSelfSignedServerCert">Gibt an, ob vom Server selbstsignierte Zertifikate zugelassen werden. Der Standardwert ist „false“.</param>
        <param name="encryptedCredential">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet. Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der SparkLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowHostNameCNMismatch">
      <MemberSignature Language="C#" Value="public object AllowHostNameCNMismatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowHostNameCNMismatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowHostNameCNMismatch As Object" />
      <MemberSignature Language="F#" Value="member this.AllowHostNameCNMismatch : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowHostNameCNMismatch" />
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
            Gibt an, ob eine Zertifizierungsstelle ausgestelltes SSL-Zertifikatsnamen entsprechend den Hostnamen des Servers Verbindungsaufbau über SSL erforderlich ist, ruft ab oder legt ihn fest. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSelfSignedServerCert">
      <MemberSignature Language="C#" Value="public object AllowSelfSignedServerCert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AllowSelfSignedServerCert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowSelfSignedServerCert As Object" />
      <MemberSignature Language="F#" Value="member this.AllowSelfSignedServerCert : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AllowSelfSignedServerCert" />
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
            Gibt an, ob selbstsignierte Zertifikate vom Server zu ermöglichen, ruft ab oder legt ihn fest. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.AuthenticationType" />
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
            Ruft ab oder legt die Authentifizierungsmethode für den Serverzugriff Spark. Folgende Werte sind möglich: "Anonymous", "Username", "UsernameAndPassword", "WindowsAzureHDInsightService"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSsl">
      <MemberSignature Language="C#" Value="public object EnableSsl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EnableSsl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSsl As Object" />
      <MemberSignature Language="F#" Value="member this.EnableSsl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EnableSsl" />
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
            Gibt an, ob die Verbindungen mit dem Server mit SSL verschlüsselt werden, ruft ab oder legt ihn fest. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.EncryptedCredential" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As Object" />
      <MemberSignature Language="F#" Value="member this.Host : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Host" />
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
            Ruft ab oder legt die IP-Adresse oder Host-Name des Servers Spark
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPath">
      <MemberSignature Language="C#" Value="public object HttpPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HttpPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPath As Object" />
      <MemberSignature Language="F#" Value="member this.HttpPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.HttpPath" />
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
            Ruft ab oder legt die partielle URL entspricht dem Spark-Server.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Password" />
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
            Ruft ab oder legt das Kennwort für den Benutzernamen, den Sie im Feld "Benutzername" angegeben
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Port" />
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
            Ruft ab oder legt den TCP-Port, den die Spark-Server verwendet, um Clientverbindungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerType">
      <MemberSignature Language="C#" Value="public string ServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerType As String" />
      <MemberSignature Language="F#" Value="member this.ServerType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ServerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serverType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Spark-Servers. Folgende Werte sind möglich: "SharkServer", "SharkServer2", "SparkThriftServer"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThriftTransportProtocol">
      <MemberSignature Language="C#" Value="public string ThriftTransportProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThriftTransportProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property ThriftTransportProtocol As String" />
      <MemberSignature Language="F#" Value="member this.ThriftTransportProtocol : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.ThriftTransportProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.thriftTransportProtocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Transportprotokoll für die Verwendung in der Thrift-Ebene.
            Folgende Werte sind möglich: "Binary", "SASL", "HTTP"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.TrustedCertPath" />
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
            Ruft ab oder legt den vollständigen Pfad der PEM-Datei, die zum Überprüfen des Servers über SSL Verbindungsaufbau vertrauenswürdige Zertifikate der Zertifizierungsstelle enthält.
            Diese Eigenschaft kann nur festgelegt werden, wenn SSL in einer selbstgehostetem IR verwendet wird. Der Standardwert ist die Datei „cacerts.pem“, die mit der IR installiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Username" />
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
            Ruft ab oder legt den Benutzernamen, mit denen Sie den Zugriff auf Spark-Server fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.UseSystemTrustStore" />
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
            Gibt an, ob ein Zertifikat aus dem System Trust Store oder aus einer angegebenen PEM-Datei verwenden, ruft ab oder legt ihn fest. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SparkLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sparkLinkedService.Validate " />
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