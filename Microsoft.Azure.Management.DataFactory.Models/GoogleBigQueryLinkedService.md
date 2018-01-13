<Type Name="GoogleBigQueryLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService">
  <TypeSignature Language="C#" Value="public class GoogleBigQueryLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GoogleBigQueryLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class GoogleBigQueryLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type GoogleBigQueryLinkedService = class&#xA;    inherit LinkedService" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("GoogleBigQuery")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Google BigQuery Dienst verknüpften Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GoogleBigQueryLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der GoogleBigQueryLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GoogleBigQueryLinkedService (object project, string authenticationType, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object additionalProjects = null, object requestGoogleDriveScope = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken = null, object email = null, object keyFilePath = null, object trustedCertPath = null, object useSystemTrustStore = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object project, string authenticationType, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object additionalProjects, object requestGoogleDriveScope, class Microsoft.Azure.Management.DataFactory.Models.SecretBase refreshToken, object email, object keyFilePath, object trustedCertPath, object useSystemTrustStore, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.#ctor(System.Object,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (project As Object, authenticationType As String, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional additionalProjects As Object = null, Optional requestGoogleDriveScope As Object = null, Optional refreshToken As SecretBase = null, Optional email As Object = null, Optional keyFilePath As Object = null, Optional trustedCertPath As Object = null, Optional useSystemTrustStore As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService : obj * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService (project, authenticationType, additionalProperties, connectVia, description, additionalProjects, requestGoogleDriveScope, refreshToken, email, keyFilePath, trustedCertPath, useSystemTrustStore, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="project" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="additionalProjects" Type="System.Object" />
        <Parameter Name="requestGoogleDriveScope" Type="System.Object" />
        <Parameter Name="refreshToken" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="email" Type="System.Object" />
        <Parameter Name="keyFilePath" Type="System.Object" />
        <Parameter Name="trustedCertPath" Type="System.Object" />
        <Parameter Name="useSystemTrustStore" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="project">Das BigQuery-Standardprojekt, das abgefragt werden soll.</param>
        <param name="authenticationType">Der OAuth 2.0-Authentifizierungsmechanismus, der für die Authentifizierung verwendet wird. „ServiceAuthentication“ kann nur für eine selbstgehostete IR verwendet werden. Folgende Werte sind möglich: "ServiceAuthentication", "UserAuthentication"</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="connectVia">Der Integration Common Language Runtime-Verweis.</param>
        <param name="description">Beschreibung des verknüpften Diensts.</param>
        <param name="additionalProjects">Eine durch Trennzeichen getrennte Liste öffentlicher BigQuery-Projekte, auf die zugegriffen werden soll.</param>
        <param name="requestGoogleDriveScope">Ob Zugriff auf Google Drive angefordert werden soll. Das Zulassen des Zugriffs auf Google Drive ermöglicht die Unterstützung von Verbundtabellen, die BigQuery-Daten mit Daten auf Google Drive kombinieren. Der Standardwert ist „false“.</param>
        <param name="refreshToken">Das Aktualisierungstoken, das von Google für die Autorisierung des Zugriffs auf BigQuery für „UserAuthentication“ abgerufen wird.</param>
        <param name="email">Die E-Mail-ID des Dienstkontos, die für die „ServiceAuthentication“ verwendet wird und nur für selbstgehostete IRs verwendet werden kann.</param>
        <param name="keyFilePath">Der vollständige Pfad zur P12-Schlüsseldatei, die zur Authentifizierung der E-Mail-Adresse des Dienstkontos verwendet wird und nur für selbstgehostete IRs verwendet werden kann.</param>
        <param name="trustedCertPath">Der vollständige Pfad der PEM-Datei mit vertrauenswürdigen Zertifizierungsstellenzertifikaten zur Überprüfung des Servers beim Verbindungsaufbau über SSL. Diese Eigenschaft kann nur festgelegt werden, wenn SSL in einer selbstgehostetem IR verwendet wird. Der Standardwert ist die Datei „cacerts.pem“, die mit der IR installiert wird.</param>
        <param name="useSystemTrustStore">Gibt an, ob ein Zertifizierungsstellenzertifikat aus dem Vertrauensspeicher des Systems oder aus einer angegebenen PEM-Datei verwendet werden soll. Der Standardwert ist „false“.</param>
        <param name="encryptedCredential">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet. Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der GoogleBigQueryLinkedService-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProjects">
      <MemberSignature Language="C#" Value="public object AdditionalProjects { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalProjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AdditionalProjects" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProjects As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalProjects : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AdditionalProjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalProjects")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine durch Trennzeichen getrennte Liste der Zugriff auf Öffentliche BigQuery-Projekte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.AuthenticationType" />
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
            Abrufen oder festlegen den OAuth 2.0-Authentifizierungsmechanismus für die Authentifizierung verwendet. „ServiceAuthentication“ kann nur für eine selbstgehostete IR verwendet werden. Folgende Werte sind möglich: "ServiceAuthentication", "UserAuthentication"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public object Email { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Email" />
      <MemberSignature Language="VB.NET" Value="Public Property Email As Object" />
      <MemberSignature Language="F#" Value="member this.Email : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Dienstkonto-e-Mail-ID, die für ServiceAuthentication verwendet wird und nur für selbst gehostete IR verwendet werden können
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.EncryptedCredential" />
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
    <Member MemberName="KeyFilePath">
      <MemberSignature Language="C#" Value="public object KeyFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object KeyFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.KeyFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.KeyFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.KeyFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.keyFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den vollständigen Pfad zum Schlüssel P12-Datei, die wird die e-Mail-Adresse des Dienstkonto authentifiziert und kann nur für selbst gehostete IR verwendet werden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Project">
      <MemberSignature Language="C#" Value="public object Project { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Project" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Project" />
      <MemberSignature Language="VB.NET" Value="Public Property Project As Object" />
      <MemberSignature Language="F#" Value="member this.Project : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Project" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.project")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest BigQuery Standardprojekt für Abfragen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As SecretBase" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Aktualisierungstoken, das von Google für die Autorisierung des Zugriffs auf BigQuery für UserAuthentication abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestGoogleDriveScope">
      <MemberSignature Language="C#" Value="public object RequestGoogleDriveScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestGoogleDriveScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RequestGoogleDriveScope" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestGoogleDriveScope As Object" />
      <MemberSignature Language="F#" Value="member this.RequestGoogleDriveScope : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.RequestGoogleDriveScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestGoogleDriveScope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Zugriff auf Google Drive anzufordern. Das Zulassen des Zugriffs auf Google Drive ermöglicht die Unterstützung von Verbundtabellen, die BigQuery-Daten mit Daten auf Google Drive kombinieren. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedCertPath">
      <MemberSignature Language="C#" Value="public object TrustedCertPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrustedCertPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.TrustedCertPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedCertPath As Object" />
      <MemberSignature Language="F#" Value="member this.TrustedCertPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.TrustedCertPath" />
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
    <Member MemberName="UseSystemTrustStore">
      <MemberSignature Language="C#" Value="public object UseSystemTrustStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object UseSystemTrustStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.UseSystemTrustStore" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSystemTrustStore As Object" />
      <MemberSignature Language="F#" Value="member this.UseSystemTrustStore : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.UseSystemTrustStore" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GoogleBigQueryLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="googleBigQueryLinkedService.Validate " />
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