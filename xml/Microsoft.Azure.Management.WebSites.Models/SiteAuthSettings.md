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
            <span data-ttu-id="0eaa8-101">Konfigurationseinstellungen für die Azure App Service-Authentifizierung / Autorisierung-Funktion.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-101">Configuration settings for the Azure App Service Authentication / Authorization feature.</span></span>
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
            <span data-ttu-id="0eaa8-102">Initialisiert eine neue Instanz der Klasse "siteauthsettings".</span><span class="sxs-lookup"><span data-stu-id="0eaa8-102">Initializes a new instance of the SiteAuthSettings class.</span></span>
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
        <param name="id"><span data-ttu-id="0eaa8-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="0eaa8-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="0eaa8-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="0eaa8-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-106">Resource type.</span></span></param>
        <param name="enabled"><span data-ttu-id="0eaa8-107">&lt;Code&gt;"true"&lt;/code&gt; Wenn die Authentifizierung / Autorisierung-Funktion ist für die aktuelle Anwendung aktiviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-107">&lt;code&gt;true&lt;/code&gt; if the Authentication / Authorization feature is enabled for the current app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="0eaa8-108">Die RuntimeVersion der Authentifizierung / Autorisierung feature für die aktuelle app verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-108">The RuntimeVersion of the Authentication / Authorization feature in use for the current app.</span></span>
            <span data-ttu-id="0eaa8-109">Die Einstellung in diesem Wert kann kontrollieren des Verhaltens von bestimmten Funktionen in die Authentifizierung / Autorisierung-Modul.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-109">The setting in this value can control the behavior of certain features in the Authentication / Authorization module.</span></span></param>
        <param name="unauthenticatedClientAction"><span data-ttu-id="0eaa8-110">Die Aktion, die ausgeführt wird, wenn ein nicht authentifizierter Client versucht, auf die app zugreifen.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-110">The action to take when an unauthenticated client attempts to access the app.</span></span> <span data-ttu-id="0eaa8-111">Folgende Werte sind möglich: "RedirectToLoginPage", "AllowAnonymous"</span><span class="sxs-lookup"><span data-stu-id="0eaa8-111">Possible values include: 'RedirectToLoginPage', 'AllowAnonymous'</span></span></param>
        <param name="tokenStoreEnabled"><span data-ttu-id="0eaa8-112">&lt;Code&gt;"true"&lt;/code&gt; plattformspezifischen Sicherheitstoken dauerhaft zu speichern, die während der Anmeldung Flüsse abgerufen wurde, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-112">&lt;code&gt;true&lt;/code&gt; to durably store platform-specific security tokens that are obtained during login flows; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span>
            <span data-ttu-id="0eaa8-113">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-113">The default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="allowedExternalRedirectUrls"><span data-ttu-id="0eaa8-114">Externe URLs, die im Rahmen der Protokollierung bzw. aus einer app-Protokollierung in umgeleitet werden können.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-114">External URLs that can be redirected to as part of logging in or logging out of the app.</span></span> <span data-ttu-id="0eaa8-115">Beachten Sie, dass der Teil der URL der Abfragezeichenfolge wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-115">Note that the query string part of the URL is ignored.</span></span>
            <span data-ttu-id="0eaa8-116">Dies ist eine erweiterte Einstellung, die in der Regel nur von Windows Store-Anwendung Back-Ends erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-116">This is an advanced setting typically only needed by Windows Store application backends.</span></span>
            <span data-ttu-id="0eaa8-117">Beachten Sie, dass URLs in der aktuellen Domäne immer implizit zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-117">Note that URLs within the current domain are always implicitly allowed.</span></span></param>
        <param name="defaultProvider"><span data-ttu-id="0eaa8-118">Der Standard-Authentifizierungsanbieter verwenden, wenn mehrere Anbieter konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-118">The default authentication provider to use when multiple providers are configured.</span></span>
            <span data-ttu-id="0eaa8-119">Diese Einstellung ist nur erforderlich, wenn mehrere Anbieter konfiguriert sind und die Aktion nicht authentifizierter Client "RedirectToLoginPage" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-119">This setting is only needed if multiple providers are configured and the unauthenticated client action is set to "RedirectToLoginPage".</span></span> <span data-ttu-id="0eaa8-120">Folgende Werte sind möglich: "AzureActiveDirectory", "Facebook", "Google", "MicrosoftAccount", "Twitter"</span><span class="sxs-lookup"><span data-stu-id="0eaa8-120">Possible values include: 'AzureActiveDirectory', 'Facebook', 'Google', 'MicrosoftAccount', 'Twitter'</span></span></param>
        <param name="tokenRefreshExtensionHours"><span data-ttu-id="0eaa8-121">Die Anzahl der Stunden nach der tokenablauf Sitzung, die ein Sitzungstoken für die Aktualisierung des Zugriffstokens-API-Aufruf verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-121">The number of hours after session token expiration that a session token can be used to call the token refresh API.</span></span> <span data-ttu-id="0eaa8-122">Die Standardeinstellung beträgt 72 Stunden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-122">The default is 72 hours.</span></span></param>
        <param name="clientId"><span data-ttu-id="0eaa8-123">Die Client-ID für diese Anwendung vertrauenden Seite, als die "client_id" bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-123">The Client ID of this relying party application, known as the client_id.</span></span>
            <span data-ttu-id="0eaa8-124">Diese Einstellung ist zum Aktivieren von OpenID Verbindungsauthentifizierung mit Azure Active Directory oder andere 3rd Party OpenID Connect-Anbieter erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-124">This setting is required for enabling OpenID Connection authentication with Azure Active Directory or other 3rd party OpenID Connect providers.</span></span>
            <span data-ttu-id="0eaa8-125">Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-125">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span></param>
        <param name="clientSecret"><span data-ttu-id="0eaa8-126">Der geheime Clientschlüssel, der Anwendung dieser vertrauenden Seite (in Azure Active Directory, dies wird auch bezeichnet als Schlüssel).</span><span class="sxs-lookup"><span data-stu-id="0eaa8-126">The Client Secret of this relying party application (in Azure Active Directory, this is also referred to as the Key).</span></span>
            <span data-ttu-id="0eaa8-127">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-127">This setting is optional.</span></span> <span data-ttu-id="0eaa8-128">Wenn kein clientgeheimnis konfiguriert ist, wird der OpenID Connect implizite Auth-Datenfluss verwendet, um Endbenutzer zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-128">If no client secret is configured, the OpenID Connect implicit auth flow is used to authenticate end users.</span></span>
            <span data-ttu-id="0eaa8-129">Andernfalls wird der OpenID verbinden Autorisierung Codefluss verwendet, um Endbenutzer zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-129">Otherwise, the OpenID Connect Authorization Code Flow is used to authenticate end users.</span></span>
            <span data-ttu-id="0eaa8-130">Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-130">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span></param>
        <param name="issuer"><span data-ttu-id="0eaa8-131">Die OpenID verbinden Issuer-URI, die die Entität darstellt, bei die Zugriffstoken für diese Anwendung ausstellt.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-131">The OpenID Connect Issuer URI that represents the entity which issues access tokens for this application.</span></span>
            <span data-ttu-id="0eaa8-132">Wenn Sie Azure Active Directory zu verwenden, wird dieser Wert ist der URI des Directory-Mandanten, z. B. https://sts.windows.net/ {Mandanten-Guid} /.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-132">When using Azure Active Directory, this value is the URI of the directory tenant, e.g. https://sts.windows.net/{tenant-guid}/.</span></span>
            <span data-ttu-id="0eaa8-133">Dieser URI wird ein Groß-/Kleinschreibung Bezeichner für den Aussteller des Tokens.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-133">This URI is a case-sensitive identifier for the token issuer.</span></span>
            <span data-ttu-id="0eaa8-134">Weitere Informationen zum Verbinden OpenID-Ermittlung: http://openid.net/specs/openid-connect-discovery-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-134">More information on OpenID Connect Discovery: http://openid.net/specs/openid-connect-discovery-1_0.html</span></span></param>
        <param name="allowedAudiences"><span data-ttu-id="0eaa8-135">Zulässige Audience-Werte beim Überprüfen von Azure Active Directory ausgestellt JWTs berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-135">Allowed audience values to consider when validating JWTs issued by Azure Active Directory.</span></span> <span data-ttu-id="0eaa8-136">Beachten Sie, dass die &lt;Code&gt;ClientID&lt;/code&gt; Wert ist immer eine zulässige Zielgruppe, unabhängig von dieser Einstellung berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-136">Note that the &lt;code&gt;ClientID&lt;/code&gt; value is always considered an allowed audience, regardless of this setting.</span></span></param>
        <param name="additionalLoginParams"><span data-ttu-id="0eaa8-137">Parameter für die Anmeldung an den autorisierungsendpunkt OpenID Connect Wenn ein Benutzer anmeldet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-137">Login parameters to send to the OpenID Connect authorization endpoint when a user logs in.</span></span> <span data-ttu-id="0eaa8-138">Jeder Parameter muss im Format "Schlüssel = Wert".</span><span class="sxs-lookup"><span data-stu-id="0eaa8-138">Each parameter must be in the form "key=value".</span></span></param>
        <param name="googleClientId"><span data-ttu-id="0eaa8-139">Die OpenID verbinden Client-ID für die Google-Webanwendung.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-139">The OpenID Connect Client ID for the Google web application.</span></span>
            <span data-ttu-id="0eaa8-140">Diese Einstellung ist erforderlich für Google Sign-In aktivieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-140">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="0eaa8-141">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-141">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="googleClientSecret"><span data-ttu-id="0eaa8-142">Der geheime Clientschlüssel Google-Webanwendung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-142">The client secret associated with the Google web application.</span></span>
            <span data-ttu-id="0eaa8-143">Diese Einstellung ist erforderlich für Google Sign-In aktivieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-143">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="0eaa8-144">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-144">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="googleOAuthScopes"><span data-ttu-id="0eaa8-145">Die OAuth 2.0-Bereiche, die im Rahmen der Sign-In Google-Authentifizierung angefordert werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-145">The OAuth 2.0 scopes that will be requested as part of Google Sign-In authentication.</span></span>
            <span data-ttu-id="0eaa8-146">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-146">This setting is optional.</span></span> <span data-ttu-id="0eaa8-147">Wenn nicht angegeben, werden als Standardbereiche "Openid", "Profil" und "Email" verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-147">If not specified, "openid", "profile", and "email" are used as default scopes.</span></span>
            <span data-ttu-id="0eaa8-148">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-148">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span></param>
        <param name="facebookAppId"><span data-ttu-id="0eaa8-149">Die App-ID, der die Facebook-app für die Anmeldung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-149">The App ID of the Facebook app used for login.</span></span>
            <span data-ttu-id="0eaa8-150">Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-150">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-151">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-151">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="facebookAppSecret"><span data-ttu-id="0eaa8-152">Der geheime Anwendungsschlüssel der Facebook-app für die Facebook-Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-152">The App Secret of the Facebook app used for Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-153">Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-153">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-154">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-154">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="facebookOAuthScopes"><span data-ttu-id="0eaa8-155">Die OAuth 2.0-Bereiche, die im Rahmen der Authentifizierung der Facebook-Anmeldung angefordert werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-155">The OAuth 2.0 scopes that will be requested as part of Facebook Login authentication.</span></span>
            <span data-ttu-id="0eaa8-156">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-156">This setting is optional.</span></span>
            <span data-ttu-id="0eaa8-157">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-157">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span></param>
        <param name="twitterConsumerKey"><span data-ttu-id="0eaa8-158">Der OAuth 1.0a consumerschlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-158">The OAuth 1.0a consumer key of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="0eaa8-159">Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-159">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="0eaa8-160">Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="0eaa8-160">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span></param>
        <param name="twitterConsumerSecret"><span data-ttu-id="0eaa8-161">Der Consumer OAuth 1.0a geheime Schlüssel des Twitter-Anwendung, die für die Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-161">The OAuth 1.0a consumer secret of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="0eaa8-162">Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-162">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="0eaa8-163">Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="0eaa8-163">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span></param>
        <param name="microsoftAccountClientId"><span data-ttu-id="0eaa8-164">Die OAuth 2.0-Client-ID, die für die app, die für die Authentifizierung verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-164">The OAuth 2.0 client ID that was created for the app used for authentication.</span></span>
            <span data-ttu-id="0eaa8-165">Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-165">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-166">Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="0eaa8-166">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span></param>
        <param name="microsoftAccountClientSecret"><span data-ttu-id="0eaa8-167">Die OAuth 2.0-clientgeheimnis, die für die app, die für die Authentifizierung verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-167">The OAuth 2.0 client secret that was created for the app used for authentication.</span></span>
            <span data-ttu-id="0eaa8-168">Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-168">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-169">Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="0eaa8-169">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span></param>
        <param name="microsoftAccountOAuthScopes"><span data-ttu-id="0eaa8-170">Die OAuth 2.0-Bereiche, die im Rahmen der Authentifizierung der Microsoft-Account angefordert werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-170">The OAuth 2.0 scopes that will be requested as part of Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-171">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-171">This setting is optional.</span></span> <span data-ttu-id="0eaa8-172">Wenn nicht angegeben, wird "wl.basic" als den Standardbereich verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-172">If not specified, "wl.basic" is used as the default scope.</span></span>
            <span data-ttu-id="0eaa8-173">Dokumentation zu Microsoft-Konto-Bereiche und Berechtigungen: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span><span class="sxs-lookup"><span data-stu-id="0eaa8-173">Microsoft Account Scopes and permissions documentation: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span></span></param>
        <summary>
            <span data-ttu-id="0eaa8-174">Initialisiert eine neue Instanz der Klasse "siteauthsettings".</span><span class="sxs-lookup"><span data-stu-id="0eaa8-174">Initializes a new instance of the SiteAuthSettings class.</span></span>
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
            <span data-ttu-id="0eaa8-175">Ruft ab oder legt Parameter für die Anmeldung an den autorisierungsendpunkt OpenID Connect senden, wenn ein Benutzer anmeldet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-175">Gets or sets login parameters to send to the OpenID Connect authorization endpoint when a user logs in.</span></span> <span data-ttu-id="0eaa8-176">Jeder Parameter muss im Format "Schlüssel = Wert".</span><span class="sxs-lookup"><span data-stu-id="0eaa8-176">Each parameter must be in the form "key=value".</span></span>
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
            <span data-ttu-id="0eaa8-177">Ermittelt oder definiert zulässige Audience-Werte beim Überprüfen von Azure Active Directory ausgestellt JWTs berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-177">Gets or sets allowed audience values to consider when validating JWTs issued by Azure Active Directory.</span></span> <span data-ttu-id="0eaa8-178">Beachten Sie, dass die &amp;Lt; Code&amp;Gt; ClientID&amp;Lt; / code&amp;Gt; Wert ist immer eine zulässige Zielgruppe, unabhängig von dieser Einstellung berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-178">Note that the &amp;lt;code&amp;gt;ClientID&amp;lt;/code&amp;gt; value is always considered an allowed audience, regardless of this setting.</span></span>
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
            <span data-ttu-id="0eaa8-179">Ruft ab, oder legt Sie externe URLs, die in umgeleitet werden können als Teil der Protokollierung bzw. aus einer app-Protokollierung fest.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-179">Gets or sets external URLs that can be redirected to as part of logging in or logging out of the app.</span></span> <span data-ttu-id="0eaa8-180">Beachten Sie, dass der Teil der URL der Abfragezeichenfolge wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-180">Note that the query string part of the URL is ignored.</span></span>
            <span data-ttu-id="0eaa8-181">Dies ist eine erweiterte Einstellung, die in der Regel nur von Windows Store-Anwendung Back-Ends erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-181">This is an advanced setting typically only needed by Windows Store application backends.</span></span>
            <span data-ttu-id="0eaa8-182">Beachten Sie, dass URLs in der aktuellen Domäne immer implizit zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-182">Note that URLs within the current domain are always implicitly allowed.</span></span>
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
            <span data-ttu-id="0eaa8-183">Ruft ab oder legt die Client-ID für diese Anwendung vertrauenden Seite, als die "client_id" bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-183">Gets or sets the Client ID of this relying party application, known as the client_id.</span></span>
            <span data-ttu-id="0eaa8-184">Diese Einstellung ist zum Aktivieren von OpenID Verbindungsauthentifizierung mit Azure Active Directory oder andere 3rd Party OpenID Connect-Anbieter erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-184">This setting is required for enabling OpenID Connection authentication with Azure Active Directory or other 3rd party OpenID Connect providers.</span></span>
            <span data-ttu-id="0eaa8-185">Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-185">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
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
            <span data-ttu-id="0eaa8-186">Ruft ab oder legt den geheimen Clientschlüssel, der Anwendung dieser vertrauenden Seite (in Azure Active Directory, dies wird auch bezeichnet als Schlüssel).</span><span class="sxs-lookup"><span data-stu-id="0eaa8-186">Gets or sets the Client Secret of this relying party application (in Azure Active Directory, this is also referred to as the Key).</span></span>
            <span data-ttu-id="0eaa8-187">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-187">This setting is optional.</span></span> <span data-ttu-id="0eaa8-188">Wenn kein clientgeheimnis konfiguriert ist, wird der OpenID Connect implizite Auth-Datenfluss verwendet, um Endbenutzer zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-188">If no client secret is configured, the OpenID Connect implicit auth flow is used to authenticate end users.</span></span>
            <span data-ttu-id="0eaa8-189">Andernfalls wird der OpenID verbinden Autorisierung Codefluss verwendet, um Endbenutzer zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-189">Otherwise, the OpenID Connect Authorization Code Flow is used to authenticate end users.</span></span>
            <span data-ttu-id="0eaa8-190">Weitere Informationen zu OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-190">More information on OpenID Connect: http://openid.net/specs/openid-connect-core-1_0.html</span></span>
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
            <span data-ttu-id="0eaa8-191">Ruft ab oder legt den Standardanbieter für die Authentifizierung zu verwenden, wenn mehrere Anbieter konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-191">Gets or sets the default authentication provider to use when multiple providers are configured.</span></span>
            <span data-ttu-id="0eaa8-192">Diese Einstellung ist nur erforderlich, wenn mehrere Anbieter konfiguriert sind und die Aktion nicht authentifizierter Client "RedirectToLoginPage" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-192">This setting is only needed if multiple providers are configured and the unauthenticated client action is set to "RedirectToLoginPage".</span></span> <span data-ttu-id="0eaa8-193">Folgende Werte sind möglich: "AzureActiveDirectory", "Facebook", "Google", "MicrosoftAccount", "Twitter"</span><span class="sxs-lookup"><span data-stu-id="0eaa8-193">Possible values include: 'AzureActiveDirectory', 'Facebook', 'Google', 'MicrosoftAccount', 'Twitter'</span></span>
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
            <span data-ttu-id="0eaa8-194">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die Authentifizierung / Autorisierung-Funktion ist für die aktuelle Anwendung aktiviert ist, andernfalls &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-194">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the Authentication / Authorization feature is enabled for the current app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="0eaa8-195">Ruft ab oder legt die App-ID der Facebook-app, die für die Anmeldung verwendeten.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-195">Gets or sets the App ID of the Facebook app used for login.</span></span>
            <span data-ttu-id="0eaa8-196">Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-196">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-197">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-197">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
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
            <span data-ttu-id="0eaa8-198">Ruft ab oder legt das App-Geheimnis der Facebook-app für die Facebook-Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-198">Gets or sets the App Secret of the Facebook app used for Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-199">Diese Einstellung ist zum Aktivieren von Facebook-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-199">This setting is required for enabling Facebook Login.</span></span>
            <span data-ttu-id="0eaa8-200">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-200">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
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
            <span data-ttu-id="0eaa8-201">Ruft ab oder legt die OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Authentifizierung der Facebook-Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-201">Gets or sets the OAuth 2.0 scopes that will be requested as part of Facebook Login authentication.</span></span>
            <span data-ttu-id="0eaa8-202">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-202">This setting is optional.</span></span>
            <span data-ttu-id="0eaa8-203">Facebook-Anmeldung Dokumentation: https://developers.facebook.com/docs/facebook-login</span><span class="sxs-lookup"><span data-stu-id="0eaa8-203">Facebook Login documentation: https://developers.facebook.com/docs/facebook-login</span></span>
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
            <span data-ttu-id="0eaa8-204">Ruft ab oder legt die OpenID verbinden Client-ID für die Google-Webanwendung.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-204">Gets or sets the OpenID Connect Client ID for the Google web application.</span></span>
            <span data-ttu-id="0eaa8-205">Diese Einstellung ist erforderlich für Google Sign-In aktivieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-205">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="0eaa8-206">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-206">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
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
            <span data-ttu-id="0eaa8-207">Abrufen oder Festlegen der geheime Clientschlüssel Google-Webanwendung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-207">Gets or sets the client secret associated with the Google web application.</span></span>
            <span data-ttu-id="0eaa8-208">Diese Einstellung ist erforderlich für Google Sign-In aktivieren.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-208">This setting is required for enabling Google Sign-In.</span></span>
            <span data-ttu-id="0eaa8-209">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-209">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
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
            <span data-ttu-id="0eaa8-210">Ruft ab oder legt die OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Sign-In Google-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-210">Gets or sets the OAuth 2.0 scopes that will be requested as part of Google Sign-In authentication.</span></span>
            <span data-ttu-id="0eaa8-211">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-211">This setting is optional.</span></span> <span data-ttu-id="0eaa8-212">Wenn nicht angegeben, werden als Standardbereiche "Openid", "Profil" und "Email" verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-212">If not specified, "openid", "profile", and "email" are used as default scopes.</span></span>
            <span data-ttu-id="0eaa8-213">Sign-In Google-Dokumentation: https://developers.google.com/identity/sign-in/web/</span><span class="sxs-lookup"><span data-stu-id="0eaa8-213">Google Sign-In documentation: https://developers.google.com/identity/sign-in/web/</span></span>
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
            <span data-ttu-id="0eaa8-214">Abrufen oder Festlegen der OpenID verbinden Issuer-URI, der die Entität darstellt, bei die Zugriffstoken für diese Anwendung ausstellt.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-214">Gets or sets the OpenID Connect Issuer URI that represents the entity which issues access tokens for this application.</span></span>
            <span data-ttu-id="0eaa8-215">Wenn Sie Azure Active Directory zu verwenden, wird dieser Wert ist der URI des Directory-Mandanten, z. B. https://sts.windows.net/ {Mandanten-Guid} /.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-215">When using Azure Active Directory, this value is the URI of the directory tenant, e.g. https://sts.windows.net/{tenant-guid}/.</span></span>
            <span data-ttu-id="0eaa8-216">Dieser URI wird ein Groß-/Kleinschreibung Bezeichner für den Aussteller des Tokens.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-216">This URI is a case-sensitive identifier for the token issuer.</span></span>
            <span data-ttu-id="0eaa8-217">Weitere Informationen zum Verbinden OpenID-Ermittlung: http://openid.net/specs/openid-connect-discovery-1_0.html</span><span class="sxs-lookup"><span data-stu-id="0eaa8-217">More information on OpenID Connect Discovery: http://openid.net/specs/openid-connect-discovery-1_0.html</span></span>
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
            <span data-ttu-id="0eaa8-218">Abrufen oder festlegen die OAuth 2.0-Client-ID, die für die app, die für die Authentifizierung verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-218">Gets or sets the OAuth 2.0 client ID that was created for the app used for authentication.</span></span>
            <span data-ttu-id="0eaa8-219">Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-219">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-220">Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="0eaa8-220">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
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
            <span data-ttu-id="0eaa8-221">Ruft ab oder legt das OAuth 2.0-Client-Geheimnis, das für die app, die für die Authentifizierung verwendet erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-221">Gets or sets the OAuth 2.0 client secret that was created for the app used for authentication.</span></span>
            <span data-ttu-id="0eaa8-222">Diese Einstellung ist zum Aktivieren der Microsoft-Account-Authentifizierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-222">This setting is required for enabling Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-223">Microsoft-Konto-OAuth-Dokumentation: https://dev.onedrive.com/auth/msa_oauth.htm</span><span class="sxs-lookup"><span data-stu-id="0eaa8-223">Microsoft Account OAuth documentation: https://dev.onedrive.com/auth/msa_oauth.htm</span></span>
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
            <span data-ttu-id="0eaa8-224">Abrufen oder Festlegen der OAuth 2.0-Bereiche, die angefordert werden im Rahmen der Microsoft-Account-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-224">Gets or sets the OAuth 2.0 scopes that will be requested as part of Microsoft Account authentication.</span></span>
            <span data-ttu-id="0eaa8-225">Diese Einstellung ist optional.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-225">This setting is optional.</span></span> <span data-ttu-id="0eaa8-226">Wenn nicht angegeben, wird "wl.basic" als den Standardbereich verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-226">If not specified, "wl.basic" is used as the default scope.</span></span>
            <span data-ttu-id="0eaa8-227">Dokumentation zu Microsoft-Konto-Bereiche und Berechtigungen: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span><span class="sxs-lookup"><span data-stu-id="0eaa8-227">Microsoft Account Scopes and permissions documentation: https://msdn.microsoft.com/en-us/library/dn631845.aspx</span></span>
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
            <span data-ttu-id="0eaa8-228">Ruft ab oder legt die RuntimeVersion der Authentifizierung / Autorisierung feature für die aktuelle app verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-228">Gets or sets the RuntimeVersion of the Authentication / Authorization feature in use for the current app.</span></span>
            <span data-ttu-id="0eaa8-229">Die Einstellung in diesem Wert kann kontrollieren des Verhaltens von bestimmten Funktionen in die Authentifizierung / Autorisierung-Modul.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-229">The setting in this value can control the behavior of certain features in the Authentication / Authorization module.</span></span>
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
            <span data-ttu-id="0eaa8-230">Ruft ab oder legt die Anzahl der Stunden nach der tokenablauf Sitzung, die ein Sitzungstoken verwendet werden kann, für die Aktualisierung des Zugriffstokens-API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-230">Gets or sets the number of hours after session token expiration that a session token can be used to call the token refresh API.</span></span> <span data-ttu-id="0eaa8-231">Die Standardeinstellung beträgt 72 Stunden.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-231">The default is 72 hours.</span></span>
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
            <span data-ttu-id="0eaa8-232">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; plattformspezifischen Sicherheitstoken dauerhaft zu speichern, die während der Anmeldung Flüsse abgerufen wurde, andernfalls &amp;Lt; Code&amp;Gt "false" &amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-232">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to durably store platform-specific security tokens that are obtained during login flows; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="0eaa8-233">Die Standardeinstellung ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-233">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
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
            <span data-ttu-id="0eaa8-234">Ruft ab, oder legt den OAuth 1.0a Consumer-Schlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-234">Gets or sets the OAuth 1.0a consumer key of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="0eaa8-235">Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-235">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="0eaa8-236">Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="0eaa8-236">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
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
            <span data-ttu-id="0eaa8-237">Abrufen oder Festlegen der OAuth 1.0a consumerschlüssel der Twitter-Anwendung, die für die Anmeldung verwendet.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-237">Gets or sets the OAuth 1.0a consumer secret of the Twitter application used for sign-in.</span></span>
            <span data-ttu-id="0eaa8-238">Diese Einstellung ist zum Aktivieren von Twitter-Anmeldung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-238">This setting is required for enabling Twitter Sign-In.</span></span>
            <span data-ttu-id="0eaa8-239">Twitter-Anmeldung Dokumentation: https://dev.twitter.com/web/sign-in</span><span class="sxs-lookup"><span data-stu-id="0eaa8-239">Twitter Sign-In documentation: https://dev.twitter.com/web/sign-in</span></span>
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
            <span data-ttu-id="0eaa8-240">Ruft ab oder legt die Aktion an, wenn ein nicht authentifizierter Client versucht, auf die app zugreifen.</span><span class="sxs-lookup"><span data-stu-id="0eaa8-240">Gets or sets the action to take when an unauthenticated client attempts to access the app.</span></span> <span data-ttu-id="0eaa8-241">Folgende Werte sind möglich: "RedirectToLoginPage", "AllowAnonymous"</span><span class="sxs-lookup"><span data-stu-id="0eaa8-241">Possible values include: 'RedirectToLoginPage', 'AllowAnonymous'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>