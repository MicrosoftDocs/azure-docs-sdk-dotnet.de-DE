<Type Name="TokenProvider" FullName="Microsoft.ServiceBus.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="39c32-101">Stellt einen Sicherheitstokenanbieter mit integrierten Factorymethoden, die einige bekannten Tokenanbieter zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="39c32-101">Represents a security token provider with built-in factory methods returning some well-known token providers.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (cacheTokens As Boolean, supportHttpAuthToken As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="39c32-102">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-102">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="39c32-103">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-103">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="39c32-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.TokenProvider" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="39c32-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="39c32-105">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-105">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="39c32-106">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-106">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-107">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-107">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.TokenProvider" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="39c32-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider (bool cacheTokens, bool supportHttpAuthToken, int cacheSize, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool cacheTokens, bool supportHttpAuthToken, int32 cacheSize, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.#ctor(System.Boolean,System.Boolean,System.Int32,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider : bool * bool * int * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="new Microsoft.ServiceBus.TokenProvider (cacheTokens, supportHttpAuthToken, cacheSize, tokenScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cacheTokens" Type="System.Boolean" />
        <Parameter Name="supportHttpAuthToken" Type="System.Boolean" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="cacheTokens"><span data-ttu-id="39c32-109">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-109">true if new security tokens are being cached; otherwise, false.</span></span></param>
        <param name="supportHttpAuthToken"><span data-ttu-id="39c32-110">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-110">true if web token is supported by this provider; otherwise, false.</span></span></param>
        <param name="cacheSize"><span data-ttu-id="39c32-111">Die Größe des Caches.</span><span class="sxs-lookup"><span data-stu-id="39c32-111">The size of the cache.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-112">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-112">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-113">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.TokenProvider" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="39c32-113">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TokenProvider" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BeginGetToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-114">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-114">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-115">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-115">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="39c32-116">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="39c32-116">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-117">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-117">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="39c32-118">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="39c32-118">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="39c32-119">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="39c32-119">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="39c32-120">Startet einen asynchronen Vorgang, um ein Sicherheitstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="39c32-120">Begins an asynchronous operation to get a security token.</span></span></summary>
        <returns><span data-ttu-id="39c32-121">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-121">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetWebToken">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetWebToken (string appliesTo, string action, bool bypassCache, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetWebToken(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BeginGetWebToken(System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetWebToken (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetWebToken : string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.BeginGetWebToken (appliesTo, action, bypassCache, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-122">Der URI, der das Token gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-122">The URI which the token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-123">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-123">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="39c32-124">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="39c32-124">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-125">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-125">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="39c32-126">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="39c32-126">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="39c32-127">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="39c32-127">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="39c32-128">Startet einen asynchronen Vorgang zum Abrufen einer webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-128">Begins an asynchronous operation to get a web token.</span></span></summary>
        <returns><span data-ttu-id="39c32-129">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-129">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="abstract member BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key&#xA;override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="tokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-130">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-130">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-131">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-131">The request action.</span></span></param>
        <summary><span data-ttu-id="39c32-132">Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-132">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-133">Ein generierter Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-133">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheSize">
      <MemberSignature Language="C#" Value="public int CacheSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CacheSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.CacheSize" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheSize As Integer" />
      <MemberSignature Language="F#" Value="member this.CacheSize : int with get, set" Usage="Microsoft.ServiceBus.TokenProvider.CacheSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39c32-134">Ruft ab oder legt die Größe des Caches.</span><span class="sxs-lookup"><span data-stu-id="39c32-134">Gets or sets the size of the cache.</span></span></summary>
        <value><span data-ttu-id="39c32-135">Die Größe des Caches.</span><span class="sxs-lookup"><span data-stu-id="39c32-135">The size of the cache.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheTokens">
      <MemberSignature Language="C#" Value="public bool CacheTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CacheTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.CacheTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheTokens As Boolean" />
      <MemberSignature Language="F#" Value="member this.CacheTokens : bool with get, set" Usage="Microsoft.ServiceBus.TokenProvider.CacheTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39c32-136">Ruft ab oder legt einen Wert, der angibt, ob neue Sicherheitstokens zwischengespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="39c32-136">Gets or sets a value that indicates whether new security tokens are being cached.</span></span></summary>
        <value><span data-ttu-id="39c32-137">"true", wenn neue Sicherheitstokens zwischengespeichert sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-137">true if new security tokens are being cached; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="tokenProvider.Clear " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="39c32-138">Löscht den Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-138">Clears the token provider.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientAssertionCertificate, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="39c32-139">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-139">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="39c32-140">Die zertifikatsanmeldeinformationen für den Client-Assertion.</span><span class="sxs-lookup"><span data-stu-id="39c32-140">The client assertion certificate credential.</span></span></param>
        <param name="audience"><span data-ttu-id="39c32-141">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-141">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-142">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-142">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-143">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-143">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientCredential, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="39c32-144">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-144">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="39c32-145">Die app-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="39c32-145">The app credential.</span></span></param>
        <param name="audience"><span data-ttu-id="39c32-146">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-146">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-147">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-147">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-148">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-148">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, userPasswordCredential, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="39c32-149">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-149">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="39c32-150">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-150">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="39c32-151">Die Kennwort-Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="39c32-151">The user password credential.</span></span></param>
        <param name="audience"><span data-ttu-id="39c32-152">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-152">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-153">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-153">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-154">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-154">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAadTokenProvider (authContext As AuthenticationContext, clientId As String, redirectUri As Uri, platformParameters As IPlatformParameters, audience As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="39c32-155">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-155">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="39c32-156">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-156">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="39c32-157">Die RedrectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="39c32-157">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="39c32-158">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="39c32-158">Platform parameters</span></span></param>
        <param name="audience"><span data-ttu-id="39c32-159">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-159">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-160">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-160">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-161">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-161">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.Uri)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, userIdentifier, audience)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="authContext"><span data-ttu-id="39c32-162">AuthenticationContext für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-162">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="39c32-163">ClientId für AAD.</span><span class="sxs-lookup"><span data-stu-id="39c32-163">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="39c32-164">Die RedrectUri auf Client-App.</span><span class="sxs-lookup"><span data-stu-id="39c32-164">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="39c32-165">Platform-Parameter</span><span class="sxs-lookup"><span data-stu-id="39c32-165">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="39c32-166">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="39c32-166">User Identifier</span></span></param>
        <param name="audience"><span data-ttu-id="39c32-167">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-167">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-168">Erstellt eine Azure Active Directory-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-168">Creates an Azure Active Directory token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-169">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-169">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateManagedServiceIdentityTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateManagedServiceIdentityTokenProvider (Uri audience);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateManagedServiceIdentityTokenProvider(class System.Uri audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateManagedServiceIdentityTokenProvider(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateManagedServiceIdentityTokenProvider (audience As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateManagedServiceIdentityTokenProvider : Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateManagedServiceIdentityTokenProvider audience" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="audience"><span data-ttu-id="39c32-170">Der Dienst Ressourcen-URI für den tokenabruf.</span><span class="sxs-lookup"><span data-stu-id="39c32-170">The service resource URI for token acquisition.</span></span></param>
        <summary><span data-ttu-id="39c32-171">Erstellt Azure verwaltet Dienstidentität-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-171">Creates Azure Managed Service Identity token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-172">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von Json-webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-172">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning Json web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOAuthTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateOAuthTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateOAuthTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateOAuthTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateOAuthTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateOAuthTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateOAuthTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="39c32-173">Die URIs der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-173">The URIs of the Security Token Service (STS).</span></span></param>
        <param name="credential"><span data-ttu-id="39c32-174">Die Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="39c32-174">The user credential.</span></span></param>
        <summary><span data-ttu-id="39c32-175">Erstellt ein Tokenanbieter OAuth (offenen Standard zur Autorisierung).</span><span class="sxs-lookup"><span data-stu-id="39c32-175">Creates an OAuth (open standard for authorization) token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-176">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe der OAuth-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-176">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning OAuth token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider samlToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-177">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-177">The string that represents the SAML token.</span></span></param>
        <summary><span data-ttu-id="39c32-178">Erstellt einen SAML-Tokenanbieter mit dem angegebenen SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-178">Creates a SAML token provider with the specified SAML token.</span></span></summary>
        <returns><span data-ttu-id="39c32-179">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-179">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-180">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-180">The string that represents the SAML token.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-181">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-181">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-182">Erstellt einen SAML-Tokenanbieter mit den angegebenen SAML-Token und den Bereich an.</span><span class="sxs-lookup"><span data-stu-id="39c32-182">Creates a SAML token provider with the specified SAML token and scope.</span></span></summary>
        <returns><span data-ttu-id="39c32-183">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-183">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-184">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-184">The string that represents the SAML token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-185">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-185">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="39c32-186">Erstellt einen SAML-Tokenanbieter mit dem angegebenen SAML-Token und den URI für den Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-186">Creates a SAML token provider with the specified SAML token and URI of the Security Token Service (STS).</span></span></summary>
        <returns><span data-ttu-id="39c32-187">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-187">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-188">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-188">The string that represents the SAML token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-189">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-189">The URI of the Security Token Service (STS).</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-190">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-190">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-191">Erstellt einen SAML-Tokenanbieter mit dem angegebenen SAML-Token URI für den Sicherheitstokendienst (STS) und den token Bereich an.</span><span class="sxs-lookup"><span data-stu-id="39c32-191">Creates a SAML token provider with the specified SAML token, URI of the Security Token Service (STS) and token scope.</span></span></summary>
        <returns><span data-ttu-id="39c32-192">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-192">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, int cacheSize);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, int32 cacheSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSamlTokenProvider (samlToken As String, stsUri As Uri, cacheSize As Integer) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * int -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, cacheSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="cacheSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-193">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-193">The string that represents the SAML token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-194">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-194">The URI of the Security Token Service (STS).</span></span></param>
        <param name="cacheSize"><span data-ttu-id="39c32-195">Die Größe des Caches.</span><span class="sxs-lookup"><span data-stu-id="39c32-195">The size of the cache.</span></span></param>
        <summary><span data-ttu-id="39c32-196">Erstellt einen SAML-Tokenanbieter mit der angegebenen SAML-Token wird der URI der Sicherheitstokendienst (STS) und der Cache-Größe an.</span><span class="sxs-lookup"><span data-stu-id="39c32-196">Creates a SAML token provider with the specified SAML token, URI of the Security Token Service (STS) and cache size.</span></span></summary>
        <returns><span data-ttu-id="39c32-197">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-197">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSamlTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider (string samlToken, Uri stsUri, int cacheSize, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSamlTokenProvider(string samlToken, class System.Uri stsUri, int32 cacheSize, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider(System.String,System.Uri,System.Int32,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSamlTokenProvider : string * Uri * int * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSamlTokenProvider (samlToken, stsUri, cacheSize, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="samlToken" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="cacheSize" Type="System.Int32" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="samlToken"><span data-ttu-id="39c32-198">Die Zeichenfolge, die das SAML-Token darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-198">The string that represents the SAML token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-199">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-199">The URI of the Security Token Service (STS).</span></span></param>
        <param name="cacheSize"><span data-ttu-id="39c32-200">Die Größe des Caches.</span><span class="sxs-lookup"><span data-stu-id="39c32-200">The size of the cache.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-201">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-201">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-202">Erstellt einen SAML-Tokenanbieter mit dem angegebenen SAML-Token URI der Sicherheitstokendienst (STS), Cachegröße und token Bereich an.</span><span class="sxs-lookup"><span data-stu-id="39c32-202">Creates a SAML token provider with the specified SAML token, URI of the Security Token Service (STS), cache size and token scope.</span></span></summary>
        <returns><span data-ttu-id="39c32-203">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von SAML-Token.</span><span class="sxs-lookup"><span data-stu-id="39c32-203">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning SAML token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="39c32-204">die SAS-Signatur.</span><span class="sxs-lookup"><span data-stu-id="39c32-204">The shared access signature.</span></span></param>
        <summary><span data-ttu-id="39c32-205">Erstellt eine URL, die der Tokenanbieter mit dem angegebenen SAS Zugriff gewährt.</span><span class="sxs-lookup"><span data-stu-id="39c32-205">Creates a URL that grants access to the token provider with the specified shared access signature.</span></span></summary>
        <returns><span data-ttu-id="39c32-206">Gibt <see cref="T:Microsoft.ServiceBus.TokenProvider" />zurück.</span><span class="sxs-lookup"><span data-stu-id="39c32-206">Returns <see cref="T:Microsoft.ServiceBus.TokenProvider" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="39c32-207">Der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="39c32-207">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="39c32-208">Der SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-208">The shared access key.</span></span></param>
        <summary><span data-ttu-id="39c32-209">Erstellt eine URL, die Zugriff auf den Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen und SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-209">Creates a URL that grants access to the token provider with the specified key name and shared access key.</span></span></summary>
        <returns><span data-ttu-id="39c32-210">Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-210">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="39c32-211">Der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="39c32-211">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="39c32-212">Der SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-212">The shared access key.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-213">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-213">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-214">Erstellt eine URL, die Zugriff auf den Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen, SAS-Schlüssel und token-Bereich.</span><span class="sxs-lookup"><span data-stu-id="39c32-214">Creates a URL that grants access to the token provider with the specified key name, shared access key and token scope.</span></span></summary>
        <returns><span data-ttu-id="39c32-215">Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-215">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="39c32-216">Der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="39c32-216">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="39c32-217">Der SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-217">The shared access key.</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="39c32-218">Die Zeit für die der Vorgang gültig bleibt.</span><span class="sxs-lookup"><span data-stu-id="39c32-218">The time for which the operation remains valid.</span></span></param>
        <summary><span data-ttu-id="39c32-219">Erstellt eine URL, die Zugriff auf den Anbieter von Sicherheitstoken mit dem angegebenen Schlüsselnamen, SAS-Schlüssel und token Zeit Gültigkeitsdauer.</span><span class="sxs-lookup"><span data-stu-id="39c32-219">Creates a URL that grants access to the token provider with the specified key name, shared access key and token time to live.</span></span></summary>
        <returns><span data-ttu-id="39c32-220">Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-220">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="39c32-221">Der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="39c32-221">The key name.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="39c32-222">Der SAS-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-222">The shared access key.</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="39c32-223">Die Zeit für die der Vorgang gültig bleibt.</span><span class="sxs-lookup"><span data-stu-id="39c32-223">The time for which the operation remains valid.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-224">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-224">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-225">Erstellt eine URL, die Zugriff auf den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-225">Creates a URL that grants access to the token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-226">Die erstellte URL, die Zugriff auf Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-226">The created URL that grants access to token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte()) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-227">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-227">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-228">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-228">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="39c32-229">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-229">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-230">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</span><span class="sxs-lookup"><span data-stu-id="39c32-230">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-231">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-231">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-232">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-232">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="39c32-233">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-233">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-234">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</span><span class="sxs-lookup"><span data-stu-id="39c32-234">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-235">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="39c32-235">The name of the issuer.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-236">Der Satz von geheimen Schlüssel des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="39c32-236">The set of issuer secret.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-237">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-237">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-238">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-238">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-239">Der Tokenanbieter erstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-239">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As Byte(), stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-240">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-240">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-241">Der Satz von geheimen Schlüssel des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="39c32-241">The set of issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-242">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-242">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="39c32-243">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-243">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-244">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</span><span class="sxs-lookup"><span data-stu-id="39c32-244">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-245">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-245">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-246">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-246">The issuer secret.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-247">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-247">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-248">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-248">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-249">Der Tokenanbieter erstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-249">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedSecretTokenProvider (issuerName As String, issuerSecret As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-250">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-250">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-251">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-251">The issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-252">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-252">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="39c32-253">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-253">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-254">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe gemeinsamen geheimen Tokens.</span><span class="sxs-lookup"><span data-stu-id="39c32-254">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning shared secret token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, byte[] issuerSecret, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, unsigned int8[] issuerSecret, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.Byte[],System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * byte[] * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-255">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-255">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-256">Der Satz von geheimen Schlüssel des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="39c32-256">The set of issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-257">Der STS Endpunkt-Uri.</span><span class="sxs-lookup"><span data-stu-id="39c32-257">The Security Token Service's endpoint Uri.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-258">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-258">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-259">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-259">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-260">Der Tokenanbieter erstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-260">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedSecretTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider (string issuerName, string issuerSecret, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSharedSecretTokenProvider(string issuerName, string issuerSecret, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider(System.String,System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedSecretTokenProvider : string * string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSharedSecretTokenProvider (issuerName, issuerSecret, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="39c32-261">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="39c32-261">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="39c32-262">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="39c32-262">The issuer secret.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-263">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-263">The URI of the Security Token Service (STS).</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-264">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-264">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-265">Erstellt einen freigegebenen geheimen Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-265">Creates a shared secret token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-266">Der Tokenanbieter erstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-266">The created token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="39c32-267">Die Zeichenfolge, die das simple webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-267">The string that represents the simple web token.</span></span></param>
        <summary><span data-ttu-id="39c32-268">Erstellt einen einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-268">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-269">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von einfachen webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-269">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning simple web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="39c32-270">Die Zeichenfolge, die das simple webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-270">The string that represents the simple web token.</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-271">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-271">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-272">Erstellt einen einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-272">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-273">Der erstellte einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-273">The created simple web token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSimpleWebTokenProvider (token As String, stsUri As Uri) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="39c32-274">Die Zeichenfolge, die das simple webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-274">The string that represents the simple web token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-275">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-275">The URI of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="39c32-276">Erstellt einen einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-276">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-277">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für die Rückgabe von einfachen webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-277">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning simple web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSimpleWebTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider (string token, Uri stsUri, Microsoft.ServiceBus.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateSimpleWebTokenProvider(string token, class System.Uri stsUri, valuetype Microsoft.ServiceBus.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider(System.String,System.Uri,Microsoft.ServiceBus.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSimpleWebTokenProvider : string * Uri * Microsoft.ServiceBus.TokenScope -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateSimpleWebTokenProvider (token, stsUri, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="stsUri" Type="System.Uri" />
        <Parameter Name="tokenScope" Type="Microsoft.ServiceBus.TokenScope" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="39c32-278">Die Zeichenfolge, die das simple webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-278">The string that represents the simple web token.</span></span></param>
        <param name="stsUri"><span data-ttu-id="39c32-279">Der URI der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-279">The URI of the Security Token Service (STS).</span></span></param>
        <param name="tokenScope"><span data-ttu-id="39c32-280">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-280">The token scope associated with the provider.</span></span></param>
        <summary><span data-ttu-id="39c32-281">Erstellt einen einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-281">Creates a simple web token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-282">Der erstellte einfache Web-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-282">The created simple web token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri)) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider stsUris" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="39c32-283">Die URIs der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-283">The URIs of the Security Token Service (STS).</span></span></param>
        <summary><span data-ttu-id="39c32-284">Erstellt einen Windows-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-284">Creates a windows token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-285">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für das Windows-Token zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="39c32-285">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning the windows token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider (System.Collections.Generic.IEnumerable&lt;Uri&gt; stsUris, System.Net.NetworkCredential credential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.TokenProvider CreateWindowsTokenProvider(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsUris, class System.Net.NetworkCredential credential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider(System.Collections.Generic.IEnumerable{System.Uri},System.Net.NetworkCredential)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateWindowsTokenProvider (stsUris As IEnumerable(Of Uri), credential As NetworkCredential) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateWindowsTokenProvider : seq&lt;Uri&gt; * System.Net.NetworkCredential -&gt; Microsoft.ServiceBus.TokenProvider" Usage="Microsoft.ServiceBus.TokenProvider.CreateWindowsTokenProvider (stsUris, credential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stsUris" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="credential" Type="System.Net.NetworkCredential" />
      </Parameters>
      <Docs>
        <param name="stsUris"><span data-ttu-id="39c32-286">Die URIs der Sicherheitstokendienst (STS).</span><span class="sxs-lookup"><span data-stu-id="39c32-286">The URIs of the Security Token Service (STS).</span></span></param>
        <param name="credential"><span data-ttu-id="39c32-287">Die Anmeldeinformationen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="39c32-287">The user credential.</span></span></param>
        <summary><span data-ttu-id="39c32-288">Erstellt einen Windows-Tokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="39c32-288">Creates a windows token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-289">Die <see cref="T:Microsoft.ServiceBus.TokenProvider" /> für das Windows-Token zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="39c32-289">The <see cref="T:Microsoft.ServiceBus.TokenProvider" /> for returning the windows token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetToken">
      <MemberSignature Language="C#" Value="public System.IdentityModel.Tokens.SecurityToken EndGetToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IdentityModel.Tokens.SecurityToken EndGetToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.EndGetToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetToken (result As IAsyncResult) As SecurityToken" />
      <MemberSignature Language="F#" Value="member this.EndGetToken : IAsyncResult -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.EndGetToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="39c32-290">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-290">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <summary><span data-ttu-id="39c32-291">Schließt einen asynchronen Vorgang ab, um ein Sicherheitstoken abzurufen.</span><span class="sxs-lookup"><span data-stu-id="39c32-291">Completes an asynchronous operation to get a security token.</span></span></summary>
        <returns><span data-ttu-id="39c32-292">Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="39c32-292">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetWebToken">
      <MemberSignature Language="C#" Value="public string EndGetWebToken (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetWebToken(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.EndGetWebToken(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetWebToken (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetWebToken : IAsyncResult -&gt; string" Usage="tokenProvider.EndGetWebToken result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="39c32-293">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-293">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <summary><span data-ttu-id="39c32-294">Schließt einen asynchronen Vorgang zum Abrufen einer webtoken.</span><span class="sxs-lookup"><span data-stu-id="39c32-294">Completes an asynchronous operation to get a web token.</span></span></summary>
        <returns><span data-ttu-id="39c32-295">Die <see cref="T:System.String" /> , die das webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-295">The <see cref="T:System.String" /> that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IdentityModel.Tokens.SecurityToken&gt; GetTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.GetTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IdentityModel.Tokens.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-296">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-296">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-297">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-297">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="39c32-298">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="39c32-298">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-299">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-299">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <summary><span data-ttu-id="39c32-300">Asynchron Ruft das Token für den Anbieter ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-300">Asynchronously retrieves the token for the provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-301">Das Ergebnis des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="39c32-301">The result of the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWebTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetWebTokenAsync (string appliesTo, string action, bool bypassCache, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetWebTokenAsync(string appliesTo, string action, bool bypassCache, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.GetWebTokenAsync(System.String,System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetWebTokenAsync (appliesTo As String, action As String, bypassCache As Boolean, timeout As TimeSpan) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetWebTokenAsync : string * string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="tokenProvider.GetWebTokenAsync (appliesTo, action, bypassCache, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="bypassCache" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-302">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-302">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-303">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-303">The request action.</span></span></param>
        <param name="bypassCache"><span data-ttu-id="39c32-304">"true", um vorhandene Tokeninformationen im Cache zu ignorieren; "false", der token Informationen im Cache zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="39c32-304">true to ignore existing token information in the cache; false to use the token information in the cache.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-305">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-305">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <summary><span data-ttu-id="39c32-306">Ruft Sie die webtoken für den Anbieter asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-306">Asynchronously retrieves the web token for the provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-307">Das Ergebnis des asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="39c32-307">The result of the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWebTokenSupported">
      <MemberSignature Language="C#" Value="public bool IsWebTokenSupported { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWebTokenSupported" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.IsWebTokenSupported" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWebTokenSupported As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWebTokenSupported : bool" Usage="Microsoft.ServiceBus.TokenProvider.IsWebTokenSupported" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39c32-308">Ruft ab oder legt einen Wert, der angibt, ob webtoken von diesem Anbieter unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="39c32-308">Gets or sets a value that indicates whether web token is supported by this provider.</span></span></summary>
        <value><span data-ttu-id="39c32-309">"true", wenn webtoken von diesem Anbieter unterstützt wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-309">true if web token is supported by this provider; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected virtual string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="abstract member NormalizeAppliesTo : string -&gt; string&#xA;override this.NormalizeAppliesTo : string -&gt; string" Usage="tokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-310">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-310">The URI which the access token applies to.</span></span></param>
        <summary><span data-ttu-id="39c32-311">Gibt ein Objekt, dessen Wert der Tokenanbieter identisch ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-311">Returns an object whose value is the same as the token provider.</span></span></summary>
        <returns><span data-ttu-id="39c32-312">Das zurückgegebene Objekt.</span><span class="sxs-lookup"><span data-stu-id="39c32-312">The returned object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-313">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-313">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-314">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-314">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-315">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-315">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="39c32-316">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="39c32-316">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="39c32-317">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="39c32-317">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="39c32-318">Führt beim Aufrufen der BeginGetToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="39c32-318">Executes upon calling the BeginGetToken method.</span></span></summary>
        <returns><span data-ttu-id="39c32-319">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-319">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="tokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="39c32-320">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="39c32-320">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="39c32-321">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="39c32-321">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="39c32-322">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="39c32-322">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="39c32-323">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="39c32-323">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="39c32-324">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="39c32-324">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="39c32-325">Führt beim Aufrufen der BeginGetWebToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="39c32-325">Executes upon calling the BeginGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="39c32-326">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-326">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected abstract System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="tokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="39c32-327">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-327">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="39c32-328">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="39c32-328">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="39c32-329">Führt beim Aufrufen der EndGetToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="39c32-329">Executes upon calling the EndGetToken method.</span></span></summary>
        <returns><span data-ttu-id="39c32-330">Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="39c32-330">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected abstract string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="tokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="39c32-331">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="39c32-331">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="39c32-332">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="39c32-332">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="39c32-333">Führt beim Aufrufen der EndGetWebToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="39c32-333">Executes upon calling the EndGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="39c32-334">Die <see cref="T:System.String" /> , die das webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="39c32-334">The <see cref="T:System.String" /> that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected virtual bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.ServiceBus.TokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39c32-335">Ruft ab, ob der Tokenanbieter Abfrageparameter entfernt.</span><span class="sxs-lookup"><span data-stu-id="39c32-335">Gets whether the token provider strips query parameters.</span></span></summary>
        <value><span data-ttu-id="39c32-336">"true", wenn der Tokenanbieter Abfrageparameter entfernt; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="39c32-336">true if the token provider strips query parameters; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenScope TokenScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TokenProvider.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.ServiceBus.TokenScope" Usage="Microsoft.ServiceBus.TokenProvider.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="39c32-337">Ermittelt oder definiert das token Bereich, der dem Anbieter zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="39c32-337">Gets or sets the token scope associated with the provider.</span></span></summary>
        <value><span data-ttu-id="39c32-338">Der token Bereich, der dem Anbieter zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="39c32-338">The token scope associated with the provider.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>