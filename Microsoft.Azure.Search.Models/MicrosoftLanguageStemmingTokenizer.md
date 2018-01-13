<Type Name="MicrosoftLanguageStemmingTokenizer" FullName="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer">
  <TypeSignature Language="C#" Value="public class MicrosoftLanguageStemmingTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MicrosoftLanguageStemmingTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class MicrosoftLanguageStemmingTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type MicrosoftLanguageStemmingTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MicrosoftLanguageStemmingTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a1692-101">Teilt Text mit sprachspezifische Regeln und Wörter auf ihre grundlegenden Formen verringert.</span><span class="sxs-lookup"><span data-stu-id="a1692-101">Divides text using language-specific rules and reduces words to their base forms.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageStemmingTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.#ctor" />
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
            <span data-ttu-id="a1692-102">Initialisiert eine neue Instanz der MicrosoftLanguageStemmingTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a1692-102">Initializes a new instance of the MicrosoftLanguageStemmingTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageStemmingTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; isSearchTokenizer = null, Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; language = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; isSearchTokenizer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null, Optional isSearchTokenizer As Nullable(Of Boolean) = null, Optional language As Nullable(Of MicrosoftStemmingTokenizerLanguage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; -&gt; Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer" Usage="new Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer (name, maxTokenLength, isSearchTokenizer, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSearchTokenizer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="language" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a1692-103">Der Name des tokenizers.</span><span class="sxs-lookup"><span data-stu-id="a1692-103">The name of the tokenizer.</span></span> <span data-ttu-id="a1692-104">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="a1692-104">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxTokenLength"><span data-ttu-id="a1692-105">Die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="a1692-105">The maximum token length.</span></span> <span data-ttu-id="a1692-106">Token, die die maximale Länge überschreiten, werden geteilt.</span><span class="sxs-lookup"><span data-stu-id="a1692-106">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="a1692-107">Maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="a1692-107">Maximum token length that can be used is 300 characters.</span></span> <span data-ttu-id="a1692-108">Token, die länger als 300 Zeichen werden zuerst in Token Länge 300 aufteilen, und anschließend wird jede diese Token aufgeteilt basierend auf den max-token-Länge.</span><span class="sxs-lookup"><span data-stu-id="a1692-108">Tokens longer than 300 characters are first split into tokens of length 300 and then each of those tokens is split based on the max token length set.</span></span> <span data-ttu-id="a1692-109">Standardwert ist</span><span class="sxs-lookup"><span data-stu-id="a1692-109">Default is</span></span>
            255.</param>
        <param name="isSearchTokenizer"><span data-ttu-id="a1692-110">Ein Wert, der angibt, wie der Tokenizer verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a1692-110">A value indicating how the tokenizer is used.</span></span> <span data-ttu-id="a1692-111">Legen Sie auf "true" Wenn verwendet, als die Suche Tokenizer, auf "false" festgelegt werden, wenn als der Volltextindizierung Tokenizer verwendet.</span><span class="sxs-lookup"><span data-stu-id="a1692-111">Set to true if used as the search tokenizer, set to false if used as the indexing tokenizer.</span></span> <span data-ttu-id="a1692-112">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="a1692-112">Default is false.</span></span></param>
        <param name="language"><span data-ttu-id="a1692-113">Die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="a1692-113">The language to use.</span></span> <span data-ttu-id="a1692-114">Die Standardeinstellung ist Englisch.</span><span class="sxs-lookup"><span data-stu-id="a1692-114">The default is English.</span></span>
            <span data-ttu-id="a1692-115">Folgende Werte sind möglich: "Arabische", "Bangla", "Bulgarisch", "Katalanisch", "Kroatisch", "Tschechische", "dänische", "Niederländisch", "english", "Estnisch", "Finnisch", "Französisch", "Deutsch", "Griechisch", "Gujarati", "hebräischen", "Hindi", "Ungarisch", "Isländisch", "Indonesisch", " Italienisch ","Kannada","Lettische","Litauisch","Malaiische","Malayalam","Marathi","NorwegianBokmaal","Polnisch"," Portugiesisch","PortugueseBrazilian","punjabi","Rumänisch","Russisch","SerbianCyrillic","SerbianLatin","Slowakisch","Slowenisch"," Spanisch ","Schwedisch","Tamilische","Telugu","Türkisch","Ukrainische","Urdu"</span><span class="sxs-lookup"><span data-stu-id="a1692-115">Possible values include: 'arabic', 'bangla', 'bulgarian', 'catalan', 'croatian', 'czech', 'danish', 'dutch', 'english', 'estonian', 'finnish', 'french', 'german', 'greek', 'gujarati', 'hebrew', 'hindi', 'hungarian', 'icelandic', 'indonesian', 'italian', 'kannada', 'latvian', 'lithuanian', 'malay', 'malayalam', 'marathi', 'norwegianBokmaal', 'polish', 'portuguese', 'portugueseBrazilian', 'punjabi', 'romanian', 'russian', 'serbianCyrillic', 'serbianLatin', 'slovak', 'slovenian', 'spanish', 'swedish', 'tamil', 'telugu', 'turkish', 'ukrainian', 'urdu'</span></span></param>
        <summary>
            <span data-ttu-id="a1692-116">Initialisiert eine neue Instanz der MicrosoftLanguageStemmingTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a1692-116">Initializes a new instance of the MicrosoftLanguageStemmingTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchTokenizer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSearchTokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSearchTokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.IsSearchTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchTokenizer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSearchTokenizer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.IsSearchTokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSearchTokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1692-117">Ruft ab oder legt einen Wert, der angibt, wie der Tokenizer verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a1692-117">Gets or sets a value indicating how the tokenizer is used.</span></span> <span data-ttu-id="a1692-118">Legen Sie auf "true" Wenn verwendet, als die Suche Tokenizer, auf "false" festgelegt werden, wenn als der Volltextindizierung Tokenizer verwendet.</span><span class="sxs-lookup"><span data-stu-id="a1692-118">Set to true if used as the search tokenizer, set to false if used as the indexing tokenizer.</span></span> <span data-ttu-id="a1692-119">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="a1692-119">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As Nullable(Of MicrosoftStemmingTokenizerLanguage)" />
      <MemberSignature Language="F#" Value="member this.Language : Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Language" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="language")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1692-120">Ruft ab oder legt die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="a1692-120">Gets or sets the language to use.</span></span> <span data-ttu-id="a1692-121">Die Standardeinstellung ist Englisch.</span><span class="sxs-lookup"><span data-stu-id="a1692-121">The default is English.</span></span> <span data-ttu-id="a1692-122">Folgende Werte sind möglich: "Arabische", "Bangla", "Bulgarisch", "Katalanisch", "Kroatisch", "Tschechische", "dänische", "Niederländisch", "english", "Estnisch", "Finnisch", "Französisch", "Deutsch", "Griechisch", "Gujarati", "hebräischen", "Hindi", "Ungarisch", "Isländisch", "Indonesisch", " Italienisch ","Kannada","Lettische","Litauisch","Malaiische","Malayalam","Marathi","NorwegianBokmaal","Polnisch"," Portugiesisch","PortugueseBrazilian","punjabi","Rumänisch","Russisch","SerbianCyrillic","SerbianLatin","Slowakisch","Slowenisch"," Spanisch ","Schwedisch","Tamilische","Telugu","Türkisch","Ukrainische","Urdu"</span><span class="sxs-lookup"><span data-stu-id="a1692-122">Possible values include: 'arabic', 'bangla', 'bulgarian', 'catalan', 'croatian', 'czech', 'danish', 'dutch', 'english', 'estonian', 'finnish', 'french', 'german', 'greek', 'gujarati', 'hebrew', 'hindi', 'hungarian', 'icelandic', 'indonesian', 'italian', 'kannada', 'latvian', 'lithuanian', 'malay', 'malayalam', 'marathi', 'norwegianBokmaal', 'polish', 'portuguese', 'portugueseBrazilian', 'punjabi', 'romanian', 'russian', 'serbianCyrillic', 'serbianLatin', 'slovak', 'slovenian', 'spanish', 'swedish', 'tamil', 'telugu', 'turkish', 'ukrainian', 'urdu'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.MaxTokenLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1692-123">Ruft ab oder legt die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="a1692-123">Gets or sets the maximum token length.</span></span> <span data-ttu-id="a1692-124">Token, die die maximale Länge überschreiten, werden geteilt.</span><span class="sxs-lookup"><span data-stu-id="a1692-124">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="a1692-125">Maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="a1692-125">Maximum token length that can be used is 300 characters.</span></span> <span data-ttu-id="a1692-126">Token, die länger als 300 Zeichen werden zuerst in Token Länge 300 aufteilen, und anschließend wird jede diese Token aufgeteilt basierend auf den max-token-Länge.</span><span class="sxs-lookup"><span data-stu-id="a1692-126">Tokens longer than 300 characters are first split into tokens of length 300 and then each of those tokens is split based on the max token length set.</span></span> <span data-ttu-id="a1692-127">Standardwert ist 255.</span><span class="sxs-lookup"><span data-stu-id="a1692-127">Default is 255.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="microsoftLanguageStemmingTokenizer.Validate " />
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
            <span data-ttu-id="a1692-128">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a1692-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a1692-129">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a1692-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>