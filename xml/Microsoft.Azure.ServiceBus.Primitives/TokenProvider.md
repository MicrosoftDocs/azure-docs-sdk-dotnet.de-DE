<Type Name="TokenProvider" FullName="Microsoft.Azure.ServiceBus.Primitives.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider : Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object implements class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider&#xA;Implements ITokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class&#xA;    interface ITokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Primitives.ITokenProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a8886-101">Dieser abstrakten Basisklasse kann erweitert werden, um zusätzliche Tokenanbieter zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="a8886-101">This abstract base class can be extended to implement additional token providers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientAssertionCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="a8886-102">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="a8886-102">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="a8886-103">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="a8886-103">The client assertion certificate credential.</span></span></param>
        <summary><span data-ttu-id="a8886-104">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="a8886-104">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="a8886-105">Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="a8886-105">The <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="a8886-106">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="a8886-106">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="a8886-107">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="a8886-107">The app credential.</span></span></param>
        <summary><span data-ttu-id="a8886-108">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="a8886-108">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="a8886-109">Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="a8886-109">The <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, userIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="a8886-110">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="a8886-110">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="a8886-111">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="a8886-111">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="a8886-112">Die RedirectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="a8886-112">The redirectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="a8886-113">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="a8886-113">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="a8886-114">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="a8886-114">User Identifier</span></span></param>
        <summary><span data-ttu-id="a8886-115">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="a8886-115">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="a8886-116">Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="a8886-116">The <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateManagedServiceIdentityTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateManagedServiceIdentityTokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateManagedServiceIdentityTokenProvider() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateManagedServiceIdentityTokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateManagedServiceIdentityTokenProvider () As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateManagedServiceIdentityTokenProvider : unit -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateManagedServiceIdentityTokenProvider " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a8886-117">Erstellt Azure verwaltet Dienstidentität-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="a8886-117">Creates Azure Managed Service Identity token provider.</span></span></summary>
        <returns><span data-ttu-id="a8886-118">Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="a8886-118">The <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="a8886-119">Die SAS</span><span class="sxs-lookup"><span data-stu-id="a8886-119">The shared access signature</span></span></param>
        <summary>
            <span data-ttu-id="a8886-120">Erstellen Sie einen TokenProvider dar, die basierend auf einer SharedAccessSignature.</span><span class="sxs-lookup"><span data-stu-id="a8886-120">Construct a TokenProvider based on a sharedAccessSignature.</span></span>
            </summary>
        <returns><span data-ttu-id="a8886-121">Einen TokenProvider dar, die mit der freigegebenen zugriffssignatur initialisiert</span><span class="sxs-lookup"><span data-stu-id="a8886-121">A TokenProvider initialized with the shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="a8886-122">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="a8886-122">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="a8886-123">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</span><span class="sxs-lookup"><span data-stu-id="a8886-123">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <summary>
            <span data-ttu-id="a8886-124">Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="a8886-124">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="a8886-125">Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</span><span class="sxs-lookup"><span data-stu-id="a8886-125">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.Azure.ServiceBus.Primitives.TokenScope -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.ServiceBus.Primitives.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="a8886-126">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="a8886-126">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="a8886-127">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</span><span class="sxs-lookup"><span data-stu-id="a8886-127">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenScope"><span data-ttu-id="a8886-128">Die TokenScope Token anfordern.</span><span class="sxs-lookup"><span data-stu-id="a8886-128">The tokenScope of tokens to request.</span></span></param>
        <summary>
            <span data-ttu-id="a8886-129">Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="a8886-129">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="a8886-130">Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</span><span class="sxs-lookup"><span data-stu-id="a8886-130">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="a8886-131">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="a8886-131">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="a8886-132">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</span><span class="sxs-lookup"><span data-stu-id="a8886-132">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="a8886-133">Die token Zeit Gültigkeitsdauer</span><span class="sxs-lookup"><span data-stu-id="a8886-133">The token time to live</span></span></param>
        <summary>
            <span data-ttu-id="a8886-134">Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="a8886-134">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="a8886-135">Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</span><span class="sxs-lookup"><span data-stu-id="a8886-135">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.Azure.ServiceBus.Primitives.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.Azure.ServiceBus.Primitives.TokenScope -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.ServiceBus.Primitives.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="a8886-136">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="a8886-136">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="a8886-137">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</span><span class="sxs-lookup"><span data-stu-id="a8886-137">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="a8886-138">Die token Zeit Gültigkeitsdauer</span><span class="sxs-lookup"><span data-stu-id="a8886-138">The token time to live</span></span></param>
        <param name="tokenScope"><span data-ttu-id="a8886-139">Die TokenScope Token anfordern.</span><span class="sxs-lookup"><span data-stu-id="a8886-139">The tokenScope of tokens to request.</span></span></param>
        <summary>
            <span data-ttu-id="a8886-140">Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="a8886-140">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="a8886-141">Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</span><span class="sxs-lookup"><span data-stu-id="a8886-141">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Primitives.ITokenProvider.GetTokenAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="a8886-142">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="a8886-142">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="a8886-143">Die Zeitspanne an, die angibt, den Timeoutwert für die Nachricht abruft, die das Sicherheitstoken</span><span class="sxs-lookup"><span data-stu-id="a8886-143">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="a8886-144">Ruft eine <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> für die angegebene Zielgruppe und die Dauer.</span><span class="sxs-lookup"><span data-stu-id="a8886-144">Gets a <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>