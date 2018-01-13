<Type Name="SharedAccessSignatureTokenProvider" FullName="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureTokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureTokenProvider extends Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1ed24-101">Repräsentiert die SAS-Signatur der Tokenanbieter zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ed24-101">Represents the shared access signature associated with the token provider.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="sharedAccessSignatureTokenProvider.BuildKey (appliesTo, action)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider+Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="1ed24-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="1ed24-103">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="1ed24-103">The request action.</span></span></param>
        <summary><span data-ttu-id="1ed24-104">Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="1ed24-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="1ed24-105">Ein generierter Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="1ed24-105">A generated key for the token provider.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EpochTime">
      <MemberSignature Language="C#" Value="public static readonly DateTime EpochTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.DateTime EpochTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EpochTime As DateTime " />
      <MemberSignature Language="F#" Value=" staticval mutable EpochTime : DateTime" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.EpochTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1ed24-106">Die epochenzeit.</span><span class="sxs-lookup"><span data-stu-id="1ed24-106">The epoch time.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public static string GetSharedAccessSignature (string keyName, string sharedAccessKey, string resource, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSharedAccessSignature(string keyName, string sharedAccessKey, string resource, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.GetSharedAccessSignature(System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSharedAccessSignature (keyName As String, sharedAccessKey As String, resource As String, tokenTimeToLive As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="static member GetSharedAccessSignature : string * string * string * TimeSpan -&gt; string" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.GetSharedAccessSignature (keyName, sharedAccessKey, resource, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="1ed24-107">der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="1ed24-107">The key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="1ed24-108">Der SAS-Schlüssel</span><span class="sxs-lookup"><span data-stu-id="1ed24-108">The shared access key</span></span></param>
        <param name="resource"><span data-ttu-id="1ed24-109">Die Ressource unscaped</span><span class="sxs-lookup"><span data-stu-id="1ed24-109">The unscaped resource</span></span></param>
        <param name="tokenTimeToLive"><span data-ttu-id="1ed24-110">Die Zeit Tolen Gültigkeitsdauer</span><span class="sxs-lookup"><span data-stu-id="1ed24-110">The tolen time to live</span></span></param>
        <summary>
             <span data-ttu-id="1ed24-111">Generiert eine shared Access signature</span><span class="sxs-lookup"><span data-stu-id="1ed24-111">Generated a shared access signature</span></span>
            </summary>
        <returns><span data-ttu-id="1ed24-112">Zurückgeben einer SAS</span><span class="sxs-lookup"><span data-stu-id="1ed24-112">Return a shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedAccessSignatureTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="1ed24-113">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-113">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="1ed24-114">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="1ed24-114">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="1ed24-115">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="1ed24-115">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="1ed24-116">Ein AsyncCallback-Delegat, der auf die Methode verweist, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="1ed24-116">An AsyncCallback delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="1ed24-117">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="1ed24-117">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="1ed24-118">Führt beim Aufrufen der BeginGetToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="1ed24-118">Executes upon calling the BeginGetToken method.</span></span></summary>
        <returns><span data-ttu-id="1ed24-119">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ed24-119">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="sharedAccessSignatureTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="appliesTo"><span data-ttu-id="1ed24-120">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-120">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="1ed24-121">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="1ed24-121">The request action.</span></span></param>
        <param name="timeout"><span data-ttu-id="1ed24-122">Die Zeitspanne, die den Timeoutwert für die Nachricht gibt an, die Ruft das Sicherheitstoken ab.</span><span class="sxs-lookup"><span data-stu-id="1ed24-122">The time span that specifies the timeout value for the message that gets the security token.</span></span></param>
        <param name="callback"><span data-ttu-id="1ed24-123">Ein AsyncCallback-Delegat, der auf die Methode verweist, die aufgerufen wird, wenn der Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="1ed24-123">An AsyncCallback delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="1ed24-124">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="1ed24-124">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="1ed24-125">Führt beim Aufrufen der BeginGetWebToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="1ed24-125">Executes upon calling the BeginGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="1ed24-126">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1ed24-126">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="sharedAccessSignatureTokenProvider.OnEndGetToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="1ed24-127">Ein "IAsyncResult"-Objekt, das den asynchronen Vorgang zum Abrufen eines Tokens verweist.</span><span class="sxs-lookup"><span data-stu-id="1ed24-127">An IAsyncResult object that references the asynchronous operation to get a token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="1ed24-128">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="1ed24-128">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="1ed24-129">Führt beim Aufrufen der EndGetToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="1ed24-129">Executes upon calling the EndGetToken method.</span></span></summary>
        <returns><span data-ttu-id="1ed24-130">Das <see cref="T:System.IdentityModel.Tokens.SecurityToken" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-130">The <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="sharedAccessSignatureTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="cacheUntil" Type="System.DateTime&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="1ed24-131">Ein "IAsyncResult"-Objekt, das den asynchronen Vorgang, um eine Web-Zugriffstoken zu erhalten verweist.</span><span class="sxs-lookup"><span data-stu-id="1ed24-131">An IAsyncResult object that references the asynchronous operation to get a web token.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="1ed24-132">Wenn diese Methode zurückgibt, enthält das Ablaufdatum und die Uhrzeit der token Informationen im Cache.</span><span class="sxs-lookup"><span data-stu-id="1ed24-132">When this method returns, contains the expiration date and time of the token information in the cache.</span></span></param>
        <summary><span data-ttu-id="1ed24-133">Führt beim Aufrufen der EndGetWebToken-Methode.</span><span class="sxs-lookup"><span data-stu-id="1ed24-133">Executes upon calling the EndGetWebToken method.</span></span></summary>
        <returns><span data-ttu-id="1ed24-134">Die Zeichenfolge, die das webtoken darstellt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-134">The String that represents the web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StripQueryParameters">
      <MemberSignature Language="C#" Value="protected override bool StripQueryParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool StripQueryParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.StripQueryParameters" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property StripQueryParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.StripQueryParameters : bool" Usage="Microsoft.Azure.NotificationHubs.SharedAccessSignatureTokenProvider.StripQueryParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1ed24-135">Ruft ab, ob der Tokenanbieter Abfrageparameter entfernt.</span><span class="sxs-lookup"><span data-stu-id="1ed24-135">Gets whether the token provider strips query parameters.</span></span></summary>
        <value><span data-ttu-id="1ed24-136">"true", wenn der Tokenanbieter Abfrageparameter entfernt; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="1ed24-136">true if the token provider strips query parameters; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>