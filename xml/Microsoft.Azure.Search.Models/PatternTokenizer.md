<Type Name="PatternTokenizer" FullName="Microsoft.Azure.Search.Models.PatternTokenizer">
  <TypeSignature Language="C#" Value="public class PatternTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type PatternTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="90687-101">Der Tokenizer, der Regex-Mustervergleich verwendet, um unterschiedliche Token zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="90687-101">Tokenizer that uses regex pattern matching to construct distinct tokens.</span></span> <span data-ttu-id="90687-102">Diese Tokenizer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="90687-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor" />
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
            <span data-ttu-id="90687-103">Initialisiert eine neue Instanz der PatternTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="90687-103">Initializes a new instance of the PatternTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer (string name, string pattern = null, Microsoft.Azure.Search.Models.RegexFlags flags = null, Nullable&lt;int&gt; group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, class Microsoft.Azure.Search.Models.RegexFlags flags, valuetype System.Nullable`1&lt;int32&gt; group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor(System.String,System.String,Microsoft.Azure.Search.Models.RegexFlags,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional pattern As String = null, Optional flags As RegexFlags = null, Optional group As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternTokenizer : string * string * Microsoft.Azure.Search.Models.RegexFlags * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.PatternTokenizer" Usage="new Microsoft.Azure.Search.Models.PatternTokenizer (name, pattern, flags, group)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="flags" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="group" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="90687-104">Der Name des tokenizers.</span><span class="sxs-lookup"><span data-stu-id="90687-104">The name of the tokenizer.</span></span> <span data-ttu-id="90687-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="90687-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="pattern"><span data-ttu-id="90687-106">Muster eines regulären Ausdrucks mit token-Trennzeichen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="90687-106">A regular expression pattern to match token separators.</span></span> <span data-ttu-id="90687-107">Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="90687-107">Default is an expression that matches one or more whitespace characters.</span></span></param>
        <param name="flags"><span data-ttu-id="90687-108">Flags für reguläre Ausdrücke.</span><span class="sxs-lookup"><span data-stu-id="90687-108">Regular expression flags.</span></span></param>
        <param name="group"><span data-ttu-id="90687-109">Die nullbasierte Ordnungszahl der entsprechenden Gruppe im Muster regulären Ausdrucks, in Token zu extrahieren.</span><span class="sxs-lookup"><span data-stu-id="90687-109">The zero-based ordinal of the matching group in the regular expression pattern to extract into tokens.</span></span> <span data-ttu-id="90687-110">Verwenden Sie-1. wenn das gesamte Muster zu verwenden, um die Eingabe in Tokens, unabhängig von der übereinstimmenden Gruppen aufgeteilt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="90687-110">Use -1 if you want to use the entire pattern to split the input into tokens, irrespective of matching groups.</span></span> <span data-ttu-id="90687-111">Standard ist-1.</span><span class="sxs-lookup"><span data-stu-id="90687-111">Default is -1.</span></span></param>
        <summary>
            <span data-ttu-id="90687-112">Initialisiert eine neue Instanz der PatternTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="90687-112">Initializes a new instance of the PatternTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RegexFlags Flags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.RegexFlags Flags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberSignature Language="VB.NET" Value="Public Property Flags As RegexFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : Microsoft.Azure.Search.Models.RegexFlags with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="flags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90687-113">Ermittelt oder definiert Flags für reguläre Ausdrücke.</span><span class="sxs-lookup"><span data-stu-id="90687-113">Gets or sets regular expression flags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Group { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberSignature Language="VB.NET" Value="Public Property Group As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Group : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="group")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90687-114">Ruft ab oder legt die nullbasierte Ordnungszahl der entsprechenden Gruppe im Muster regulären Ausdrucks, in Token zu extrahieren.</span><span class="sxs-lookup"><span data-stu-id="90687-114">Gets or sets the zero-based ordinal of the matching group in the regular expression pattern to extract into tokens.</span></span> <span data-ttu-id="90687-115">Verwenden Sie-1. wenn das gesamte Muster zu verwenden, um die Eingabe in Tokens, unabhängig von der übereinstimmenden Gruppen aufgeteilt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="90687-115">Use -1 if you want to use the entire pattern to split the input into tokens, irrespective of matching groups.</span></span> <span data-ttu-id="90687-116">Standard ist-1.</span><span class="sxs-lookup"><span data-stu-id="90687-116">Default is -1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90687-117">Ermittelt oder definiert ein Muster eines regulären Ausdrucks token-Trennzeichen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="90687-117">Gets or sets a regular expression pattern to match token separators.</span></span> <span data-ttu-id="90687-118">Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="90687-118">Default is an expression that matches one or more whitespace characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternTokenizer.Validate " />
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
            <span data-ttu-id="90687-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="90687-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="90687-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="90687-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>