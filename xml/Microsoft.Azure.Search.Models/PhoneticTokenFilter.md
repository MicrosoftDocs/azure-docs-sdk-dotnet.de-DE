<Type Name="PhoneticTokenFilter" FullName="Microsoft.Azure.Search.Models.PhoneticTokenFilter">
  <TypeSignature Language="C#" Value="public class PhoneticTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PhoneticTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PhoneticTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PhoneticTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PhoneticTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PhoneticTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bf8c8-101">Erstellen von Tokens für phonetischen entspricht.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-101">Create tokens for phonetic matches.</span></span> <span data-ttu-id="bf8c8-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-phonetic/org/apache/lucene/analysis/phonetic/package-tree.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf8c8-103">Initialisiert eine neue Instanz der PhoneticTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-103">Initializes a new instance of the PhoneticTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter (string name, Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder = null, Nullable&lt;bool&gt; replaceOriginalTokens = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder, valuetype System.Nullable`1&lt;bool&gt; replaceOriginalTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor(System.String,System.Nullable{Microsoft.Azure.Search.Models.PhoneticEncoder},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional encoder As Nullable(Of PhoneticEncoder) = null, Optional replaceOriginalTokens As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PhoneticTokenFilter : string * Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.PhoneticTokenFilter" Usage="new Microsoft.Azure.Search.Models.PhoneticTokenFilter (name, encoder, replaceOriginalTokens)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="encoder" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;" />
        <Parameter Name="replaceOriginalTokens" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="bf8c8-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-104">The name of the token filter.</span></span> <span data-ttu-id="bf8c8-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="encoder"><span data-ttu-id="bf8c8-106">Der phonetischen Encoder verwenden.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-106">The phonetic encoder to use.</span></span> <span data-ttu-id="bf8c8-107">Der Standardwert ist "Metaphone".</span><span class="sxs-lookup"><span data-stu-id="bf8c8-107">Default is "metaphone".</span></span> <span data-ttu-id="bf8c8-108">Folgende Werte sind möglich: "Metaphone", "DoubleMetaphone", "Soundex", "RefinedSoundex", "caverphone1", "caverphone2", "Köln", "Nysiis", "KoelnerPhonetik", "HaasePhonetik", "BeiderMorse"</span><span class="sxs-lookup"><span data-stu-id="bf8c8-108">Possible values include: 'metaphone', 'doubleMetaphone', 'soundex', 'refinedSoundex', 'caverphone1', 'caverphone2', 'cologne', 'nysiis', 'koelnerPhonetik', 'haasePhonetik', 'beiderMorse'</span></span></param>
        <param name="replaceOriginalTokens"><span data-ttu-id="bf8c8-109">Ein Wert, der angibt, ob die ursprünglichen Token codierte Token ersetzt werden soll.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-109">A value indicating whether encoded tokens should replace original tokens.</span></span> <span data-ttu-id="bf8c8-110">Wenn "false" werden codierte Token als Synonyme hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-110">If false, encoded tokens are added as synonyms.</span></span> <span data-ttu-id="bf8c8-111">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-111">Default is true.</span></span></param>
        <summary>
            <span data-ttu-id="bf8c8-112">Initialisiert eine neue Instanz der PhoneticTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-112">Initializes a new instance of the PhoneticTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoder">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoder As Nullable(Of PhoneticEncoder)" />
      <MemberSignature Language="F#" Value="member this.Encoder : Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoder")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf8c8-113">Abrufen oder festlegen den phonetischen Encoder verwenden.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-113">Gets or sets the phonetic encoder to use.</span></span> <span data-ttu-id="bf8c8-114">Der Standardwert ist "Metaphone".</span><span class="sxs-lookup"><span data-stu-id="bf8c8-114">Default is "metaphone".</span></span>
            <span data-ttu-id="bf8c8-115">Folgende Werte sind möglich: "Metaphone", "DoubleMetaphone", "Soundex", "RefinedSoundex", "caverphone1", "caverphone2", "Köln", "Nysiis", "KoelnerPhonetik", "HaasePhonetik", "BeiderMorse"</span><span class="sxs-lookup"><span data-stu-id="bf8c8-115">Possible values include: 'metaphone', 'doubleMetaphone', 'soundex', 'refinedSoundex', 'caverphone1', 'caverphone2', 'cologne', 'nysiis', 'koelnerPhonetik', 'haasePhonetik', 'beiderMorse'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceOriginalTokens">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReplaceOriginalTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReplaceOriginalTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplaceOriginalTokens As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReplaceOriginalTokens : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf8c8-116">Ruft ab oder legt einen Wert, der angibt, ob die ursprünglichen Token codierte Token ersetzt werden soll.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-116">Gets or sets a value indicating whether encoded tokens should replace original tokens.</span></span> <span data-ttu-id="bf8c8-117">Wenn "false" werden codierte Token als Synonyme hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-117">If false, encoded tokens are added as synonyms.</span></span> <span data-ttu-id="bf8c8-118">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-118">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="phoneticTokenFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf8c8-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bf8c8-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf8c8-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bf8c8-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>