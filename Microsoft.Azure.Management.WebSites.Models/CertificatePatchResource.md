<Type Name="CertificatePatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource">
  <TypeSignature Language="C#" Value="public class CertificatePatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificatePatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificatePatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type CertificatePatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ARM-Ressource für ein Zertifikat.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificatePatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificatePatchResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificatePatchResource (string id = null, string name = null, string kind = null, string type = null, string friendlyName = null, string subjectName = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, byte[] pfxBlob = null, string siteName = null, string selfLink = null, string issuer = null, Nullable&lt;DateTime&gt; issueDate = null, Nullable&lt;DateTime&gt; expirationDate = null, string password = null, string thumbprint = null, Nullable&lt;bool&gt; valid = null, byte[] cerBlob = null, string publicKeyHash = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, string keyVaultId = null, string keyVaultSecretName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; keyVaultSecretStatus = null, string geoRegion = null, string serverFarmId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string friendlyName, string subjectName, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, unsigned int8[] pfxBlob, string siteName, string selfLink, string issuer, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; issueDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationDate, string password, string thumbprint, valuetype System.Nullable`1&lt;bool&gt; valid, unsigned int8[] cerBlob, string publicKeyHash, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, string keyVaultId, string keyVaultSecretName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; keyVaultSecretStatus, string geoRegion, string serverFarmId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Byte[],System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},System.Byte[],System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus},System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource : string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * byte[] * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * byte[] * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource (id, name, kind, type, friendlyName, subjectName, hostNames, pfxBlob, siteName, selfLink, issuer, issueDate, expirationDate, password, thumbprint, valid, cerBlob, publicKeyHash, hostingEnvironmentProfile, keyVaultId, keyVaultSecretName, keyVaultSecretStatus, geoRegion, serverFarmId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="subjectName" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="pfxBlob" Type="System.Byte[]" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="selfLink" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issueDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="valid" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cerBlob" Type="System.Byte[]" />
        <Parameter Name="publicKeyHash" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyVaultSecretName" Type="System.String" />
        <Parameter Name="keyVaultSecretStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" />
        <Parameter Name="geoRegion" Type="System.String" />
        <Parameter Name="serverFarmId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="friendlyName">Anzeigename des Zertifikats.</param>
        <param name="subjectName">Der Antragstellername des Zertifikats.</param>
        <param name="hostNames">Hostnamen, denen das Zertifikat gilt.</param>
        <param name="pfxBlob">PFX-Blob.</param>
        <param name="siteName">App-Name.</param>
        <param name="selfLink">Self-Link.</param>
        <param name="issuer">Aussteller des Zertifikats.</param>
        <param name="issueDate">Das Zertifikat Problem Datum.</param>
        <param name="expirationDate">Zertifikat Expriration Datum.</param>
        <param name="password">Kennwort des Zertifikats.</param>
        <param name="thumbprint">Fingerabdruck des Zertifikats.</param>
        <param name="valid">Ist Zertifikat gültig sein.</param>
        <param name="cerBlob">Rohbytes der CER-Datei</param>
        <param name="publicKeyHash">Hash für öffentliche Schlüssel.</param>
        <param name="hostingEnvironmentProfile">Spezifikation für die App Service-Umgebung für das Zertifikat zu verwenden.</param>
        <param name="keyVaultId">Ressourcen-ID für Key Vault-Csm</param>
        <param name="keyVaultSecretName">Für den geheimen Key Vault-Name.</param>
        <param name="keyVaultSecretStatus">Status des geheimen Schlüssels Key Vault.
            Folgende Werte sind möglich: "Initialisiert", "WaitingOnCertificateOrder", "Erfolgreich abgeschlossen", "CertificateOrderFailed", "OperationNotPermittedOnKeyVault", "AzureServiceUnauthorizedToAccessKeyVault", "KeyVaultDoesNotExist", " KeyVaultSecretDoesNotExist ", '" UnknownError "', 'ExternalPrivateKey', 'Unbekannt'</param>
        <param name="geoRegion">Die Region des Zertifikats.</param>
        <param name="serverFarmId">Ressourcen-ID des zugeordneten App Service-Plans formatiert: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</param>
        <summary>
            Initialisiert eine neue Instanz der CertificatePatchResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CerBlob">
      <MemberSignature Language="C#" Value="public byte[] CerBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] CerBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.CerBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CerBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.CerBlob : byte[]" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.CerBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cerBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die rohbytes der CER-Datei
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.ExpirationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.ExpirationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zertifikat Expriration Datum.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzeigenamen des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegion">
      <MemberSignature Language="C#" Value="public string GeoRegion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.GeoRegion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegion As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegion : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.GeoRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Region des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Spezifikation für die App Service-Umgebung für das Zertifikat zu verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Hostnamen das Zertifikat gilt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssueDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IssueDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IssueDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.IssueDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssueDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IssueDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.IssueDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.issueDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zertifikatsproblem Datum ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zertifikataussteller an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Key Vault Csm-Ressourcen-ID
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretName">
      <MemberSignature Language="C#" Value="public string KeyVaultSecretName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultSecretName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultSecretName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultSecretName As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultSecretName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Tresor geheimen Schlüsselnamen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultSecretStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; KeyVaultSecretStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt; KeyVaultSecretStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultSecretStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultSecretStatus As Nullable(Of KeyVaultSecretStatus)" />
      <MemberSignature Language="F#" Value="member this.KeyVaultSecretStatus : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.KeyVaultSecretStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultSecretStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.KeyVaultSecretStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Schlüsseltresors für den geheimen ab. Folgende Werte sind möglich: "Initialisiert", "WaitingOnCertificateOrder", "Erfolgreich abgeschlossen", "CertificateOrderFailed", "OperationNotPermittedOnKeyVault", "AzureServiceUnauthorizedToAccessKeyVault", "KeyVaultDoesNotExist", " KeyVaultSecretDoesNotExist ", '" UnknownError "', 'ExternalPrivateKey', 'Unbekannt'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Zertifikatskennwort.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PfxBlob">
      <MemberSignature Language="C#" Value="public byte[] PfxBlob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] PfxBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.PfxBlob" />
      <MemberSignature Language="VB.NET" Value="Public Property PfxBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.PfxBlob : byte[] with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.PfxBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pfxBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die Pfx-Blob fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeyHash">
      <MemberSignature Language="C#" Value="public string PublicKeyHash { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicKeyHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.PublicKeyHash" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicKeyHash As String" />
      <MemberSignature Language="F#" Value="member this.PublicKeyHash : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.PublicKeyHash" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicKeyHash")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Hash für öffentliche Schlüssel ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SelfLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.selfLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Self-Link.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest des zugehörigen App Service-Plans, formatiert als Ressourcen-ID: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die app-Namen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectName">
      <MemberSignature Language="C#" Value="public string SubjectName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SubjectName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubjectName As String" />
      <MemberSignature Language="F#" Value="member this.SubjectName : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.SubjectName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subjectName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Antragstellername des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zertifikatfingerabdruck an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Valid">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Valid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Valid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Valid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Valid As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Valid : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.CertificatePatchResource.Valid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.valid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zertifikat ist gültig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>