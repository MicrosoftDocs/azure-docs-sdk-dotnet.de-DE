<Type Name="ConfidentialClientApplication" FullName="Microsoft.Identity.Client.ConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public sealed class ConfidentialClientApplication : Microsoft.Identity.Client.ClientApplicationBase, Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfidentialClientApplication extends Microsoft.Identity.Client.ClientApplicationBase implements class Microsoft.Identity.Client.IClientApplicationBase, class Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfidentialClientApplication&#xA;Inherits ClientApplicationBase&#xA;Implements IConfidentialClientApplication" />
  <TypeSignature Language="F#" Value="type ConfidentialClientApplication = class&#xA;    inherit ClientApplicationBase&#xA;    interface IConfidentialClientApplication&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.ClientApplicationBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IConfidentialClientApplication</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="12364-101">Die Klasse für vertrauliche Clientanwendungen wie Web Apps /-API verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="12364-101">Class to be used for confidential client applications like Web Apps/API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="12364-102">Client-Id der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-102">Client Id of the application.</span></span> <span data-ttu-id="12364-103">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-103">REQUIRED.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="12364-104">Umleitungs-URI der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-104">Redirect URI of the application.</span></span> <span data-ttu-id="12364-105">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-105">REQUIRED.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="12364-106">Clientanmeldeinformationen für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-106">Client credential for the application.</span></span> <span data-ttu-id="12364-107">Ein Zertifikat oder einen geheimen Schlüssel kann sein.</span><span class="sxs-lookup"><span data-stu-id="12364-107">Could be a certificate or a secret.</span></span> <span data-ttu-id="12364-108">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-108">REQUIRED.</span></span></param>
        <param name="userTokenCache"><span data-ttu-id="12364-109">Tokencache zum Speichern von Benutzertoken.</span><span class="sxs-lookup"><span data-stu-id="12364-109">Token cache for saving user tokens.</span></span> <span data-ttu-id="12364-110">OPTIONAL.</span><span class="sxs-lookup"><span data-stu-id="12364-110">OPTIONAL.</span></span></param>
        <param name="appTokenCache"><span data-ttu-id="12364-111">Tokencache zum Speichern von Anwendungsclient /-Token.</span><span class="sxs-lookup"><span data-stu-id="12364-111">Token cache for saving application/client tokens.</span></span> <span data-ttu-id="12364-112">OPTIONAL.</span><span class="sxs-lookup"><span data-stu-id="12364-112">OPTIONAL.</span></span></param>
        <summary>
            <span data-ttu-id="12364-113">Konstruktor zum Erstellen der Instanz der Klasse</span><span class="sxs-lookup"><span data-stu-id="12364-113">Constructor to create instance of the class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string authority, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, authority, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="12364-114">Client-Id der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-114">Client Id of the application.</span></span> <span data-ttu-id="12364-115">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-115">REQUIRED.</span></span></param>
        <param name="authority"><span data-ttu-id="12364-116">Autorität für die Clientanwendung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="12364-116">Authority to be used for the client application.</span></span> <span data-ttu-id="12364-117">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-117">REQUIRED.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="12364-118">Umleitungs-URI der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-118">Redirect URI of the application.</span></span> <span data-ttu-id="12364-119">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-119">REQUIRED.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="12364-120">Clientanmeldeinformationen für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="12364-120">Client credential for the application.</span></span> <span data-ttu-id="12364-121">Ein Zertifikat oder einen geheimen Schlüssel kann sein.</span><span class="sxs-lookup"><span data-stu-id="12364-121">Could be a certificate or a secret.</span></span> <span data-ttu-id="12364-122">REQUIRED. (ERFORDERLICH.)</span><span class="sxs-lookup"><span data-stu-id="12364-122">REQUIRED.</span></span></param>
        <param name="userTokenCache"><span data-ttu-id="12364-123">Tokencache zum Speichern von Benutzertoken.</span><span class="sxs-lookup"><span data-stu-id="12364-123">Token cache for saving user tokens.</span></span> <span data-ttu-id="12364-124">OPTIONAL.</span><span class="sxs-lookup"><span data-stu-id="12364-124">OPTIONAL.</span></span></param>
        <param name="appTokenCache"><span data-ttu-id="12364-125">Tokencache zum Speichern von Anwendungsclient /-Token.</span><span class="sxs-lookup"><span data-stu-id="12364-125">Token cache for saving application/client tokens.</span></span> <span data-ttu-id="12364-126">OPTIONAL.</span><span class="sxs-lookup"><span data-stu-id="12364-126">OPTIONAL.</span></span></param>
        <summary>
            <span data-ttu-id="12364-127">Konstruktor zum Erstellen der Instanz der Klasse</span><span class="sxs-lookup"><span data-stu-id="12364-127">Constructor to create instance of the class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationCode"><span data-ttu-id="12364-128">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</span><span class="sxs-lookup"><span data-stu-id="12364-128">The authorization code received from service authorization endpoint.</span></span></param>
        <param name="scopes"><span data-ttu-id="12364-129">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-129">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="12364-130">Ruft den Sicherheitstoken von der Zertifizierungsstelle mithilfe des Autorisierungscodes zuvor empfangen.</span><span class="sxs-lookup"><span data-stu-id="12364-130">Acquires security token from the authority using authorization code previously received.</span></span>
            <span data-ttu-id="12364-131">Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />.</span><span class="sxs-lookup"><span data-stu-id="12364-131">This method does not lookup token cache, but stores the result in it, so it can be looked up using other methods such as <see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-132">Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</span><span class="sxs-lookup"><span data-stu-id="12364-132">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync scopes" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-133">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-133">Array of scopes requested for resource</span></span></param>
        <summary>
            <span data-ttu-id="12364-134">Ruft die Token vom Dienst für den vertraulichen Client ab.</span><span class="sxs-lookup"><span data-stu-id="12364-134">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="12364-135">Diese Methode versucht, gültige Zugriffstoken im Cache nachzuschlagen.</span><span class="sxs-lookup"><span data-stu-id="12364-135">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-136">Authentifizierungsergebnis anwendungstoken für die angeforderten Bereiche mit</span><span class="sxs-lookup"><span data-stu-id="12364-136">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-137">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-137">Array of scopes requested for resource</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="12364-138">Bei "true", API ignoriert das Zugriffstoken im Cache und versucht, neue Clientanmeldeinformationen mit Zugriffstoken zu erhalten</span><span class="sxs-lookup"><span data-stu-id="12364-138">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using client credentials</span></span></param>
        <summary>
            <span data-ttu-id="12364-139">Ruft die Token vom Dienst für den vertraulichen Client ab.</span><span class="sxs-lookup"><span data-stu-id="12364-139">Acquires token from the service for the confidential client.</span></span> <span data-ttu-id="12364-140">Diese Methode versucht, gültige Zugriffstoken im Cache nachzuschlagen.</span><span class="sxs-lookup"><span data-stu-id="12364-140">This method attempts to look up valid access token in the cache.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-141">Authentifizierungsergebnis anwendungstoken für die angeforderten Bereiche mit</span><span class="sxs-lookup"><span data-stu-id="12364-141">Authentication result containing application token for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-142">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-142">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="12364-143">In der Instanz von UserAssertion enthält Benutzer werden token.</span><span class="sxs-lookup"><span data-stu-id="12364-143">Instance of UserAssertion containing user's token.</span></span></param>
        <summary>
            <span data-ttu-id="12364-144">Ruft mithilfe der On-Behalf-Of-Flow-token.</span><span class="sxs-lookup"><span data-stu-id="12364-144">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-145">Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</span><span class="sxs-lookup"><span data-stu-id="12364-145">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-146">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-146">Array of scopes requested for resource</span></span></param>
        <param name="userAssertion"><span data-ttu-id="12364-147">In der Instanz von UserAssertion enthält Benutzer werden token.</span><span class="sxs-lookup"><span data-stu-id="12364-147">Instance of UserAssertion containing user's token.</span></span></param>
        <param name="authority"><span data-ttu-id="12364-148">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="12364-148">Specific authority for which the token is requested.</span></span> <span data-ttu-id="12364-149">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="12364-149">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="12364-150">Ruft mithilfe der On-Behalf-Of-Flow-token.</span><span class="sxs-lookup"><span data-stu-id="12364-150">Acquires token using On-Behalf-Of flow.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-151">Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</span><span class="sxs-lookup"><span data-stu-id="12364-151">Authentication result containing token of the user for the requested scopes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-152">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-152">Array of scopes requested for resource</span></span></param>
        <param name="loginHint"><span data-ttu-id="12364-153">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="12364-153">Identifier of the user.</span></span> <span data-ttu-id="12364-154">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="12364-154">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="12364-155">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="12364-155">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="12364-156">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="12364-156">The parameter can be null.</span></span></param>
        <summary>
            <span data-ttu-id="12364-157">URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.</span><span class="sxs-lookup"><span data-stu-id="12364-157">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-158">URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="12364-158">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="12364-159">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="12364-159">Array of scopes requested for resource</span></span></param>
        <param name="redirectUri"><span data-ttu-id="12364-160">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</span><span class="sxs-lookup"><span data-stu-id="12364-160">Address to return to upon receiving a response from the authority.</span></span></param>
        <param name="loginHint"><span data-ttu-id="12364-161">Der Bezeichner des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="12364-161">Identifier of the user.</span></span> <span data-ttu-id="12364-162">Im Allgemeinen einen UPN.</span><span class="sxs-lookup"><span data-stu-id="12364-162">Generally a UPN.</span></span></param>
        <param name="extraQueryParameters"><span data-ttu-id="12364-163">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt.</span><span class="sxs-lookup"><span data-stu-id="12364-163">This parameter will be appended as is to the query string in the HTTP authentication request to the authority.</span></span> <span data-ttu-id="12364-164">Der Parameter kann null sein.</span><span class="sxs-lookup"><span data-stu-id="12364-164">The parameter can be null.</span></span></param>
        <param name="extraScopesToConsent"><span data-ttu-id="12364-165">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</span><span class="sxs-lookup"><span data-stu-id="12364-165">Array of scopes for which a developer can request consent upfront.</span></span></param>
        <param name="authority"><span data-ttu-id="12364-166">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="12364-166">Specific authority for which the token is requested.</span></span> <span data-ttu-id="12364-167">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="12364-167">Passing a different value than configured does not change the configured value</span></span></param>
        <summary>
            <span data-ttu-id="12364-168">URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.</span><span class="sxs-lookup"><span data-stu-id="12364-168">Gets URL of the authorize endpoint including the query parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="12364-169">URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="12364-169">URL of the authorize endpoint including the query parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>