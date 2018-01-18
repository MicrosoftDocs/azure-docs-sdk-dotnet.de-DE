<Type Name="SamlTokenProvider" FullName="Microsoft.ServiceBus.SamlTokenProvider">
  <TypeSignature Language="C#" Value="public class SamlTokenProvider : Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SamlTokenProvider extends Microsoft.ServiceBus.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SamlTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SamlTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SamlTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="0902e-101">Bietet eine Reihe von Methoden, die asynchrone Abrufvorgänge der SAML-token ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="0902e-101">Provides a set of methods that execute asynchronous SAML token retrieval operations.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.ServiceBus.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.ServiceBus.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SamlTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="samlTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="0902e-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="0902e-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="0902e-103">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="0902e-103">The request action.</span></span></param>
        <summary><span data-ttu-id="0902e-104">Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="0902e-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="0902e-105">Ein generierter Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="0902e-105">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SamlTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="samlTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="0902e-106">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="0902e-106">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="0902e-107">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="0902e-107">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="0902e-108">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="0902e-108">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="0902e-109">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0902e-109">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="0902e-110">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="0902e-110">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="0902e-111">Führt die Begin Get-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="0902e-111">Executes the begin get token action.</span></span></summary>
        <returns><span data-ttu-id="0902e-112">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="0902e-112">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SamlTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="samlTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="0902e-113">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="0902e-113">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="0902e-114">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="0902e-114">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="0902e-115">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="0902e-115">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="0902e-116">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0902e-116">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="0902e-117">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="0902e-117">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="0902e-118">Führt die Begin Get-Web-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="0902e-118">Executes the begin get web token action.</span></span></summary>
        <returns><span data-ttu-id="0902e-119">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="0902e-119">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SamlTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="samlTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="0902e-120">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="0902e-120">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="0902e-121">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="0902e-121">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="0902e-122">Führt die End Get-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="0902e-122">Executes the end get token action.</span></span></summary>
        <returns><span data-ttu-id="0902e-123">Das Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="0902e-123">The security token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SamlTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="samlTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="0902e-124">Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen einer webtoken verweist.</span><span class="sxs-lookup"><span data-stu-id="0902e-124">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="0902e-125">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="0902e-125">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="0902e-126">Führt die End Get-Web-token-Aktion an.</span><span class="sxs-lookup"><span data-stu-id="0902e-126">Executes the end get web token action.</span></span></summary>
        <returns><span data-ttu-id="0902e-127">Das webtoken.</span><span class="sxs-lookup"><span data-stu-id="0902e-127">The web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>