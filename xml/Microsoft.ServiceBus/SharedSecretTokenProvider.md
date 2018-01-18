<Type Name="SharedSecretTokenProvider" FullName="Microsoft.ServiceBus.SharedSecretTokenProvider">
  <TypeSignature Language="C#" Value="public class SharedSecretTokenProvider : Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedSecretTokenProvider extends Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SharedSecretTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedSecretTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SharedSecretTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d6de8-101">Enthält Methoden, die Name/Wert-Paare für Web token Assertionen zurückgibt und das asynchrone freigegebene geheime Sicherheitstoken Abrufvorgänge ausführen.</span><span class="sxs-lookup"><span data-stu-id="d6de8-101">Provides methods that return name/value pairs for web token assertions, and that execute asynchronous shared secret token retrieval operations.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="sharedSecretTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="d6de8-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="d6de8-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="d6de8-103">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="d6de8-103">The request action.</span></span></param>
        <summary><span data-ttu-id="d6de8-104">Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="d6de8-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="d6de8-105">Ein generierter Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="d6de8-105">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeSimpleWebTokenString">
      <MemberSignature Language="C#" Value="public static string ComputeSimpleWebTokenString (string issuerName, byte[] issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ComputeSimpleWebTokenString(string issuerName, unsigned int8[] issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ComputeSimpleWebTokenString (issuerName As String, issuerSecret As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member ComputeSimpleWebTokenString : string * byte[] -&gt; string" Usage="Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="d6de8-106">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="d6de8-106">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="d6de8-107">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="d6de8-107">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="d6de8-108">Gibt eine Zeichenfolge mit URL-Wert-Paare für einfache Web-tokenassertion mit dem angegebenen Ausstellernamen und geheime Schlüssel des Ausstellers codiert zurück.</span><span class="sxs-lookup"><span data-stu-id="d6de8-108">Returns a string of URL encoded name/value pairs for a simple web token assertion using the specified issuer name and issuer secret.</span></span></summary>
        <returns><span data-ttu-id="d6de8-109">Eine URL-codierte Name/Wert-Paare für eine einfache Web-token-Assertion.</span><span class="sxs-lookup"><span data-stu-id="d6de8-109">A URL encoded name/value pairs for a simple web token assertion.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeSimpleWebTokenString">
      <MemberSignature Language="C#" Value="public static string ComputeSimpleWebTokenString (string issuerName, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ComputeSimpleWebTokenString(string issuerName, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ComputeSimpleWebTokenString (issuerName As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member ComputeSimpleWebTokenString : string * string -&gt; string" Usage="Microsoft.ServiceBus.SharedSecretTokenProvider.ComputeSimpleWebTokenString (issuerName, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="d6de8-110">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="d6de8-110">The issuer name.</span></span></param>
        <param name="issuerSecret"><span data-ttu-id="d6de8-111">Der geheime Ausstellerschlüssel.</span><span class="sxs-lookup"><span data-stu-id="d6de8-111">The issuer secret.</span></span></param>
        <summary><span data-ttu-id="d6de8-112">Gibt eine Zeichenfolge mit URL-Wert-Paare für einfache Web-tokenassertion mit dem angegebenen Ausstellernamen und geheime Schlüssel des Ausstellers codiert zurück.</span><span class="sxs-lookup"><span data-stu-id="d6de8-112">Returns a string of URL encoded name/value pairs for a simple web token assertion using the specified issuer name and issuer secret.</span></span></summary>
        <returns><span data-ttu-id="d6de8-113">Eine URL-codierte Name/Wert-Paare für eine einfache Web-token-Assertion.</span><span class="sxs-lookup"><span data-stu-id="d6de8-113">A URL encoded name/value pairs for a simple web token assertion.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedSecretTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="d6de8-114">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="d6de8-114">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="d6de8-115">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="d6de8-115">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="d6de8-116">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="d6de8-116">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="d6de8-117">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d6de8-117">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d6de8-118">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d6de8-118">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="d6de8-119">Führt die Begin Get-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="d6de8-119">Executes the begin get token action.</span></span></summary>
        <returns><span data-ttu-id="d6de8-120">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="d6de8-120">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedSecretTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="d6de8-121">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="d6de8-121">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="d6de8-122">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="d6de8-122">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="d6de8-123">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="d6de8-123">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="d6de8-124">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="d6de8-124">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="d6de8-125">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="d6de8-125">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="d6de8-126">Führt die Begin Get-Web-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="d6de8-126">Executes the begin get web token action.</span></span></summary>
        <returns><span data-ttu-id="d6de8-127">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="d6de8-127">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="sharedSecretTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="d6de8-128">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="d6de8-128">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="d6de8-129">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="d6de8-129">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="d6de8-130">Führt die End Get-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="d6de8-130">Executes the end get token action.</span></span></summary>
        <returns><span data-ttu-id="d6de8-131">Das Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="d6de8-131">The security token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedSecretTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="sharedSecretTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="d6de8-132">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="d6de8-132">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="d6de8-133">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="d6de8-133">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="d6de8-134">Führt die End Get-Web-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="d6de8-134">Executes the end get web token action.</span></span></summary>
        <returns><span data-ttu-id="d6de8-135">Das webtoken.</span><span class="sxs-lookup"><span data-stu-id="d6de8-135">The web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>