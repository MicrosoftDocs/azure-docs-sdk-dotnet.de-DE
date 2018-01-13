<Type Name="WindowsTokenProvider" FullName="Microsoft.Azure.NotificationHubs.WindowsTokenProvider">
  <TypeSignature Language="C#" Value="public class WindowsTokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsTokenProvider extends Microsoft.Azure.NotificationHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WindowsTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type WindowsTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="fde86-101">Stellt den Tokenanbieter für Servicebus dar.</span><span class="sxs-lookup"><span data-stu-id="fde86-101">Represents the token provider for the service bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildKey">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.NotificationHubs.TokenProvider.Key BuildKey (string appliesTo, string action);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.NotificationHubs.TokenProvider/Key BuildKey(string appliesTo, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.BuildKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function BuildKey (appliesTo As String, action As String) As TokenProvider.Key" />
      <MemberSignature Language="F#" Value="override this.BuildKey : string * string -&gt; Microsoft.Azure.NotificationHubs.TokenProvider.Key" Usage="windowsTokenProvider.BuildKey (appliesTo, action)" />
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
        <param name="appliesTo"><span data-ttu-id="fde86-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="fde86-102">The URI which the access token applies to.</span></span></param>
        <param name="action"><span data-ttu-id="fde86-103">Die anforderungsaktion.</span><span class="sxs-lookup"><span data-stu-id="fde86-103">The request action.</span></span></param>
        <summary><span data-ttu-id="fde86-104">Generiert einen Schlüssel für den Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="fde86-104">Generates a key for the token provider.</span></span></summary>
        <returns><span data-ttu-id="fde86-105">Ein generierter Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="fde86-105">A generated key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NormalizeAppliesTo">
      <MemberSignature Language="C#" Value="protected override string NormalizeAppliesTo (string appliesTo);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string NormalizeAppliesTo(string appliesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.NormalizeAppliesTo(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function NormalizeAppliesTo (appliesTo As String) As String" />
      <MemberSignature Language="F#" Value="override this.NormalizeAppliesTo : string -&gt; string" Usage="windowsTokenProvider.NormalizeAppliesTo appliesTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="fde86-106">Der URI, der die Normalisierung gilt.</span><span class="sxs-lookup"><span data-stu-id="fde86-106">The URI which the normalization applies to.</span></span></param>
        <summary><span data-ttu-id="fde86-107">Gibt den URI-Form die Zieladresse normalisieren.</span><span class="sxs-lookup"><span data-stu-id="fde86-107">Returns the normalize URI form of the target address.</span></span></summary>
        <returns><span data-ttu-id="fde86-108">Das Normalisieren URI-Format für die Zieladresse.</span><span class="sxs-lookup"><span data-stu-id="fde86-108">The normalize URI form for the target address.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnBeginGetToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="fde86-109">Das Objekt, in dem das Token angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="fde86-109">The object where the token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="fde86-110">Die Aktion.</span><span class="sxs-lookup"><span data-stu-id="fde86-110">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="fde86-111">Die Dauer des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-111">The duration of the operation.</span></span></param>
        <param name="callback"><span data-ttu-id="fde86-112">Das Argument Fir des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="fde86-112">The argument fir the provider.</span></span></param>
        <param name="state"><span data-ttu-id="fde86-113">Der Status des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="fde86-113">The state of the provider.</span></span></param>
        <summary><span data-ttu-id="fde86-114">Ruft ein Token ab, wenn der Provider-Dienst gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="fde86-114">Retrieves a token when the provider service was started.</span></span></summary>
        <returns><span data-ttu-id="fde86-115">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-115">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetWebToken">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginGetWebToken (string appliesTo, string action, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginGetWebToken(string appliesTo, string action, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnBeginGetWebToken(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginGetWebToken (appliesTo As String, action As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginGetWebToken : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="windowsTokenProvider.OnBeginGetWebToken (appliesTo, action, timeout, callback, state)" />
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
        <param name="appliesTo"><span data-ttu-id="fde86-116">Das Objekt, in dem das Token angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="fde86-116">The object where the token will be applied.</span></span></param>
        <param name="action"><span data-ttu-id="fde86-117">Die Aktion.</span><span class="sxs-lookup"><span data-stu-id="fde86-117">The action.</span></span></param>
        <param name="timeout"><span data-ttu-id="fde86-118">Die Dauer des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-118">The duration of the operation.</span></span></param>
        <param name="callback"><span data-ttu-id="fde86-119">Das Argument Fir des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="fde86-119">The argument fir the provider.</span></span></param>
        <param name="state"><span data-ttu-id="fde86-120">Der Status des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="fde86-120">The state of the provider.</span></span></param>
        <summary><span data-ttu-id="fde86-121">Ruft eine webtoken ab, wenn der Provider-Dienst gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="fde86-121">Retrieves a web token when the provider service was started.</span></span></summary>
        <returns><span data-ttu-id="fde86-122">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-122">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetToken">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken OnEndGetToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken OnEndGetToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnEndGetToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.OnEndGetToken : IAsyncResult *  -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="windowsTokenProvider.OnEndGetToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="fde86-123">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-123">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="fde86-124">Die angegebene Zeitspanne für den Anbieter zum Speichern von Daten.</span><span class="sxs-lookup"><span data-stu-id="fde86-124">The specified duration of time for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="fde86-125">Ruft ein Token ab, wenn der Provider-Dienst beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="fde86-125">Retrieves a token when the provider service was stopped.</span></span></summary>
        <returns><span data-ttu-id="fde86-126">Das abgerufene-Token.</span><span class="sxs-lookup"><span data-stu-id="fde86-126">The retrieved token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetWebToken">
      <MemberSignature Language="C#" Value="protected override string OnEndGetWebToken (IAsyncResult result, out DateTime cacheUntil);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string OnEndGetWebToken(class System.IAsyncResult result, [out] valuetype System.DateTime&amp; cacheUntil) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WindowsTokenProvider.OnEndGetWebToken(System.IAsyncResult,System.DateTime@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndGetWebToken (result As IAsyncResult, ByRef cacheUntil As DateTime) As String" />
      <MemberSignature Language="F#" Value="override this.OnEndGetWebToken : IAsyncResult *  -&gt; string" Usage="windowsTokenProvider.OnEndGetWebToken (result, cacheUntil)" />
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
        <param name="result"><span data-ttu-id="fde86-127">Das Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fde86-127">The result of the operation.</span></span></param>
        <param name="cacheUntil"><span data-ttu-id="fde86-128">Die angegebene Zeitspanne für den Anbieter zum Speichern von Daten.</span><span class="sxs-lookup"><span data-stu-id="fde86-128">The specified duration of time for the provider to store data.</span></span></param>
        <summary><span data-ttu-id="fde86-129">Ruft eine webtoken ab, wenn der Provider-Dienst beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="fde86-129">Retrieves a web token when the provider service was stopped.</span></span></summary>
        <returns><span data-ttu-id="fde86-130">Das abgerufene webtoken.</span><span class="sxs-lookup"><span data-stu-id="fde86-130">The retrieved web token.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>