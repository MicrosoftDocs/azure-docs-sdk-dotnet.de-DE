<Type Name="TokenProvider" FullName="Microsoft.Azure.Relay.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a9152-101">Dieser abstrakten Basisklasse kann erweitert werden, um zusätzliche Tokenanbieter zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="a9152-101">This abstract base class can be extended to implement additional token providers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a9152-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.TokenProvider" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a9152-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Relay.TokenProvider" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature"><span data-ttu-id="a9152-103">Die SAS</span><span class="sxs-lookup"><span data-stu-id="a9152-103">The shared access signature</span></span></param>
        <summary>
            <span data-ttu-id="a9152-104">Erstellen Sie einen TokenProvider dar, die basierend auf einer SharedAccessSignature.</span><span class="sxs-lookup"><span data-stu-id="a9152-104">Construct a TokenProvider based on a sharedAccessSignature.</span></span>
            </summary>
        <returns><span data-ttu-id="a9152-105">Einen TokenProvider dar, die mit der freigegebenen zugriffssignatur initialisiert</span><span class="sxs-lookup"><span data-stu-id="a9152-105">A TokenProvider initialized with the shared access signature</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Relay.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="a9152-106">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="a9152-106">The key name of the corresponding SharedAccessKeyAuthorizationRule.</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="a9152-107">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</span><span class="sxs-lookup"><span data-stu-id="a9152-107">The key associated with the SharedAccessKeyAuthorizationRule</span></span></param>
        <summary>
            <span data-ttu-id="a9152-108">Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.</span><span class="sxs-lookup"><span data-stu-id="a9152-108">Construct a TokenProvider based on the provided Key Name and Shared Access Key.</span></span>
            </summary>
        <returns><span data-ttu-id="a9152-109">Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</span><span class="sxs-lookup"><span data-stu-id="a9152-109">A TokenProvider initialized with the provided RuleId and Password</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; GetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="member this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience"><span data-ttu-id="a9152-110">Die Zielgruppe für das Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="a9152-110">The target audience for the security token.</span></span></param>
        <param name="validFor"><span data-ttu-id="a9152-111">Wie lange das generierte Token gültig sein soll.</span><span class="sxs-lookup"><span data-stu-id="a9152-111">How long the generated token should be valid for.</span></span></param>
        <summary>
            <span data-ttu-id="a9152-112">Ruft eine <see cref="T:Microsoft.Azure.Relay.SecurityToken" /> für die angegebene Zielgruppe und die Dauer.</span><span class="sxs-lookup"><span data-stu-id="a9152-112">Gets a <see cref="T:Microsoft.Azure.Relay.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns><span data-ttu-id="a9152-113">Eine Aufgabe, die neu erstellte SecurityToken zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="a9152-113">A Task returning the newly created SecurityToken.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetTokenAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync (string audience, TimeSpan validFor);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.SecurityToken&gt; OnGetTokenAsync(string audience, valuetype System.TimeSpan validFor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.TokenProvider.OnGetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetTokenAsync (audience As String, validFor As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member OnGetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;" Usage="tokenProvider.OnGetTokenAsync (audience, validFor)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="validFor" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="audience"><span data-ttu-id="a9152-114">Die Zielgruppe für das Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="a9152-114">The target audience for the security token.</span></span></param>
        <param name="validFor"><span data-ttu-id="a9152-115">Wie lange das generierte Token gültig sein soll.</span><span class="sxs-lookup"><span data-stu-id="a9152-115">How long the generated token should be valid for.</span></span></param>
        <summary>
            <span data-ttu-id="a9152-116">Implementiert durch abgeleitete Typen TokenProvider ihre SecurityTokens zu generieren.</span><span class="sxs-lookup"><span data-stu-id="a9152-116">Implemented by derived TokenProvider types to generate their SecurityTokens.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThisLock">
      <MemberSignature Language="C#" Value="protected object ThisLock { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ThisLock" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ThisLock As Object" />
      <MemberSignature Language="F#" Value="member this.ThisLock : obj" Usage="Microsoft.Azure.Relay.TokenProvider.ThisLock" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9152-117">Ruft das Synchronisierungsobjekt, das für die gegebene Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="a9152-117">Gets the synchronization object for the given instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>