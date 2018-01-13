<Type Name="SharedAccessSignatureToken" FullName="Microsoft.ServiceBus.SharedAccessSignatureToken">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureToken : Microsoft.ServiceBus.SimpleWebSecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureToken extends Microsoft.ServiceBus.SimpleWebSecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SharedAccessSignatureToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureToken&#xA;Inherits SimpleWebSecurityToken" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureToken = class&#xA;    inherit SimpleWebSecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.SimpleWebSecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="92166-101">Stellt die SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92166-101">Represents the shared access signature token.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedAccessSignatureToken.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SharedAccessSignatureToken : string -&gt; Microsoft.ServiceBus.SharedAccessSignatureToken" Usage="new Microsoft.ServiceBus.SharedAccessSignatureToken tokenString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="92166-102">Die Tokenzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="92166-102">The token string.</span></span></param>
        <summary><span data-ttu-id="92166-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> -Klasse mit angegebenen tokenzeichenkette darstellt.</span><span class="sxs-lookup"><span data-stu-id="92166-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> class with specified token string.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString, DateTime expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedAccessSignatureToken.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SharedAccessSignatureToken : string * DateTime -&gt; Microsoft.ServiceBus.SharedAccessSignatureToken" Usage="new Microsoft.ServiceBus.SharedAccessSignatureToken (tokenString, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="92166-104">Die Tokenzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="92166-104">The token string.</span></span></param>
        <param name="expiry"><span data-ttu-id="92166-105">Die token-Ablauf.</span><span class="sxs-lookup"><span data-stu-id="92166-105">The token expiry.</span></span></param>
        <summary><span data-ttu-id="92166-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> -Klasse mit angegebenen Tokenzeichenfolge und Ablauf.</span><span class="sxs-lookup"><span data-stu-id="92166-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> class with specified token string and expiry.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string id, string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedAccessSignatureToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SharedAccessSignatureToken : string * string -&gt; Microsoft.ServiceBus.SharedAccessSignatureToken" Usage="new Microsoft.ServiceBus.SharedAccessSignatureToken (id, tokenString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="92166-107">Die token-ID.</span><span class="sxs-lookup"><span data-stu-id="92166-107">The token identifier.</span></span></param>
        <param name="tokenString"><span data-ttu-id="92166-108">Die Tokenzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="92166-108">The token string.</span></span></param>
        <summary><span data-ttu-id="92166-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> Klasse mit dem angegebenen Bezeichner und tokenzeichenkette darstellt.</span><span class="sxs-lookup"><span data-stu-id="92166-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> class with specified identifier and token string.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureToken (string tokenString, DateTime expiry, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SharedAccessSignatureToken.#ctor(System.String,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SharedAccessSignatureToken : string * DateTime * string -&gt; Microsoft.ServiceBus.SharedAccessSignatureToken" Usage="new Microsoft.ServiceBus.SharedAccessSignatureToken (tokenString, expiry, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString"><span data-ttu-id="92166-110">Die Tokenzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="92166-110">The token string.</span></span></param>
        <param name="expiry"><span data-ttu-id="92166-111">Die token-Ablauf.</span><span class="sxs-lookup"><span data-stu-id="92166-111">The token expiry.</span></span></param>
        <param name="audience"><span data-ttu-id="92166-112">Die token Zielgruppe.</span><span class="sxs-lookup"><span data-stu-id="92166-112">The token audience.</span></span></param>
        <summary><span data-ttu-id="92166-113">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> -Klasse mit angegebenen Tokenzeichenfolge, Ablauf und Zielgruppe.</span><span class="sxs-lookup"><span data-stu-id="92166-113">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.SharedAccessSignatureToken" /> class with specified token string, expiry and audience.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AudienceFieldName">
      <MemberSignature Language="C#" Value="protected override string AudienceFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AudienceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SharedAccessSignatureToken.AudienceFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property AudienceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.AudienceFieldName : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.AudienceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-114">Ruft die Zielgruppe Feldnamen ab.</span><span class="sxs-lookup"><span data-stu-id="92166-114">Gets the audience field name.</span></span></summary>
        <value><span data-ttu-id="92166-115">Der Feldname der Zielgruppe.</span><span class="sxs-lookup"><span data-stu-id="92166-115">The audience field name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOnFieldName">
      <MemberSignature Language="C#" Value="protected override string ExpiresOnFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpiresOnFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SharedAccessSignatureToken.ExpiresOnFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property ExpiresOnFieldName As String" />
      <MemberSignature Language="F#" Value="member this.ExpiresOnFieldName : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.ExpiresOnFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-116">Ruft den Wert, der Name des Felds läuft ab.</span><span class="sxs-lookup"><span data-stu-id="92166-116">Gets the value that expires on field name.</span></span></summary>
        <value><span data-ttu-id="92166-117">Der Wert, der Name des Felds läuft ab.</span><span class="sxs-lookup"><span data-stu-id="92166-117">The value that expires on field name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueSeparator">
      <MemberSignature Language="C#" Value="protected override string KeyValueSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValueSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SharedAccessSignatureToken.KeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property KeyValueSeparator As String" />
      <MemberSignature Language="F#" Value="member this.KeyValueSeparator : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.KeyValueSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-118">Ruft das Schlüssel-Wert-Trennzeichen an.</span><span class="sxs-lookup"><span data-stu-id="92166-118">Gets the key value separator.</span></span></summary>
        <value><span data-ttu-id="92166-119">Das Schlüssel-Wert-Trennzeichen.</span><span class="sxs-lookup"><span data-stu-id="92166-119">The key value separator.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxKeyLength">
      <MemberSignature Language="C#" Value="public const int MaxKeyLength = 256;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxKeyLength = (256)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.MaxKeyLength" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxKeyLength As Integer  = 256" />
      <MemberSignature Language="F#" Value="val mutable MaxKeyLength : int" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.MaxKeyLength" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary><span data-ttu-id="92166-120">Gibt die maximale Länge des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="92166-120">Specifies the maximum length of the key.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxKeyNameLength">
      <MemberSignature Language="C#" Value="public const int MaxKeyNameLength = 256;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxKeyNameLength = (256)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.MaxKeyNameLength" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxKeyNameLength As Integer  = 256" />
      <MemberSignature Language="F#" Value="val mutable MaxKeyNameLength : int" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.MaxKeyNameLength" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary><span data-ttu-id="92166-121">Gibt die maximale Länge des Schlüsselnamens.</span><span class="sxs-lookup"><span data-stu-id="92166-121">Specifies the maximum length of the key name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairSeparator">
      <MemberSignature Language="C#" Value="protected override string PairSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PairSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SharedAccessSignatureToken.PairSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PairSeparator As String" />
      <MemberSignature Language="F#" Value="member this.PairSeparator : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.PairSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-122">Ruft das Paar Trennzeichen, die dem Token zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="92166-122">Gets the pair separator associated with the token.</span></span></summary>
        <value><span data-ttu-id="92166-123">Das Paar-Trennzeichen, das dem Token zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="92166-123">The pair separator associated with the token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyValueSeparator">
      <MemberSignature Language="C#" Value="public const string SasKeyValueSeparator;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SasKeyValueSeparator" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SasKeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Const SasKeyValueSeparator As String " />
      <MemberSignature Language="F#" Value="val mutable SasKeyValueSeparator : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SasKeyValueSeparator" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-124">Gibt an, das Schlüssel-Wert-Trennzeichen für SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92166-124">Specifies the key value separator for shared access signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasPairSeparator">
      <MemberSignature Language="C#" Value="public const string SasPairSeparator;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SasPairSeparator" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SasPairSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Const SasPairSeparator As String " />
      <MemberSignature Language="F#" Value="val mutable SasPairSeparator : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SasPairSeparator" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-125">Gibt das Paar-Trennzeichen für SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92166-125">Specifies the pair separator for shared access signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public const string SharedAccessSignature;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Const SharedAccessSignature As String " />
      <MemberSignature Language="F#" Value="val mutable SharedAccessSignature : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SharedAccessSignature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-126">Gibt die SAS-Signatur.</span><span class="sxs-lookup"><span data-stu-id="92166-126">Specifies the shared access signature.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Signature">
      <MemberSignature Language="C#" Value="public const string Signature;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Signature" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.Signature" />
      <MemberSignature Language="VB.NET" Value="Public Const Signature As String " />
      <MemberSignature Language="F#" Value="val mutable Signature : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.Signature" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-127">Gibt an, die SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="92166-127">Specifies the signature token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedExpiry">
      <MemberSignature Language="C#" Value="public const string SignedExpiry;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedExpiry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SignedExpiry" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedExpiry As String " />
      <MemberSignature Language="F#" Value="val mutable SignedExpiry : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SignedExpiry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-128">Gibt an, mit Vorzeichen nach Ablauf des Tokens.</span><span class="sxs-lookup"><span data-stu-id="92166-128">Specifies the signed expiry of the token.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedKeyName">
      <MemberSignature Language="C#" Value="public const string SignedKeyName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedKeyName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SignedKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedKeyName As String " />
      <MemberSignature Language="F#" Value="val mutable SignedKeyName : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SignedKeyName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-129">Gibt den Namen des mit Vorzeichen.</span><span class="sxs-lookup"><span data-stu-id="92166-129">Specifies the signed key name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedResource">
      <MemberSignature Language="C#" Value="public const string SignedResource;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedResource" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SignedResource" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedResource As String " />
      <MemberSignature Language="F#" Value="val mutable SignedResource : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SignedResource" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-130">Gibt die signierte Ressource an.</span><span class="sxs-lookup"><span data-stu-id="92166-130">Specifies the signed resource.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedResourceFullFieldName">
      <MemberSignature Language="C#" Value="public const string SignedResourceFullFieldName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SignedResourceFullFieldName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SharedAccessSignatureToken.SignedResourceFullFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Const SignedResourceFullFieldName As String " />
      <MemberSignature Language="F#" Value="val mutable SignedResourceFullFieldName : string" Usage="Microsoft.ServiceBus.SharedAccessSignatureToken.SignedResourceFullFieldName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92166-131">Gibt den vollständigen Namen des signierte Ressource an.</span><span class="sxs-lookup"><span data-stu-id="92166-131">Specifies the full field name of the signed resource.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>