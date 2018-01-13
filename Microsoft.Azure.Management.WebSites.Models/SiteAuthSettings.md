<Type Name="SiteAuthSettings" FullName="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings">
  <TypeSignature Language="C#" Value="public class SiteAuthSettings : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteAuthSettings extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteAuthSettings&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteAuthSettings = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Konfigurationseinstellungen für die Azure App Service-Authentifizierung / Autorisierung-Funktion.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse "siteauthsettings".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteAuthSettings (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; enabled = null, string runtimeVersion = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction = null, Nullable&lt;bool&gt; tokenStoreEnabled = null, System.Collections.Generic.IList&lt;string&gt; allowedExternalRedirectUrls = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; defaultProvider = null, Nullable&lt;double&gt; tokenRefreshExtensionHours = null, string clientId = null, string clientSecret = null, string issuer = null, System.Collections.Generic.IList&lt;string&gt; allowedAudiences = null, System.Collections.Generic.IList&lt;string&gt; additionalLoginParams = null, string googleClientId = null, string googleClientSecret = null, System.Collections.Generic.IList&lt;string&gt; googleOAuthScopes = null, string facebookAppId = null, string facebookAppSecret = null, System.Collections.Generic.IList&lt;string&gt; facebookOAuthScopes = null, string twitterConsumerKey = null, string twitterConsumerSecret = null, string microsoftAccountClientId = null, string microsoftAccountClientSecret = null, System.Collections.Generic.IList&lt;string&gt; microsoftAccountOAuthScopes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; enabled, string runtimeVersion, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; unauthenticatedClientAction, valuetype System.Nullable`1&lt;bool&gt; tokenStoreEnabled, class System.Collections.Generic.IList`1&lt;string&gt; allowedExternalRedirectUrls, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; defaultProvider, valuetype System.Nullable`1&lt;float64&gt; tokenRefreshExtensionHours, string clientId, string clientSecret, string issuer, class System.Collections.Generic.IList`1&lt;string&gt; allowedAudiences, class System.Collections.Generic.IList`1&lt;string&gt; additionalLoginParams, string googleClientId, string googleClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; googleOAuthScopes, string facebookAppId, string facebookAppSecret, class System.Collections.Generic.IList`1&lt;string&gt; facebookOAuthScopes, string twitterConsumerKey, string twitterConsumerSecret, string microsoftAccountClientId, string microsoftAccountClientSecret, class System.Collections.Generic.IList`1&lt;string&gt; microsoftAccountOAuthScopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider},System.Nullable{System.Double},System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional enabled As Nullable(Of Boolean) = null, Optional runtimeVersion As String = null, Optional unauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction) = null, Optional tokenStoreEnabled As Nullable(Of Boolean) = null, Optional allowedExternalRedirectUrls As IList(Of String) = null, Optional defaultProvider As Nullable(Of BuiltInAuthenticationProvider) = null, Optional tokenRefreshExtensionHours As Nullable(Of Double) = null, Optional clientId As String = null, Optional clientSecret As String = null, Optional issuer As String = null, Optional allowedAudiences As IList(Of String) = null, Optional additionalLoginParams As IList(Of String) = null, Optional googleClientId As String = null, Optional googleClientSecret As String = null, Optional googleOAuthScopes As IList(Of String) = null, Optional facebookAppId As String = null, Optional facebookAppSecret As String = null, Optional facebookOAuthScopes As IList(Of String) = null, Optional twitterConsumerKey As String = null, Optional twitterConsumerSecret As String = null, Optional microsoftAccountClientId As String = null, Optional microsoftAccountClientSecret As String = null, Optional microsoftAccountOAuthScopes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings : string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; * Nullable&lt;double&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings (id, name, kind, type, enabled, runtimeVersion, unauthenticatedClientAction, tokenStoreEnabled, allowedExternalRedirectUrls, defaultProvider, tokenRefreshExtensionHours, clientId, clientSecret, issuer, allowedAudiences, additionalLoginParams, googleClientId, googleClientSecret, googleOAuthScopes, facebookAppId, facebookAppSecret, facebookOAuthScopes, twitterConsumerKey, twitterConsumerSecret, microsoftAccountClientId, microsoftAccountClientSecret, microsoftAccountOAuthScopes)" />
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
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="unauthenticatedClientAction" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt;" />
        <Parameter Name="tokenStoreEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="allowedExternalRedirectUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="defaultProvider" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt;" />
        <Parameter Name="tokenRefreshExtensionHours" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="allowedAudiences" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="additionalLoginParams" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="googleClientId" Type="System.String" />
        <Parameter Name="googleClientSecret" Type="System.String" />
        <Parameter Name="googleOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="facebookAppId" Type="System.String" />
        <Parameter Name="facebookAppSecret" Type="System.String" />
        <Parameter Name="facebookOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="twitterConsumerKey" Type="System.String" />
        <Parameter Name="twitterConsumerSecret" Type="System.String" />
        <Parameter Name="microsoftAccountClientId" Type="System.String" />
        <Parameter Name="microsoftAccountClientSecret" Type="System.String" />
        <Parameter Name="microsoftAccountOAuthScopes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="enabled">&lt;Code&gt;"true"&lt;/code&gt; Wenn die Authentifizierung / Autorisierung-Funktion ist für die aktuelle Anwendung aktiviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="runtimeVersion">Die RuntimeVersion der Authentifizierung / Autorisierung feature für die aktuelle app verwendet.
            Die Einstellung in diesem Wert kann kontrollieren des Verhaltens von bestimmten Funktionen in die Authentifizierung / Autorisierung-Modul.</param>
        <param name="unauthenticatedClientAction">Die Aktion, die ausgeführt wird, wenn ein nicht authentifizierter Client versucht, auf die app zugreifen. Folgende Werte sind möglich: "RedirectToLoginPage", "AllowAnonymous"</param>
        <param name="tokenStoreEnabled">&lt;Code&gt;"true"&lt;/code&gt; plattformspezifischen Sicherheitstoken dauerhaft zu speichern, die während der Anmeldung Flüsse abgerufen wurde, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.
            Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="allowedExternalRedirectUrls">Externe URLs, die im Rahmen der Protokollierung bzw. aus einer app-Protokollierung in umgeleitet werden können. Beachten Sie, dass der Teil der URL der Abfragezeichenfolge wird ignoriert.
            Dies ist eine erweiterte Einstellung, die in der Regel nur von Windows Store-Anwendung Back-Ends erforderlich.
            Beachten Sie, dass URLs in der aktuellen Domäne immer implizit zulässig sind.</param>
        <param name="defaultProvider">Der Standard-Authentifizierungsanbieter verwenden, wenn mehrere Anbieter konfiguriert werden.
            Diese Einstellung ist nur erforderlich, wenn mehrere Anbieter konfiguriert sind und die Aktion nicht authentifizierter Client "RedirectToLoginPage" festgelegt ist. Folgende Werte sind möglich: "AzureActiveDirectory", "Facebook", "Google", "MicrosoftAccount", "Twitter"</param>
        <param name="tokenRefreshExtensionHours">Die Anzahl der Stunden nach der tokenablauf Sitzung, die ein Sitzungstoken für die Aktualisierung des Zugriffstokens-API-Aufruf verwendet werden kann. Die Standardeinstellung beträgt 72 Stunden.</param>
        <param name="clientId">Die Client-ID für diese Anwendung vertrauenden Seite, als die "client_id" bezeichnet.
            Diese Einstellung ist zum Aktivieren von OpenID Verbindungsauthentifizierung mit Azure Active Directory oder andere 3rd Party OpenID Connect-Anbieter erforderlich.
            Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</param>
        <param name="clientSecret">Der geheime Clientschlüssel, der Anwendung dieser vertrauenden Seite (in Azure Active Directory, dies wird auch bezeichnet als Schlüssel).
            Diese Einstellung ist optional. Wenn kein clientgeheimnis konfiguriert ist, wird der OpenID Connect implizite Auth-Datenfluss verwendet, um Endbenutzer zu authentifizieren.
            Andernfalls wird der OpenID verbinden Autorisierung Codefluss verwendet, um Endbenutzer zu authentifizieren.
            Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</param>
        <param name="issuer">Die OpenID verbinden Issuer-URI, die die Entität darstellt, bei die Zugriffstoken für diese Anwendung ausstellt.
            Wenn Sie Azure Active Directory zu verwenden, wird dieser Wert ist der URI des Directory-Mandanten, z. B. https://sts.windows.net/ {Mandanten-Guid} /.
            Dieser URI wird ein Groß-/Kleinschreibung Bezeichner für den Aussteller des Tokens.
            Weitere Informationen zum Verbinden OpenID-Ermittlung: http://openid.net/specs/openid-connect-discovery-1_0.html</param>
        <param name="allowedAudiences">Zulässige Audience-Werte beim Überprüfen von Azure Active Directory ausgestellt JWTs berücksichtigt werden. Beachten Sie, dass die &lt;Code&gt;ClientID&lt;/code&gt; Wert ist immer eine zulässige Zielgruppe, unabhängig von dieser Einstellung berücksichtigt.</param>
        <param name="additionalLoginParams">Parameter für die Anmeldung an den autorisierungsendpunkt OpenID Connect Wenn ein Benutzer anmeldet. Jeder Parameter muss im Format "Schlüssel = Wert".</param>
        <param name="googleClientId">Die OpenID verbinden Client-ID für die Google-Webanwendung.
            Diese Einstellung ist erforderlich für Google Sign-In aktivieren.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</param>
        <param name="googleClientSecret">Der geheime Clientschlüssel Google-Webanwendung zugeordnet ist.
            Diese Einstellung ist erforderlich für Google Sign-In aktivieren.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</param>
        <param name="googleOAuthScopes">Die OAuth 2.0-Bereiche, die im Rahmen der Sign-In Google-Authentifizierung angefordert werden.
            Diese Einstellung ist optional. Wenn nicht angegeben, werden als Standardbereiche "Openid", "Profil" und "Email" verwendet.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</param>
        <param name="facebookAppId">Die App-ID, der die Facebook-app für die Anmeldung verwendet werden soll.
            Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</param>
        <param name="facebookAppSecret">Der geheime Anwendungsschlüssel der Facebook-app für die Facebook-Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</param>
        <param name="facebookOAuthScopes">Die OAuth 2.0-Bereiche, die im Rahmen der Authentifizierung der Facebook-Anmeldung angefordert werden.
            Diese Einstellung ist optional.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</param>
        <param name="twitterConsumerKey">Der OAuth 1.0a consumerschlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.
            Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</param>
        <param name="twitterConsumerSecret">Der Consumer OAuth 1.0a geheime Schlüssel des Twitter-Anwendung, die für die Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.
            Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</param>
        <param name="microsoftAccountClientId">Die OAuth 2.0-Client-ID, die für die app, die für die Authentifizierung verwendet wurde.
            Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.
            Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</param>
        <param name="microsoftAccountClientSecret">Die OAuth 2.0-clientgeheimnis, die für die app, die für die Authentifizierung verwendet wurde.
            Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.
            Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</param>
        <param name="microsoftAccountOAuthScopes">Die OAuth 2.0-Bereiche, die im Rahmen der Authentifizierung der Microsoft-Account angefordert werden.
            Diese Einstellung ist optional. Wenn nicht angegeben, wird "wl.basic" als den Standardbereich verwendet.
            Dokumentation zu Microsoft-Konto-Bereiche und Berechtigungen: https://msdn.microsoft.com/en-us/library/dn631845.aspx</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "siteauthsettings".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLoginParams">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalLoginParams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalLoginParams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AdditionalLoginParams" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLoginParams As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLoginParams : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AdditionalLoginParams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.additionalLoginParams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Parameter für die Anmeldung an den autorisierungsendpunkt OpenID Connect senden, wenn ein Benutzer anmeldet. Jeder Parameter muss im Format "Schlüssel = Wert".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedAudiences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedAudiences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedAudiences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedAudiences" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedAudiences As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedAudiences : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedAudiences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedAudiences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert zulässige Audience-Werte beim Überprüfen von Azure Active Directory ausgestellt JWTs berücksichtigt werden. Beachten Sie, dass die &amp;Lt; Code&amp;Gt; ClientID&amp;Lt; / code&amp;Gt; Wert ist immer eine zulässige Zielgruppe, unabhängig von dieser Einstellung berücksichtigt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedExternalRedirectUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedExternalRedirectUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedExternalRedirectUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedExternalRedirectUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedExternalRedirectUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedExternalRedirectUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.AllowedExternalRedirectUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedExternalRedirectUrls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie externe URLs, die in umgeleitet werden können als Teil der Protokollierung bzw. aus einer app-Protokollierung fest. Beachten Sie, dass der Teil der URL der Abfragezeichenfolge wird ignoriert.
            Dies ist eine erweiterte Einstellung, die in der Regel nur von Windows Store-Anwendung Back-Ends erforderlich.
            Beachten Sie, dass URLs in der aktuellen Domäne immer implizit zulässig sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Client-ID für diese Anwendung vertrauenden Seite, als die "client_id" bezeichnet.
            Diese Einstellung ist zum Aktivieren von OpenID Verbindungsauthentifizierung mit Azure Active Directory oder andere 3rd Party OpenID Connect-Anbieter erforderlich.
            Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den geheimen Clientschlüssel, der Anwendung dieser vertrauenden Seite (in Azure Active Directory, dies wird auch bezeichnet als Schlüssel).
            Diese Einstellung ist optional. Wenn kein clientgeheimnis konfiguriert ist, wird der OpenID Connect implizite Auth-Datenfluss verwendet, um Endbenutzer zu authentifizieren.
            Andernfalls wird der OpenID verbinden Autorisierung Codefluss verwendet, um Endbenutzer zu authentifizieren.
            Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProvider">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; DefaultProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; DefaultProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.DefaultProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProvider As Nullable(Of BuiltInAuthenticationProvider)" />
      <MemberSignature Language="F#" Value="member this.DefaultProvider : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.DefaultProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BuiltInAuthenticationProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Standardanbieter für die Authentifizierung zu verwenden, wenn mehrere Anbieter konfiguriert werden.
            Diese Einstellung ist nur erforderlich, wenn mehrere Anbieter konfiguriert sind und die Aktion nicht authentifizierter Client "RedirectToLoginPage" festgelegt ist. Folgende Werte sind möglich: "AzureActiveDirectory", "Facebook", "Google", "MicrosoftAccount", "Twitter"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die Authentifizierung / Autorisierung-Funktion ist für die aktuelle Anwendung aktiviert ist, andernfalls &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppId">
      <MemberSignature Language="C#" Value="public string FacebookAppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppId" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppId As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookAppId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die App-ID der Facebook-app, die für die Anmeldung verwendeten.
            Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookAppSecret">
      <MemberSignature Language="C#" Value="public string FacebookAppSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FacebookAppSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookAppSecret As String" />
      <MemberSignature Language="F#" Value="member this.FacebookAppSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookAppSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookAppSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das App-Geheimnis der Facebook-app für die Facebook-Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FacebookOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; FacebookOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; FacebookOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property FacebookOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.FacebookOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.FacebookOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.facebookOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Authentifizierung der Facebook-Anmeldung.
            Diese Einstellung ist optional.
            Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientId">
      <MemberSignature Language="C#" Value="public string GoogleClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientId As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OpenID verbinden Client-ID für die Google-Webanwendung.
            Diese Einstellung ist erforderlich für Google Sign-In aktivieren.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleClientSecret">
      <MemberSignature Language="C#" Value="public string GoogleClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GoogleClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.GoogleClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleClientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der geheime Clientschlüssel Google-Webanwendung zugeordnet.
            Diese Einstellung ist erforderlich für Google Sign-In aktivieren.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GoogleOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GoogleOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GoogleOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property GoogleOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GoogleOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.GoogleOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.googleOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Sign-In Google-Authentifizierung.
            Diese Einstellung ist optional. Wenn nicht angegeben, werden als Standardbereiche "Openid", "Profil" und "Email" verwendet.
            Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.Issuer" />
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
            Abrufen oder Festlegen der OpenID verbinden Issuer-URI, der die Entität darstellt, bei die Zugriffstoken für diese Anwendung ausstellt.
            Wenn Sie Azure Active Directory zu verwenden, wird dieser Wert ist der URI des Directory-Mandanten, z. B. https://sts.windows.net/ {Mandanten-Guid} /.
            Dieser URI wird ein Groß-/Kleinschreibung Bezeichner für den Aussteller des Tokens.
            Weitere Informationen zum Verbinden OpenID-Ermittlung: http://openid.net/specs/openid-connect-discovery-1_0.html
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientId">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientId As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountClientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die OAuth 2.0-Client-ID, die für die app, die für die Authentifizierung verwendet wurde.
            Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.
            Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountClientSecret">
      <MemberSignature Language="C#" Value="public string MicrosoftAccountClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicrosoftAccountClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountClientSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountClientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das OAuth 2.0-Client-Geheimnis, das für die app, die für die Authentifizierung verwendet erstellt wurde.
            Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.
            Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAccountOAuthScopes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; MicrosoftAccountOAuthScopes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountOAuthScopes" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftAccountOAuthScopes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.MicrosoftAccountOAuthScopes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.MicrosoftAccountOAuthScopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftAccountOAuthScopes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Microsoft-Account-Authentifizierung.
            Diese Einstellung ist optional. Wenn nicht angegeben, wird "wl.basic" als den Standardbereich verwendet.
            Dokumentation zu Microsoft-Konto-Bereiche und Berechtigungen: https://msdn.microsoft.com/en-us/library/dn631845.aspx
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die RuntimeVersion der Authentifizierung / Autorisierung feature für die aktuelle app verwendet.
            Die Einstellung in diesem Wert kann kontrollieren des Verhaltens von bestimmten Funktionen in die Authentifizierung / Autorisierung-Modul.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenRefreshExtensionHours">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; TokenRefreshExtensionHours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; TokenRefreshExtensionHours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenRefreshExtensionHours" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenRefreshExtensionHours As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.TokenRefreshExtensionHours : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenRefreshExtensionHours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenRefreshExtensionHours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Stunden nach der tokenablauf Sitzung, die ein Sitzungstoken verwendet werden kann, für die Aktualisierung des Zugriffstokens-API-Aufruf. Die Standardeinstellung beträgt 72 Stunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenStoreEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; TokenStoreEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; TokenStoreEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenStoreEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenStoreEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TokenStoreEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TokenStoreEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenStoreEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; plattformspezifischen Sicherheitstoken dauerhaft zu speichern, die während der Anmeldung Flüsse abgerufen wurde, andernfalls &amp;Lt; Code&amp;Gt "false" &amp;Lt; / code&amp;Gt;.
            Die Standardeinstellung ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerKey">
      <MemberSignature Language="C#" Value="public string TwitterConsumerKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerKey" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerKey As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerKey : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.twitterConsumerKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt den OAuth 1.0a Consumer-Schlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.
            Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TwitterConsumerSecret">
      <MemberSignature Language="C#" Value="public string TwitterConsumerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TwitterConsumerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property TwitterConsumerSecret As String" />
      <MemberSignature Language="F#" Value="member this.TwitterConsumerSecret : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.TwitterConsumerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.twitterConsumerSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der OAuth 1.0a consumerschlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.
            Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.
            Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnauthenticatedClientAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; UnauthenticatedClientAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.UnauthenticatedClientAction" />
      <MemberSignature Language="VB.NET" Value="Public Property UnauthenticatedClientAction As Nullable(Of UnauthenticatedClientAction)" />
      <MemberSignature Language="F#" Value="member this.UnauthenticatedClientAction : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteAuthSettings.UnauthenticatedClientAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unauthenticatedClientAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.UnauthenticatedClientAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Aktion an, wenn ein nicht authentifizierter Client versucht, auf die app zugreifen. Folgende Werte sind möglich: "RedirectToLoginPage", "AllowAnonymous"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>