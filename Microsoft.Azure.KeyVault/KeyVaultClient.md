<Type Name="KeyVaultClient" FullName="Microsoft.Azure.KeyVault.KeyVaultClient">
  <TypeSignature Language="C#" Value="public class KeyVaultClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;, IDisposable, Microsoft.Azure.KeyVault.IKeyVaultClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.KeyVault.KeyVaultClient&gt; implements class Microsoft.Azure.KeyVault.IKeyVaultClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultClient&#xA;Inherits ServiceClient(Of KeyVaultClient)&#xA;Implements IAzureClient, IDisposable, IKeyVaultClient" />
  <TypeSignature Language="F#" Value="type KeyVaultClient = class&#xA;    inherit ServiceClient&lt;KeyVaultClient&gt;&#xA;    interface IKeyVaultClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.KeyVault.KeyVaultClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.KeyVault.IKeyVaultClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f4406-101">Kryptografische Schlüssel Vorgänge und Tresor Vorgänge für die Key Vault-Dienst-Client-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f4406-101">Client class to perform cryptographic key operations and vault operations against the Key Vault service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            <span data-ttu-id="f4406-102">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-102">Optional.</span></span> <span data-ttu-id="f4406-103">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="f4406-103">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-104">Initialisiert eine neue Instanz der KeyVaultClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f4406-104">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="authenticationCallback"><span data-ttu-id="f4406-105">Der authentifizierungsrückruf</span><span class="sxs-lookup"><span data-stu-id="f4406-105">The authentication callback</span></span></param>
        <param name="handlers"><span data-ttu-id="f4406-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-106">Optional.</span></span> <span data-ttu-id="f4406-107">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="f4406-107">The delegating handlers to add to the http client pipeline.</span></span></param>
        <summary>
            <span data-ttu-id="f4406-108">Konstruktor</span><span class="sxs-lookup"><span data-stu-id="f4406-108">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="authenticationCallback"><span data-ttu-id="f4406-109">Der authentifizierungsrückruf</span><span class="sxs-lookup"><span data-stu-id="f4406-109">The authentication callback</span></span></param>
        <param name="httpClient"><span data-ttu-id="f4406-110">Benutzerdefinierten HTTP-client</span><span class="sxs-lookup"><span data-stu-id="f4406-110">Customized HTTP client</span></span> </param>
        <summary>
            <span data-ttu-id="f4406-111">Konstruktor</span><span class="sxs-lookup"><span data-stu-id="f4406-111">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultCredential credential, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultCredential credential, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultCredential,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultCredential * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credential, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="Microsoft.Azure.KeyVault.KeyVaultCredential" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="f4406-112">Anmeldeinformationen für den schlüsseltresor-Vorgänge</span><span class="sxs-lookup"><span data-stu-id="f4406-112">Credential for key vault operations</span></span></param>
        <param name="httpClient"><span data-ttu-id="f4406-113">Benutzerdefinierten HTTP-client</span><span class="sxs-lookup"><span data-stu-id="f4406-113">Customized HTTP client</span></span> </param>
        <summary>
            <span data-ttu-id="f4406-114">Konstruktor</span><span class="sxs-lookup"><span data-stu-id="f4406-114">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="f4406-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-115">Required.</span></span> <span data-ttu-id="f4406-116">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-116">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4406-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-117">Optional.</span></span> <span data-ttu-id="f4406-118">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="f4406-118">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-119">Initialisiert eine neue Instanz der KeyVaultClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f4406-119">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-120">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            <span data-ttu-id="f4406-121">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-121">Optional.</span></span> <span data-ttu-id="f4406-122">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="f4406-122">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4406-123">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-123">Optional.</span></span> <span data-ttu-id="f4406-124">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="f4406-124">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-125">Initialisiert eine neue Instanz der KeyVaultClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f4406-125">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="f4406-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-126">Required.</span></span> <span data-ttu-id="f4406-127">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-127">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="f4406-128">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-128">Optional.</span></span> <span data-ttu-id="f4406-129">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="f4406-129">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="f4406-130">Optional.</span><span class="sxs-lookup"><span data-stu-id="f4406-130">Optional.</span></span> <span data-ttu-id="f4406-131">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="f4406-131">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-132">Initialisiert eine neue Instanz der KeyVaultClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f4406-132">Initializes a new instance of the KeyVaultClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-133">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-134">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="f4406-134">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-135">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="f4406-135">Client API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;&#xA;override this.BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;" Usage="keyVaultClient.BackupKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupKeyWithHttpMessagesAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-136">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-136">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-137">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-137">The name of the key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-138">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-138">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-140">Fordert an, dass eine Sicherung des angegebenen Schlüssels an den Client heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-140">Requests that a backup of the specified key be downloaded to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-141">Der Schlüssel Sicherungsvorgang exportiert einen Schlüssel aus dem Azure-Schlüsseltresor in einer geschützten Form.</span><span class="sxs-lookup"><span data-stu-id="f4406-141">The Key Backup operation exports a key from Azure Key Vault in a protected form.</span></span> <span data-ttu-id="f4406-142">Beachten Sie, dass dieser Vorgang gibt keinen Schlüsselmaterial zurück, in ein Formular, das außerhalb der Azure Key Vault-System verwendet werden kann, das zurückgegebene Schlüsselmaterial ist entweder geschützt ein Azure-Schlüsseltresor-HSM oder Azure Key Vault selbst.</span><span class="sxs-lookup"><span data-stu-id="f4406-142">Note that this operation does NOT return key material in a form that can be used outside the Azure Key Vault system, the returned key material is either protected to a Azure Key Vault HSM or to Azure Key Vault itself.</span></span>
            <span data-ttu-id="f4406-143">Der Zweck dieses Vorgangs ist, kann einen Client einen Schlüssel in einer Instanz von Azure Key Vault, Sichern Sie den Schlüssel generieren und dann in eine andere Azure Key Vault-Instanz wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="f4406-143">The intent of this operation is to allow a client to GENERATE a key in one Azure Key Vault instance, BACKUP the key, and then RESTORE it into another Azure Key Vault instance.</span></span> <span data-ttu-id="f4406-144">Der Sicherungsvorgang kann verwendet werden, in geschützter Form jedes Schlüsseltyps im Azure Key Vault zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-144">The BACKUP operation may be used to export, in protected form, any key type from Azure Key Vault.</span></span> <span data-ttu-id="f4406-145">Einzelne Versionen eines Schlüssels können nicht gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-145">Individual versions of a key cannot be backed up.</span></span> <span data-ttu-id="f4406-146">Sicherung / Wiederherstellung nur; innerhalb geografischer Grenzen ausgeführt werden kann. Dies bedeutet, dass eine Sicherung aus einem geografischen Bereich nicht zu einem anderen geografischen Bereich wiederhergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="f4406-146">BACKUP / RESTORE can be performed within geographical boundaries only; meaning that a BACKUP from one geographical area cannot be restored to another geographical area.</span></span> <span data-ttu-id="f4406-147">Beispielsweise kann eine Sicherung von geografischen Gebiet der USA in einer geografischen Bereich der EU wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-147">For example, a backup from the US geographical area cannot be restored in an EU geographical area.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-148">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-149">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-150">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-150">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-151">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-151">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-152">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-152">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;&#xA;override this.BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;" Usage="keyVaultClient.BackupSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupSecretWithHttpMessagesAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-153">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-153">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-154">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-154">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-155">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-155">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-157">Fordert an, dass eine Sicherung des angegebenen geheimen Schlüssels an den Client heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-157">Requests that a backup of the specified secret be downloaded to the client.</span></span>
            <span data-ttu-id="f4406-158">Autorisierung: ist der geheime Schlüssel/Backup-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-158">Authorization: requires the secrets/backup permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-159">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-160">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-161">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-161">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-162">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-162">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-163">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-163">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.CreateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateCertificateWithHttpMessagesAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-164">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-164">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-165">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-165">The name of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="f4406-166">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="f4406-166">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="f4406-167">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="f4406-167">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-168">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-168">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-169">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-169">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-171">Erstellt ein neues Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="f4406-171">Creates a new certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-172">Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-172">If this is the first version, the certificate resource is created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-173">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-174">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-175">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-175">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-176">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-176">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-177">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-177">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.CreateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, curve, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateKeyWithHttpMessagesAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-178">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-178">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-179">Der Name für den neuen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-179">The name for the new key.</span></span> <span data-ttu-id="f4406-180">Das System generiert den Versionsnamen für den neuen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-180">The system will generate the version name for the new key.</span></span>
            </param>
        <param name="kty">
            <span data-ttu-id="f4406-181">Der Typ des Schlüssels zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="f4406-181">The type of key to create.</span></span> <span data-ttu-id="f4406-182">Gültige Werte finden Sie unter JsonWebKeyType.</span><span class="sxs-lookup"><span data-stu-id="f4406-182">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="f4406-183">Folgende Werte sind möglich: "EC", "EC-HSM", "RSA", "RSA-HSM", "oct"</span><span class="sxs-lookup"><span data-stu-id="f4406-183">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </param>
        <param name="keySize">
            <span data-ttu-id="f4406-184">Die Schlüsselgröße in Bytes.</span><span class="sxs-lookup"><span data-stu-id="f4406-184">The key size in bytes.</span></span> <span data-ttu-id="f4406-185">Z. B. 1024 oder 2048.</span><span class="sxs-lookup"><span data-stu-id="f4406-185">For example, 1024 or 2048.</span></span>
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="f4406-186">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-186">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="curve">
            <span data-ttu-id="f4406-187">Name der Elliptische Kurve.</span><span class="sxs-lookup"><span data-stu-id="f4406-187">Elliptic curve name.</span></span> <span data-ttu-id="f4406-188">Gültige Werte finden Sie unter JsonWebKeyCurveName.</span><span class="sxs-lookup"><span data-stu-id="f4406-188">For valid values, see JsonWebKeyCurveName.</span></span> <span data-ttu-id="f4406-189">Folgende Werte sind möglich: "P-256", "P-384", "P-521", "SECP256K1"</span><span class="sxs-lookup"><span data-stu-id="f4406-189">Possible values include: 'P-256', 'P-384', 'P-521', 'SECP256K1'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-190">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-190">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-192">Erstellt einen neuen Schlüssel, speichert ihn, dann gibt Schlüsselparameter und Attribute an den Client.</span><span class="sxs-lookup"><span data-stu-id="f4406-192">Creates a new key, stores it, then returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-193">Der Erstellvorgang Schlüssel kann zum Erstellen jedes Schlüsseltyps im Azure-Schlüsseltresor verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-193">The create key operation can be used to create any key type in Azure Key Vault.</span></span> <span data-ttu-id="f4406-194">Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-194">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-195">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-195">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-196">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-196">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-197">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-197">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-198">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-198">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-199">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-199">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-200">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-200">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.DecryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DecryptWithHttpMessagesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-201">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-201">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-202">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-202">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-203">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-203">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-204">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="f4406-204">algorithm identifier.</span></span> <span data-ttu-id="f4406-205">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="f4406-205">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-206">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-206">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-208">Entschlüsselt einen einzelnen Block von verschlüsselten Daten.</span><span class="sxs-lookup"><span data-stu-id="f4406-208">Decrypts a single block of encrypted data.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-209">Der DECRYPT-Vorgang entschlüsselt einen wohlgeformten Block mit verschlüsseltem Text transformiert, die mit dem Ziel-Verschlüsselungsschlüssel und angegebenen Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="f4406-209">The DECRYPT operation decrypts a well-formed block of ciphertext using the target encryption key and specified algorithm.</span></span> <span data-ttu-id="f4406-210">Dieser Vorgang ist die Umkehrung des ENCRYPT-Vorgangs; nur ein einzelner Datenblock entschlüsselt werden kann, ist die Größe dieses Blocks vom Zielschlüssel und dem zu verwendenden Algorithmus abhängig.</span><span class="sxs-lookup"><span data-stu-id="f4406-210">This operation is the reverse of the ENCRYPT operation; only a single block of data may be decrypted, the size of this block is dependent on the target key and the algorithm to be used.</span></span> <span data-ttu-id="f4406-211">Der DECRYPT-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="f4406-211">The DECRYPT operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-212">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-213">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-214">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-214">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-215">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-215">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-216">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-216">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateContactsWithHttpMessagesAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-217">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-217">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-218">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-218">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-220">Löscht die Zertifikat-Kontakte für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-220">Deletes the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-221">Löscht die Zertifikat-Kontakte für ein Zertifikat für die angegebene schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-221">Deletes the certificate contacts for a specified key vault certificate.</span></span>
            <span data-ttu-id="f4406-222">Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-222">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-223">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-223">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-224">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-224">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-225">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-225">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-226">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-226">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-227">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-227">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateIssuerWithHttpMessagesAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-228">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-228">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="f4406-229">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="f4406-229">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-230">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-230">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-231">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-232">Löscht den angegebenen Zertifikataussteller an.</span><span class="sxs-lookup"><span data-stu-id="f4406-232">Deletes the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-233">Der Vorgang DeleteCertificateIssuer werden endgültig gelöscht der Aussteller des angegebenen Zertifikats aus dem Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-233">The DeleteCertificateIssuer operation permanently removes the specified certificate issuer from the vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-234">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-235">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-236">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-236">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-237">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-237">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-238">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-238">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateOperationWithHttpMessagesAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-239">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-239">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-240">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-240">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-241">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-241">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-242">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-243">Löscht den Vorgang für ein angegebenes Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="f4406-243">Deletes the operation for a specified certificate.</span></span> <span data-ttu-id="f4406-244">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-244">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-245">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-245">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-246">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-246">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-247">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-247">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-248">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-248">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-249">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-249">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateWithHttpMessagesAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-250">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-250">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-251">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-251">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-252">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-252">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-254">Löscht ein Zertifikat aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-254">Deletes a certificate from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-255">Löscht alle Versionen eines Objekts Zertifikat zusammen mit der zugeordneten Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="f4406-255">Deletes all versions of a certificate object along with its associated policy.</span></span> <span data-ttu-id="f4406-256">Löschen von Zertifikat kann nicht verwendet werden, um einzelne Versionen eines Objekts Zertifikat zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="f4406-256">Delete certificate cannot be used to remove individual versions of a certificate object.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-257">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-258">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-259">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-259">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-260">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-260">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-261">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-261">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.DeleteKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteKeyWithHttpMessagesAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-262">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-262">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-263">Der Name des Schlüssels zu löschen.</span><span class="sxs-lookup"><span data-stu-id="f4406-263">The name of the key to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-264">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-264">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-265">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-266">Löscht einen Schlüssel eines beliebigen Typs aus dem Speicher in Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="f4406-266">Deletes a key of any type from storage in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-267">Der Löschvorgang Schlüssel kann nicht zum Entfernen einzelner Versionen eines Schlüssels verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-267">The delete key operation cannot be used to remove individual versions of a key.</span></span> <span data-ttu-id="f4406-268">Dieser Vorgang entfernt das kryptografische Material, das dem Schlüssel, was bedeutet, dass der Schlüssel nicht für Sign/Verify-, Wrap/Unwrap- oder Encrypt/Decrypt-Vorgänge verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-268">This operation removes the cryptographic material associated with the key, which means the key is not usable for Sign/Verify, Wrap/Unwrap or Encrypt/Decrypt operations.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-269">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-269">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-270">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-270">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-271">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-271">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-272">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-272">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-273">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-273">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSasDefinitionWithHttpMessagesAsync&gt;d__106))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-274">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-274">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-275">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-275">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="f4406-276">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-276">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-277">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-277">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-278">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-279">Löscht eine SAS-Definition aus einem angegebenen Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f4406-279">Deletes a SAS definition from a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-280">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-280">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-281">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-281">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-282">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-282">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-283">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-283">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-284">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-284">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.DeleteSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSecretWithHttpMessagesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-285">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-285">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-286">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-286">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-287">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-287">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-288">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-289">Löscht einen geheimen Schlüssel aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-289">Deletes a secret from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-290">Der DELETE-Vorgang gilt für alle geheimen Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="f4406-290">The DELETE operation applies to any secret stored in Azure Key Vault.</span></span>
            <span data-ttu-id="f4406-291">DELETE kann nicht für eine einzelne Version eines geheimen Schlüssels angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-291">DELETE cannot be applied to an individual version of a secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-292">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-292">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-293">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-293">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-294">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-294">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-295">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-295">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-296">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-296">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.DeleteStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteStorageAccountWithHttpMessagesAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-297">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-297">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-298">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-298">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-299">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-299">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-300">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-300">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-301">Löscht ein Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f4406-301">Deletes a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-302">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-302">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-303">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-303">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-304">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-304">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-305">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-305">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-306">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-306">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-307">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="f4406-307">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.EncryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;EncryptWithHttpMessagesAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-308">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-308">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-309">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-309">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-310">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-310">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-311">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="f4406-311">algorithm identifier.</span></span> <span data-ttu-id="f4406-312">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="f4406-312">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-313">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-313">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-314">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-315">Verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in einem schlüsseltresor gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="f4406-315">Encrypts an arbitrary sequence of bytes using an encryption key that is stored in a key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-316">Der ENCRYPT-Vorgang verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in Azure Key Vault gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-316">The ENCRYPT operation encrypts an arbitrary sequence of bytes using an encryption key that is stored in Azure Key Vault.</span></span> <span data-ttu-id="f4406-317">Beachten Sie, dass der ENCRYPT-Vorgang nur einen einzelnen Block von Daten unterstützt, deren Größe vom Zielschlüssel und den zu verwendenden Verschlüsselungsalgorithmus abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-317">Note that the ENCRYPT operation only supports a single block of data, the size of which is dependent on the target key and the encryption algorithm to be used.</span></span> <span data-ttu-id="f4406-318">Der ENCRYPT-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mithilfe der öffentliche Teil des Schlüssels ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="f4406-318">The ENCRYPT operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using public portion of the key.</span></span> <span data-ttu-id="f4406-319">Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.</span><span class="sxs-lookup"><span data-stu-id="f4406-319">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-320">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-320">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-321">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-321">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-322">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-322">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-323">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-323">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-324">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-324">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-325">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="f4406-325">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="f4406-326">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="f4406-326">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.GetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateContactsWithHttpMessagesAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-327">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-327">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-328">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-328">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-329">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-329">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-330">Listet die Kontakte Zertifikat für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-330">Lists the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-331">Der GetCertificateContacts-Vorgang gibt den Satz von Zertifikat Kontakt Ressourcen im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-331">The GetCertificateContacts operation returns the set of certificate contact resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-332">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-332">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-333">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-333">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-334">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-334">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-335">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-335">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-336">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-336">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersNextWithHttpMessagesAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-337">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-337">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-338">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-338">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-339">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-340">Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-340">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-341">Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-341">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-342">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-342">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-343">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-343">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-344">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-344">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-345">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-345">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-346">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-346">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersWithHttpMessagesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-347">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-347">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-348">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-348">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-349">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-349">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-350">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-350">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-351">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-351">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-352">Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-352">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-353">Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-353">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-354">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-354">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-355">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-355">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-356">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-356">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-357">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-357">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-358">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-358">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuerWithHttpMessagesAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-359">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-359">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="f4406-360">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="f4406-360">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-361">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-361">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-362">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-362">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-363">Listet den Aussteller des angegebenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="f4406-363">Lists the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-364">Der Vorgang GetCertificateIssuer gibt das angegebene Zertifikat Aussteller Ressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-364">The GetCertificateIssuer operation returns the specified certificate issuer resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-365">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-365">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-366">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-366">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-367">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-367">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-368">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-368">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-369">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-369">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.GetCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateOperationWithHttpMessagesAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-370">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-370">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-371">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-371">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-372">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-372">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-373">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-373">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-374">Ruft ein angegebenes Zertifikat zugeordneten Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-374">Gets the operation associated with a specified certificate.</span></span> <span data-ttu-id="f4406-375">Autorisierung: erfordert die Zertifikate/Get-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-375">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-376">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-376">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-377">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-377">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-378">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-378">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-379">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-379">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-380">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-380">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.GetCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatePolicyWithHttpMessagesAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-381">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-381">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-382">Der Name des Zertifikats in einer bestimmten schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-382">The name of the certificate in a given key vault.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-383">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-383">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-384">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-384">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-385">Listet die Richtlinie für ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="f4406-385">Lists the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-386">Der Vorgang GetCertificatePolicy gibt das angegebene Zertifikat Richtlinie Ressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-386">The GetCertificatePolicy operation returns the specified certificate policy resources in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-387">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-387">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-388">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-388">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-389">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-389">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-390">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-390">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-391">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-391">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesNextWithHttpMessagesAsync&gt;d__116))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-392">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-392">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-393">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-393">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-394">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-395">Liste der Zertifikate in einem angegebenen Schlüssel Tresor</span><span class="sxs-lookup"><span data-stu-id="f4406-395">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-396">Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-396">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-397">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-397">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-398">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-398">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-399">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-399">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-400">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-400">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-401">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-401">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesWithHttpMessagesAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-402">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-402">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-403">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-403">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-404">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-404">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-405">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-405">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-406">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-406">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-407">Liste der Zertifikate in einem angegebenen Schlüssel Tresor</span><span class="sxs-lookup"><span data-stu-id="f4406-407">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-408">Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-408">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-409">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-409">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-410">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-410">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-411">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-411">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-412">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-412">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-413">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-413">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsNextWithHttpMessagesAsync&gt;d__118))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-414">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-414">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-415">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-415">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-416">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-416">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-417">Liste der Versionen eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="f4406-417">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-418">Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-418">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-419">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-419">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-420">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-420">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-421">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-421">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-422">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-422">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-423">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-423">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsWithHttpMessagesAsync (vaultBaseUrl, certificateName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsWithHttpMessagesAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-424">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-424">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-425">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-425">The name of the certificate.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-426">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-426">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-427">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-427">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-428">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-428">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-429">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-430">Liste der Versionen eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="f4406-430">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-431">Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="f4406-431">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-432">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-432">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-433">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-433">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-434">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-434">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-435">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-435">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-436">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-436">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateWithHttpMessagesAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-437">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-437">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-438">Der Name des Zertifikats in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-438">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="f4406-439">Die Version des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-439">The version of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-440">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-440">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-441">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-441">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-442">Ruft Informationen zu einem angegebenen Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-442">Gets information about a specified certificate.</span></span> <span data-ttu-id="f4406-443">Autorisierung: erfordert die Zertifikate/Get-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-443">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-444">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-444">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-445">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-445">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-446">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-446">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-447">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-447">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-448">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-448">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesNextWithHttpMessagesAsync&gt;d__119))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-449">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-449">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-450">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-450">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-451">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-452">Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f4406-452">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-453">Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.</span><span class="sxs-lookup"><span data-stu-id="f4406-453">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-454">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-454">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-455">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-455">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-456">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-456">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-457">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-457">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-458">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-458">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesWithHttpMessagesAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-459">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-459">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-460">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-460">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-461">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-461">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-462">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-462">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-463">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-464">Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f4406-464">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-465">Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.</span><span class="sxs-lookup"><span data-stu-id="f4406-465">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-466">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-466">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-467">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-467">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-468">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-468">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-469">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-469">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-470">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-470">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificateWithHttpMessagesAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-471">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-471">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-472">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="f4406-472">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-473">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-473">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-474">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-474">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-475">Ruft Informationen über das angegebene gelöschten Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-475">Retrieves information about the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-476">Mit dem Vorgang GetDeletedCertificate abgerufen, die gelöschte Zertifikatinformationen sowie seiner Attribute, z. B. Aufbewahrungszeitraum, geplante permanent löschen und die aktuelle Ebene der Löschvorgang Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="f4406-476">The GetDeletedCertificate operation retrieves the deleted certificate information plus its attributes, such as retention interval, scheduled permanent deletion and the current deletion recovery level.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-477">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-477">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-478">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-478">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-479">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-479">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-480">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-480">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-481">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-481">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysNextWithHttpMessagesAsync&gt;d__112))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-482">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-482">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-483">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-483">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-484">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-484">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-485">Liste gelöscht Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-485">List deleted keys in the specified vault.</span></span> <span data-ttu-id="f4406-486">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-486">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-487">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-487">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-488">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-488">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-489">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-489">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-490">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-490">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-491">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-491">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysWithHttpMessagesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-492">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-492">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-493">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-493">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-494">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-494">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-495">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-495">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-496">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-496">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-497">Liste gelöscht Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-497">List deleted keys in the specified vault.</span></span> <span data-ttu-id="f4406-498">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-498">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-499">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-499">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-500">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-500">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-501">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-501">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-502">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-502">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-503">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-503">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeyWithHttpMessagesAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-504">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-504">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-505">Der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-505">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-506">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-506">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-507">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-507">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-508">Ruft ab, die gelöschte Schlüsselinformationen sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="f4406-508">Retrieves the deleted key information plus its attributes.</span></span> <span data-ttu-id="f4406-509">Autorisierung: Ist der Schlüssel/Get-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-509">Authorization: Requires the keys/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-510">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-510">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-511">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-511">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-512">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-512">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-513">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-513">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-514">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-514">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsNextWithHttpMessagesAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-515">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-515">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-516">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-516">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-517">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-517">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-518">Liste gelöscht geheime Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-518">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="f4406-519">Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-519">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-520">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-520">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-521">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-521">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-522">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-522">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-523">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-523">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-524">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-524">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsWithHttpMessagesAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-525">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-525">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-526">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-526">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-527">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-527">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-528">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-528">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-529">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-529">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-530">Liste gelöscht geheime Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-530">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="f4406-531">Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-531">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-532">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-532">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-533">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-533">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-534">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-534">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-535">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-535">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-536">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-536">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretWithHttpMessagesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-537">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-537">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-538">Der Name des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-538">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-539">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-539">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-540">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-540">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-541">Ruft ab, die gelöschte geheimen Informationen sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="f4406-541">Retrieves the deleted secret information plus its attributes.</span></span>
            <span data-ttu-id="f4406-542">Autorisierung: ist der geheime Schlüssel/Get-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-542">Authorization: requires the secrets/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-543">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-543">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-544">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-544">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-545">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-545">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-546">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-546">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-547">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-547">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysNextWithHttpMessagesAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-548">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-548">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-549">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-549">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-550">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-550">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-551">Liste von Schlüsseln in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-551">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-552">Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten.</span><span class="sxs-lookup"><span data-stu-id="f4406-552">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="f4406-553">Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-553">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="f4406-554">Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="f4406-554">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="f4406-555">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-555">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-556">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-556">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-557">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-557">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-558">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-558">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-559">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-559">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-560">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-560">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysWithHttpMessagesAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-561">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-561">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-562">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-562">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-563">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-563">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-564">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-564">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-565">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-565">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-566">Liste von Schlüsseln in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-566">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-567">Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten.</span><span class="sxs-lookup"><span data-stu-id="f4406-567">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="f4406-568">Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-568">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="f4406-569">Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="f4406-569">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="f4406-570">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-570">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-571">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-571">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-572">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-572">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-573">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-573">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-574">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-574">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-575">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-575">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsNextWithHttpMessagesAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-576">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-576">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-577">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-577">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-578">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-578">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-579">Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-579">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-580">Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-580">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-581">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-581">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-582">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-582">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-583">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-583">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-584">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-584">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-585">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-585">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync(string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsWithHttpMessagesAsync (vaultBaseUrl, keyName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsWithHttpMessagesAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-586">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-586">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-587">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-587">The name of the key.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-588">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-588">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-589">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-589">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-590">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-590">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-591">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-591">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-592">Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-592">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-593">Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-593">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-594">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-594">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-595">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-595">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-596">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-596">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-597">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-597">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-598">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-598">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.GetKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-599">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-599">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-600">Der Name des abzurufenden Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-600">The name of the key to get.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-601">Hinzufügen der "Version"-Parameter ruft eine bestimmte Version eines Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-601">Adding the version parameter retrieves a specific version of a key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-602">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-602">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-603">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-603">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-604">Ruft den öffentlichen Teil eines gespeicherten Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-604">Gets the public part of a stored key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-605">Die wichtigsten Get-Vorgang gilt zwar für alle Schlüsseltypen.</span><span class="sxs-lookup"><span data-stu-id="f4406-605">The get key operation is applicable to all key types.</span></span> <span data-ttu-id="f4406-606">Wenn es sich bei der angeforderte Schlüssel symmetrisch ist, wird keine Schlüsselmaterial in der Antwort freigegeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-606">If the requested key is symmetric, then no key material is released in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-607">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-607">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-608">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-608">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-609">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-609">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-610">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-610">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-611">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-611">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;&#xA;override this.GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="keyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetPendingCertificateSigningRequestWithHttpMessagesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-612">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</span><span class="sxs-lookup"><span data-stu-id="f4406-612">The vault name, e.g. https://myvault.vault.azure.net</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-613">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="f4406-613">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-614">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-614">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-615">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-615">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-616">Ruft den ausstehenden CSR Anforderungsantwort ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-616">Gets the pending certificate signing request response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="f4406-617">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-617">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsNextWithHttpMessagesAsync&gt;d__121))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-618">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-618">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-619">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-619">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-620">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-620">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-621">Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f4406-621">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-622">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-622">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-623">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-623">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-624">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-624">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-625">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-625">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-626">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-626">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsWithHttpMessagesAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-627">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-627">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-628">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-628">The name of the storage account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-629">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-629">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-630">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-630">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-631">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-631">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-632">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-632">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-633">Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f4406-633">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-634">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-634">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-635">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-635">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-636">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-636">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-637">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-637">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-638">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-638">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionWithHttpMessagesAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-639">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-639">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-640">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-640">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="f4406-641">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-641">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-642">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-642">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-643">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-643">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-644">Ruft Informationen über eine SAS-Definition für das angegebene Speicherkonto ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-644">Gets information about a SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-645">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-645">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-646">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-646">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-647">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-647">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-648">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-648">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-649">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-649">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsNextWithHttpMessagesAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-650">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-650">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-651">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-651">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-652">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-652">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-653">Auflisten geheimer Schlüssel in einer angegebenen Key Vault.</span><span class="sxs-lookup"><span data-stu-id="f4406-653">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-654">Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-654">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="f4406-655">Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="f4406-655">Individual secret versions are not listed in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-656">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-656">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-657">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-657">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-658">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-658">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-659">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-659">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-660">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-660">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsWithHttpMessagesAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-661">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-661">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-662">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-662">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-663">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-663">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-664">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-664">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-665">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-665">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-666">Auflisten geheimer Schlüssel in einer angegebenen Key Vault.</span><span class="sxs-lookup"><span data-stu-id="f4406-666">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-667">Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-667">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="f4406-668">Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="f4406-668">Individual secret versions are not listed in the response.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-669">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-669">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-670">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-670">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-671">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-671">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-672">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-672">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-673">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-673">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsNextWithHttpMessagesAsync&gt;d__114))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-674">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-674">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-675">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-675">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-676">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-676">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-677">Liste der Versionen des angegebenen geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-677">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-678">Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-678">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="f4406-679">Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-679">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="f4406-680">Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="f4406-680">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-681">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-681">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-682">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-682">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-683">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-683">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-684">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-684">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-685">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-685">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync (string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync(string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsWithHttpMessagesAsync (vaultBaseUrl, secretName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsWithHttpMessagesAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-686">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-686">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-687">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-687">The name of the secret.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-688">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-688">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-689">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-689">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-690">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-690">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-691">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-691">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-692">Liste der Versionen des angegebenen geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-692">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-693">Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-693">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="f4406-694">Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-694">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="f4406-695">Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="f4406-695">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-696">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-696">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-697">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-697">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-698">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-698">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-699">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-699">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-700">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-700">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.GetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretWithHttpMessagesAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-701">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-701">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-702">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-702">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="f4406-703">die Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-703">The version of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-704">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-704">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-705">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-705">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-706">Erhalten Sie einen angegebenen Schlüssel aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-706">Get a specified secret from a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-707">Die GET-Vorgang gilt zwar für alle geheimen Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="f4406-707">The GET operation is applicable to any secret stored in Azure Key Vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-708">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-708">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-709">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-709">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-710">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-710">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-711">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-711">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-712">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-712">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsNextWithHttpMessagesAsync&gt;d__120))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f4406-713">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-713">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-714">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-714">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-715">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-715">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-716">Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="f4406-716">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-717">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-717">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-718">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-718">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-719">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-719">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-720">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-720">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-721">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-721">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsWithHttpMessagesAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-722">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-722">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="f4406-723">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-723">Maximum number of results to return in a page.</span></span> <span data-ttu-id="f4406-724">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="f4406-724">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-725">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-725">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-726">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-726">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-727">Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="f4406-727">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-728">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-728">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-729">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-729">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-730">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-730">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-731">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-731">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-732">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-732">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.GetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountWithHttpMessagesAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-733">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-733">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-734">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-734">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-735">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-735">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-736">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-736">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-737">Ruft Informationen über ein angegebenes Speicherkonto ab.</span><span class="sxs-lookup"><span data-stu-id="f4406-737">Gets information about a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-738">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-738">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-739">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-739">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-740">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-740">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-741">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-741">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-742">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-742">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.ImportCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportCertificateWithHttpMessagesAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-743">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-743">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-744">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-744">The name of the certificate.</span></span>
            </param>
        <param name="base64EncodedCertificate">
            <span data-ttu-id="f4406-745">Base64-codierte Darstellung des Objekts Zertifikat zu importieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-745">Base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="f4406-746">Dieses Zertifikat muss den privaten Schlüssel enthalten.</span><span class="sxs-lookup"><span data-stu-id="f4406-746">This certificate needs to contain the private key.</span></span>
            </param>
        <param name="password">
            <span data-ttu-id="f4406-747">Wenn der private Schlüssel im base64EncodedCertificate verschlüsselt ist, können Sie das Kennwort für die Verschlüsselung verwendete.</span><span class="sxs-lookup"><span data-stu-id="f4406-747">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="f4406-748">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="f4406-748">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="f4406-749">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="f4406-749">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-750">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-750">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-751">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-751">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-752">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-752">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-753">Wird ein Zertifikat in einem angegebenen schlüsseltresor importiert.</span><span class="sxs-lookup"><span data-stu-id="f4406-753">Imports a certificate into a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-754">Importiert ein vorhandenes gültiges Zertifikat ist, einen privaten Schlüssel enthält, in Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="f4406-754">Imports an existing valid certificate, containing a private key, into Azure Key Vault.</span></span> <span data-ttu-id="f4406-755">Das Zertifikat importiert werden sollen, kann im PFX oder PEM-Format sein.</span><span class="sxs-lookup"><span data-stu-id="f4406-755">The certificate to be imported can be in either PFX or PEM format.</span></span> <span data-ttu-id="f4406-756">Wenn das Zertifikat im PEM-Format ist muss die PEM-Datei enthalten, den Schlüssel als auch X509 Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="f4406-756">If the certificate is in PEM format the PEM file must contain the key as well as x509 certificates.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-757">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-757">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-758">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-758">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-759">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-759">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-760">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-760">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-761">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-761">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.ImportKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportKeyWithHttpMessagesAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-762">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-762">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-763">Der Name für den importierten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-763">Name for the imported key.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="f4406-764">Das Json Web key</span><span class="sxs-lookup"><span data-stu-id="f4406-764">The Json web key</span></span>
            </param>
        <param name="hsm">
            <span data-ttu-id="f4406-765">Ob als Hardwareschlüssel (HSM) oder Softwareschlüssel zu importieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-765">Whether to import as a hardware key (HSM) or software key.</span></span>
            </param>
        <param name="keyAttributes">
            <span data-ttu-id="f4406-766">Die schlüsselverwaltung-Attribute.</span><span class="sxs-lookup"><span data-stu-id="f4406-766">The key management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-767">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-767">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-768">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-768">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-769">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-769">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-770">Importiert einen extern erstellten Schlüssel, speichert ihn und gibt Schlüsselparameter und Attribute an den Client.</span><span class="sxs-lookup"><span data-stu-id="f4406-770">Imports an externally created key, stores it, and returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-771">Beim Importieren kann verwendet werden, um jedes Schlüsseltyps in Azure Key Vault zu importieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-771">The import key operation may be used to import any key type into an Azure Key Vault.</span></span> <span data-ttu-id="f4406-772">Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-772">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-773">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-773">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-774">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-774">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-775">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-775">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-776">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-776">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-777">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-777">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-778">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f4406-778">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="f4406-779">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="f4406-779">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.MergeCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;MergeCertificateWithHttpMessagesAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-780">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-780">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-781">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-781">The name of the certificate.</span></span>
            </param>
        <param name="x509Certificates">
            <span data-ttu-id="f4406-782">Das Zertifikat oder der Zertifikatskette zum Zusammenführen.</span><span class="sxs-lookup"><span data-stu-id="f4406-782">The certificate or the certificate chain to merge.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="f4406-783">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="f4406-783">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-784">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-784">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-785">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-785">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-786">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-786">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-787">Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.</span><span class="sxs-lookup"><span data-stu-id="f4406-787">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-788">Der Vorgang MergeCertificate führt das Zusammenführen von einem Zertifikat oder der Zertifikatkette mit einem Schlüsselpaar, die zurzeit in den Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f4406-788">The MergeCertificate operation performs the merging of a certificate or certificate chain with a key pair currently available in the service.</span></span>
            <span data-ttu-id="f4406-789">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-789">Authorization: requires the certificates/update permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-790">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-790">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-791">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-791">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-792">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-792">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-793">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-793">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-794">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-794">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedCertificateWithHttpMessagesAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-795">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-795">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-796">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="f4406-796">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-797">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-797">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-798">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-798">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-799">Dauerhaft löscht das angegebene Zertifikat gelöschte.</span><span class="sxs-lookup"><span data-stu-id="f4406-799">Permanently deletes the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-800">Der Vorgang PurgeDeletedCertificate führt eine Löschung des angegebenen Zertifikats, ohne Möglichkeit zur Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="f4406-800">The PurgeDeletedCertificate operation performs an irreversible deletion of the specified certificate, without possibility for recovery.</span></span> <span data-ttu-id="f4406-801">Der Vorgang ist nicht verfügbar, wenn die Wiederherstellung Ebene keine "Purgeable" angibt.</span><span class="sxs-lookup"><span data-stu-id="f4406-801">The operation is not available if the recovery level does not specify 'Purgeable'.</span></span>
            <span data-ttu-id="f4406-802">Erfordert die explizite erteilen der Berechtigung "löschen".</span><span class="sxs-lookup"><span data-stu-id="f4406-802">Requires the explicit granting of the 'purge' permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-803">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-803">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-804">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-804">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-805">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-805">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-806">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-806">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedKeyWithHttpMessagesAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-807">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-807">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-808">Der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-808">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-809">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-809">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-810">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-810">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-811">Dauerhaft löscht den angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-811">Permanently deletes the specified key.</span></span> <span data-ttu-id="f4406-812">d. h. löscht den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-812">aka purges the key.</span></span> <span data-ttu-id="f4406-813">Autorisierung: Ist der Schlüssel/löschen-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-813">Authorization: Requires the keys/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-814">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-814">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-815">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-815">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-816">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-816">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-817">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-817">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedSecretWithHttpMessagesAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-818">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-818">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-819">Der Name des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-819">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-820">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-820">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-821">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-821">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-822">Dauerhaft löscht den angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-822">Permanently deletes the specified secret.</span></span> <span data-ttu-id="f4406-823">AKA löscht den geheimen Schlüssel ein.</span><span class="sxs-lookup"><span data-stu-id="f4406-823">aka purges the secret.</span></span>
            <span data-ttu-id="f4406-824">Autorisierung: ist der geheime Schlüssel/löschen-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-824">Authorization: requires the secrets/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-825">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-825">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-826">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-826">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-827">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-827">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-828">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-828">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedCertificateWithHttpMessagesAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-829">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-829">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-830">Der Name des gelöschten Zertifikats</span><span class="sxs-lookup"><span data-stu-id="f4406-830">The name of the deleted certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-831">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-831">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-832">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-832">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-833">Wird das gelöschte Zertifikat an die aktuelle Version unter Zertifikatinhaber wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-833">Recovers the deleted certificate back to its current version under /certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-834">Die RecoverDeletedCertificate werden die Umkehrung der Löschvorgang durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="f4406-834">The RecoverDeletedCertificate operation performs the reversal of the Delete operation.</span></span> <span data-ttu-id="f4406-835">Der Vorgang gilt in Tresoren, die für die Soft-Delete aktiviert und während das beibehaltungsintervall (verfügbar in der gelöschten Zertifikats Attribute) ausgegeben werden muss.</span><span class="sxs-lookup"><span data-stu-id="f4406-835">The operation is applicable in vaults enabled for soft-delete, and must be issued during the retention interval (available in the deleted certificate's attributes).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-836">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-836">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-837">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-837">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-838">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-838">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-839">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-839">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-840">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-840">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedKeyWithHttpMessagesAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-841">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-841">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-842">Der Name des gelöschten Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-842">The name of the deleted key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-843">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-843">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-844">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-844">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-845">Wird die gelöschten Schlüssel wieder mit ihrer aktuellen Version unter/Keys wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-845">Recovers the deleted key back to its current version under /keys.</span></span>
            <span data-ttu-id="f4406-846">Autorisierung: Ist der Schlüssel/Recover-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-846">Authorization: Requires the keys/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-847">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-847">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-848">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-848">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-849">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-849">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-850">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-850">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-851">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-851">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedSecretWithHttpMessagesAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-852">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-852">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-853">Der Name des gelöschten geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="f4406-853">The name of the deleted secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-854">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-854">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-855">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-855">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-856">Wird die gelöschte geheimen wieder mit ihrer aktuellen Version unter "/ Secrets" wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-856">Recovers the deleted secret back to its current version under /secrets.</span></span>
            <span data-ttu-id="f4406-857">Autorisierung: ist der geheime Schlüssel/Recover-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-857">Authorization: requires the secrets/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-858">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-858">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-859">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-859">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-860">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-860">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-861">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-861">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-862">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-862">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RegenerateStorageAccountKeyWithHttpMessagesAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-863">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-863">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-864">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-864">The name of the storage account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-865">Name des Speicherkontos Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-865">The storage account key name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-866">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-866">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-867">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-867">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-868">Generiert die angegebenen Schlüsselwert für das angegebene Speicherkonto neu.</span><span class="sxs-lookup"><span data-stu-id="f4406-868">Regenerates the specified key value for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-869">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-869">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-870">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-870">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-871">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-871">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-872">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-872">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-873">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-873">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync (string vaultBaseUrl, byte[] keyBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] keyBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RestoreKeyWithHttpMessagesAsync (vaultBaseUrl, keyBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreKeyWithHttpMessagesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-874">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-874">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyBundleBackup">
            <span data-ttu-id="f4406-875">Der Blob-Sicherungsdatei eine wichtige Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f4406-875">The backup blob associated with a key bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-876">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-876">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-877">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-877">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-878">Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.</span><span class="sxs-lookup"><span data-stu-id="f4406-878">Restores a backed up key to a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-879">Importiert einen zuvor gesicherten Schlüssel in Azure Key Vault, den Schlüssel, der den Schlüsselbezeichner, Attribute und Zugriffssteuerungsrichtlinien wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="f4406-879">Imports a previously backed up key into Azure Key Vault, restoring the key, its key identifier, attributes and access control policies.</span></span> <span data-ttu-id="f4406-880">Der Wiederherstellungsvorgang kann verwendet werden, um einen zuvor gesicherten Schlüssel zu importieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-880">The RESTORE operation may be used to import a previously backed up key.</span></span> <span data-ttu-id="f4406-881">Einzelne Versionen eines Schlüssels können nicht wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-881">Individual versions of a key cannot be restored.</span></span> <span data-ttu-id="f4406-882">Der Schlüssel wird in seiner Gesamtheit mit demselben Schlüsselnamen wiederhergestellt, wie er hatte, als er gesichert wurde.</span><span class="sxs-lookup"><span data-stu-id="f4406-882">The key is restored in its entirety with the same key name as it had when it was backed up.</span></span> <span data-ttu-id="f4406-883">Wenn Sie nicht den Namen des Schlüssels im zielschlüsseltresor verfügbar ist, wird der RESTORE-Vorgang abgelehnt.</span><span class="sxs-lookup"><span data-stu-id="f4406-883">If the key name is not available in the target Key Vault, the RESTORE operation will be rejected.</span></span> <span data-ttu-id="f4406-884">Während der Schlüsselname während der Wiederherstellung beibehalten wird, ändert die endgültige Schlüsselbezeichner, wenn der Schlüssel in einem anderen Tresor wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="f4406-884">While the key name is retained during restore, the final key identifier will change if the key is restored to a different vault.</span></span> <span data-ttu-id="f4406-885">Wiederherstellen werden alle Versionen wiederherstellen und erhält die Versionsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="f4406-885">Restore will restore all versions and preserve version identifiers.</span></span> <span data-ttu-id="f4406-886">Der RESTORE-Vorgang unterliegt sicherheitseinschränkungen: das Ziel Key Vault muss wie Key Vault Benutzer RESTORE-Berechtigung im zielschlüsseltresor nicht über die Quelle muss durch den gleichen Microsoft Azure-Abonnement besitzen.</span><span class="sxs-lookup"><span data-stu-id="f4406-886">The RESTORE operation is subject to security constraints: The target Key Vault must be owned by the same Microsoft Azure Subscription as the source Key Vault The user must have RESTORE permission in the target Key Vault.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-887">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-887">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-888">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-888">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-889">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-889">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-890">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-890">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-891">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-891">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync (string vaultBaseUrl, byte[] secretBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] secretBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RestoreSecretWithHttpMessagesAsync (vaultBaseUrl, secretBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreSecretWithHttpMessagesAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-892">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-892">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretBundleBackup">
            <span data-ttu-id="f4406-893">Der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f4406-893">The backup blob associated with a secret bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-894">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-894">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-895">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-895">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-896">Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.</span><span class="sxs-lookup"><span data-stu-id="f4406-896">Restores a backed up secret to a vault.</span></span> <span data-ttu-id="f4406-897">Autorisierung: ist der geheime Schlüssel/Restore-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f4406-897">Authorization: requires the secrets/restore permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-898">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-898">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-899">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-899">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-900">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-900">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-901">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-901">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-902">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-902">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4406-903">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="f4406-903">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.SetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, contacts, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateContactsWithHttpMessagesAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-904">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-904">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="contacts">
            <span data-ttu-id="f4406-905">Die Kontakte für das Zertifikat des Key Vault.</span><span class="sxs-lookup"><span data-stu-id="f4406-905">The contacts for the key vault certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-906">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-906">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-907">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-907">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-908">Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="f4406-908">Sets the certificate contacts for the specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-909">Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="f4406-909">Sets the certificate contacts for the specified key vault.</span></span> <span data-ttu-id="f4406-910">Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-910">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-911">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-911">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-912">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-912">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-913">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-913">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-914">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-914">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-915">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-915">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.SetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateIssuerWithHttpMessagesAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-916">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-916">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="f4406-917">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="f4406-917">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="f4406-918">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="f4406-918">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f4406-919">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f4406-919">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="f4406-920">Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-920">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="f4406-921">Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="f4406-921">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-922">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-922">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-923">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-923">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-924">Legt den angegebenen Zertifikataussteller fest.</span><span class="sxs-lookup"><span data-stu-id="f4406-924">Sets the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-925">Der Vorgang SetCertificateIssuer fügt hinzu oder aktualisiert den Aussteller des angegebenen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-925">The SetCertificateIssuer operation adds or updates the specified certificate issuer.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-926">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-926">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-927">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-927">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-928">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-928">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-929">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-929">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-930">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-930">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.SetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSasDefinitionWithHttpMessagesAsync&gt;d__108))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-931">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-931">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-932">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-932">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="f4406-933">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-933">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f4406-934">SAS-Definition Erstellung Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-934">Sas definition creation metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="f4406-935">Die Attribute der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-935">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-936">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-936">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-937">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-937">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-938">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-938">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-939">Erstellt oder aktualisiert eine neue SAS-Definition für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f4406-939">Creates or updates a new SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-940">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-940">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-941">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-941">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-942">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-942">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-943">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-943">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-944">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-944">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.SetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSecretWithHttpMessagesAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-945">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-945">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-946">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-946">The name of the secret.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="f4406-947">Der Wert des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-947">The value of the secret.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-948">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-948">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="f4406-949">Typ des Werts für den geheimen z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="f4406-949">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="f4406-950">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="f4406-950">The secret management attributes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-951">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-951">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-952">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-952">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-953">Legt einen geheimen Schlüssel in einer angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="f4406-953">Sets a secret in a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-954">Der SET-Vorgang hinzugefügt der Azure-Schlüsseltresor einen geheimer Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-954">The SET operation adds a secret to the Azure Key Vault.</span></span> <span data-ttu-id="f4406-955">Wenn der benannte geheime Schlüssel bereits vorhanden ist, erstellt Azure-Schlüsseltresor eine neue Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-955">If the named secret already exists, Azure Key Vault creates a new version of that secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-956">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-956">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-957">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-957">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-958">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-958">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-959">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-959">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-960">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-960">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.SetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetStorageAccountWithHttpMessagesAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-961">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-961">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-962">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-962">The name of the storage account.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="f4406-963">Ressourcen-Id des Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="f4406-963">Storage account resource id.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="f4406-964">Aktuelle aktive Key Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-964">Current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="f4406-965">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f4406-965">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="f4406-966">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-966">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="f4406-967">Die Attribute des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-967">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-968">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-968">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-969">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-969">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-970">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-970">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-971">Erstellt oder aktualisiert ein neues Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="f4406-971">Creates or updates a new storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-972">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-972">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-973">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-973">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-974">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-974">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-975">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-975">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-976">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-976">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="SignWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.SignWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SignWithHttpMessagesAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-977">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-977">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-978">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-978">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-979">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-979">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-980">Die ID des Signieren/überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f4406-980">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="f4406-981">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="f4406-981">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="f4406-982">Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"</span><span class="sxs-lookup"><span data-stu-id="f4406-982">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-983">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-983">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-984">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-984">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-985">Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-985">Creates a signature from a digest using the specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-986">Die Anmelde-Vorgang gilt zwar für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da dieser Vorgang den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="f4406-986">The SIGN operation is applicable to asymmetric and symmetric keys stored in Azure Key Vault since this operation uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-987">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-987">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-988">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-988">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-989">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-989">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-990">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-990">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-991">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-991">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.UnwrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UnwrapKeyWithHttpMessagesAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-992">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-992">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-993">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-993">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-994">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-994">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-995">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="f4406-995">algorithm identifier.</span></span> <span data-ttu-id="f4406-996">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="f4406-996">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-997">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-997">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-998">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-998">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-999">Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel, der ursprünglich für diesen Schlüssel wrapping verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="f4406-999">Unwraps a symmetric key using the specified key that was initially used for wrapping that key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1000">Die UNWRAP-Vorgang unterstützt die Entschlüsselung eines symmetrischen Schlüssels mit dem Zielschlüssel für die Schlüsselverschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1000">The UNWRAP operation supports decryption of a symmetric key using the target key encryption key.</span></span> <span data-ttu-id="f4406-1001">Dieser Vorgang ist die Umkehrung des WRAP-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f4406-1001">This operation is the reverse of the WRAP operation.</span></span> <span data-ttu-id="f4406-1002">Der UNWRAP-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="f4406-1002">The UNWRAP operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1003">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1003">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1004">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1004">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1005">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1005">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1006">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1006">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1007">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1007">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateIssuerWithHttpMessagesAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1008">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1008">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="f4406-1009">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="f4406-1009">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="f4406-1010">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="f4406-1010">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="f4406-1011">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f4406-1011">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="f4406-1012">Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-1012">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="f4406-1013">Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="f4406-1013">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1014">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1014">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1015">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1015">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1016">Aktualisiert den Aussteller des angegebenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="f4406-1016">Updates the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1017">Der UpdateCertificateIssuer-Vorgang führt ein Update für das angegebene Zertifikat Aussteller-Entität.</span><span class="sxs-lookup"><span data-stu-id="f4406-1017">The UpdateCertificateIssuer operation performs an update on the specified certificate issuer entity.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1018">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1018">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1019">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1019">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1020">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1020">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1021">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1021">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1022">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1022">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, bool cancellationRequested, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, cancellationRequested, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateOperationWithHttpMessagesAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1023">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1023">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-1024">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-1024">The name of the certificate.</span></span>
            </param>
        <param name="cancellationRequested">
            <span data-ttu-id="f4406-1025">Gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.</span><span class="sxs-lookup"><span data-stu-id="f4406-1025">Indicates if cancellation was requested on the certificate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1026">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1026">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1027">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1027">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1028">Aktualisiert einen Zertifikat-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f4406-1028">Updates a certificate operation.</span></span> <span data-ttu-id="f4406-1029">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1029">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1030">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1030">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1031">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1031">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1032">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1032">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1033">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1033">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1034">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1034">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificatePolicyWithHttpMessagesAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1035">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1035">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-1036">Der Name des Zertifikats in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-1036">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="f4406-1037">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1037">The policy for the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1038">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1038">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1039">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1039">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1040">Aktualisiert die Richtlinie für ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="f4406-1040">Updates the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1041">Festzulegen Sie angegebene Member in der Zertifikatrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="f4406-1041">Set specified members in the certificate policy.</span></span> <span data-ttu-id="f4406-1042">Belassen Sie andere als Null.</span><span class="sxs-lookup"><span data-stu-id="f4406-1042">Leave others as null.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1043">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1043">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1044">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1044">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1045">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1045">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1046">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1046">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1047">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1047">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateWithHttpMessagesAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1048">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1048">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="f4406-1049">Der Name des Zertifikats im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="f4406-1049">The name of the certificate in the given key vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="f4406-1050">Die Version des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="f4406-1050">The version of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="f4406-1051">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1051">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="f4406-1052">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="f4406-1052">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-1053">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1053">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1054">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1054">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1055">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1055">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1056">Aktualisiert die angegebenen Attribute, die dem angegebenen Zertifikat zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f4406-1056">Updates the specified attributes associated with the given certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1057">Der UpdateCertificate-Vorgang gilt das Update für das angegebene Zertifikat; Beachten Sie, dass die einzigen Elemente, die aktualisiert wird das Zertifikat Attribute sind.</span><span class="sxs-lookup"><span data-stu-id="f4406-1057">The UpdateCertificate operation applies the specified update on the given certificate; note the only elements being updated are the certificate's attributes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1058">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1058">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1059">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1059">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1060">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1060">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1061">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1061">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1062">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1062">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.UpdateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateKeyWithHttpMessagesAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1063">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1063">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-1064">Der Name der zu aktualisierende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f4406-1064">The name of key to update.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-1065">Die Version des Schlüssels zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1065">The version of the key to update.</span></span>
            </param>
        <param name="keyOps">
            <span data-ttu-id="f4406-1066">JSON Web Key-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="f4406-1066">Json web key operations.</span></span> <span data-ttu-id="f4406-1067">Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.</span><span class="sxs-lookup"><span data-stu-id="f4406-1067">For more information on possible key operations, see JsonWebKeyOperation.</span></span>
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="f4406-1068">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1068">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1069">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1069">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1070">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1070">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1071">Die Änderungen am Update Schlüsselvorgang angegebene Attribute eines gespeicherten Schlüssels und können auf alle Schlüsseltypen und Schlüssel in Azure Key Vault gespeicherten Version angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-1071">The update key operation changes specified attributes of a stored key and can be applied to any key type and key version stored in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1072">Um diesen Vorgang auszuführen, muss der Schlüssel bereits im Schlüsseltresor vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="f4406-1072">In order to perform this operation, the key must already exist in the Key Vault.</span></span> <span data-ttu-id="f4406-1073">Hinweis: Das kryptografische Material eines Schlüssels selbst kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-1073">Note: The cryptographic material of a key itself cannot be changed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1074">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1074">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1075">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1075">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1076">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1076">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1077">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1077">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1078">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1078">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSasDefinitionWithHttpMessagesAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1079">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1079">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-1080">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-1080">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="f4406-1081">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-1081">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f4406-1082">SAS-definitionsaktualisierung Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1082">Sas definition update metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="f4406-1083">Die Attribute der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="f4406-1083">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-1084">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1084">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1085">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1085">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1086">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1086">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1087">Aktualisiert die angegebenen Attribute der bestimmten SAS-Definition zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f4406-1087">Updates the specified attributes associated with the given SAS definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1088">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1088">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1089">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1089">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1090">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1090">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1091">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1091">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1092">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1092">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.UpdateSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSecretWithHttpMessagesAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1093">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1093">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="f4406-1094">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1094">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="f4406-1095">die Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1095">The version of the secret.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="f4406-1096">Typ des Werts für den geheimen z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="f4406-1096">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="f4406-1097">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="f4406-1097">The secret management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-1098">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1098">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1099">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1099">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1100">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1100">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1101">Aktualisiert die Attribute, die mit einem angegebenen Schlüssel in einem angegebenen Schlüssel Tresor verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="f4406-1101">Updates the attributes associated with a specified secret in a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1102">Der UPDATE-Vorgang ändert angegebene Attribute einer vorhandenen gespeicherten, geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1102">The UPDATE operation changes specified attributes of an existing stored secret.</span></span> <span data-ttu-id="f4406-1103">Attribute, die nicht in der Anforderung angegeben werden bleiben unverändert.</span><span class="sxs-lookup"><span data-stu-id="f4406-1103">Attributes that are not specified in the request are left unchanged.</span></span> <span data-ttu-id="f4406-1104">Der Wert eines geheimen Schlüssels selbst kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="f4406-1104">The value of a secret itself cannot be changed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1105">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1105">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1106">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1106">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1107">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1107">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1108">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1108">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1109">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1109">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.UpdateStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateStorageAccountWithHttpMessagesAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1110">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1110">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="f4406-1111">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-1111">The name of the storage account.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="f4406-1112">Der aktuellen aktiven Schlüssel speicherkontoname.</span><span class="sxs-lookup"><span data-stu-id="f4406-1112">The current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="f4406-1113">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f4406-1113">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="f4406-1114">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="f4406-1114">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="f4406-1115">Die Attribute des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="f4406-1115">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="f4406-1116">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1116">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1117">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1117">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1119">Aktualisiert die angegebenen Attributen, die das angegebene Speicherkonto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f4406-1119">Updates the specified attributes associated with the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1120">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1121">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1122">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1122">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1123">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1123">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1124">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1124">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;&#xA;override this.VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;" Usage="keyVaultClient.VerifyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;VerifyWithHttpMessagesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1125">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1125">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-1126">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1126">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-1127">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1127">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-1128">Der Algorithmus Signieren/überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f4406-1128">The signing/verification algorithm.</span></span> <span data-ttu-id="f4406-1129">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="f4406-1129">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="f4406-1130">Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"</span><span class="sxs-lookup"><span data-stu-id="f4406-1130">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="digest">
            <span data-ttu-id="f4406-1131">Den Hashwert, der zum Signieren verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="f4406-1131">The digest used for signing.</span></span>
            </param>
        <param name="signature">
            <span data-ttu-id="f4406-1132">Die zu überprüfende Signatur.</span><span class="sxs-lookup"><span data-stu-id="f4406-1132">The signature to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1133">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1133">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1135">Überprüft eine Signatur, die mithilfe eines angegebenen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1135">Verifies a signature using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1136">Die VERIFY-Vorgang gilt zwar für symmetrische Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="f4406-1136">The VERIFY operation is applicable to symmetric keys stored in Azure Key Vault.</span></span> <span data-ttu-id="f4406-1137">Überprüfen Sie, ob ist nicht unbedingt erforderlich für asymmetrische Schlüssel im Azure-Schlüsseltresor gespeichert sind, da die signaturüberprüfung kann mit dem öffentlichen Teil des Schlüssels ausgeführt werden, aber dieser Vorgang wird als Annehmlichkeit unterstützt, für den Aufrufer, die nur einen Schlüssel-Verweis und nicht die öffentliche Teil des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1137">VERIFY is not strictly necessary for asymmetric keys stored in Azure Key Vault since signature verification can be performed using the public portion of the key but this operation is supported as a convenience for callers that only have a key-reference and not the public portion of the key.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1138">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1139">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1140">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1140">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1141">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1141">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1142">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1142">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.WrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;WrapKeyWithHttpMessagesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="f4406-1143">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="f4406-1143">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="f4406-1144">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1144">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="f4406-1145">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1145">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="f4406-1146">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="f4406-1146">algorithm identifier.</span></span> <span data-ttu-id="f4406-1147">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="f4406-1147">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="f4406-1148">Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="f4406-1148">Headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f4406-1149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f4406-1149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f4406-1150">Umschließt einen symmetrischen Schlüssel mithilfe eines angegebenen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f4406-1150">Wraps a symmetric key using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f4406-1151">Der WRAP-Vorgang unterstützt die Verschlüsselung eines symmetrischen Schlüssels mit einem schlüsselverschlüsselungsschlüssel, der zuvor in einem Azure-Schlüsseltresor gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="f4406-1151">The WRAP operation supports encryption of a symmetric key using a key encryption key that has previously been stored in an Azure Key Vault.</span></span> <span data-ttu-id="f4406-1152">Der WRAP-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mit dem öffentlichen Teil des Schlüssels ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="f4406-1152">The WRAP operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using the public portion of the key.</span></span> <span data-ttu-id="f4406-1153">Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.</span><span class="sxs-lookup"><span data-stu-id="f4406-1153">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            <span data-ttu-id="f4406-1154">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="f4406-1154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f4406-1155">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="f4406-1155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4406-1156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1156">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="f4406-1157">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="f4406-1157">Thrown when a required parameter is null</span></span>
            </exception>
        <return>
            <span data-ttu-id="f4406-1158">Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.</span><span class="sxs-lookup"><span data-stu-id="f4406-1158">A response object containing the response body and response headers.</span></span>
            </return>
      </Docs>
    </Member>
  </Members>
</Type>