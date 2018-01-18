<Type Name="PatternAnalyzer" FullName="Microsoft.Azure.Search.Models.PatternAnalyzer">
  <TypeSignature Language="C#" Value="public class PatternAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type PatternAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ff4de-101">Flexible trennt Text in Begriffe über Muster eines regulären Ausdrucks ein.</span><span class="sxs-lookup"><span data-stu-id="ff4de-101">Flexibly separates text into terms via a regular expression pattern.</span></span>
            <span data-ttu-id="ff4de-102">Diese Analyzer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="ff4de-102">This analyzer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/PatternAnalyzer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternAnalyzer.#ctor" />
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
            <span data-ttu-id="ff4de-103">Initialisiert eine neue Instanz der PatternAnalyzer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ff4de-103">Initializes a new instance of the PatternAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternAnalyzer (string name, Nullable&lt;bool&gt; lowerCaseTerms = null, string pattern = null, Microsoft.Azure.Search.Models.RegexFlags flags = null, System.Collections.Generic.IList&lt;string&gt; stopwords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; lowerCaseTerms, string pattern, class Microsoft.Azure.Search.Models.RegexFlags flags, class System.Collections.Generic.IList`1&lt;string&gt; stopwords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternAnalyzer.#ctor(System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Search.Models.RegexFlags,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional lowerCaseTerms As Nullable(Of Boolean) = null, Optional pattern As String = null, Optional flags As RegexFlags = null, Optional stopwords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternAnalyzer : string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Search.Models.RegexFlags * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.PatternAnalyzer" Usage="new Microsoft.Azure.Search.Models.PatternAnalyzer (name, lowerCaseTerms, pattern, flags, stopwords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="lowerCaseTerms" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="flags" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ff4de-104">Der Name des Analyzers.</span><span class="sxs-lookup"><span data-stu-id="ff4de-104">The name of the analyzer.</span></span> <span data-ttu-id="ff4de-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="ff4de-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="lowerCaseTerms"><span data-ttu-id="ff4de-106">Ein Wert, der angibt, ob die Begriffe untere-Schreibweise verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff4de-106">A value indicating whether terms should be lower-cased.</span></span> <span data-ttu-id="ff4de-107">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="ff4de-107">Default is true.</span></span></param>
        <param name="pattern"><span data-ttu-id="ff4de-108">Muster eines regulären Ausdrucks mit token-Trennzeichen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ff4de-108">A regular expression pattern to match token separators.</span></span> <span data-ttu-id="ff4de-109">Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="ff4de-109">Default is an expression that matches one or more whitespace characters.</span></span></param>
        <param name="flags"><span data-ttu-id="ff4de-110">Flags für reguläre Ausdrücke.</span><span class="sxs-lookup"><span data-stu-id="ff4de-110">Regular expression flags.</span></span></param>
        <param name="stopwords"><span data-ttu-id="ff4de-111">Eine Liste von Stoppwörtern.</span><span class="sxs-lookup"><span data-stu-id="ff4de-111">A list of stopwords.</span></span></param>
        <summary>
            <span data-ttu-id="ff4de-112">Initialisiert eine neue Instanz der PatternAnalyzer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ff4de-112">Initializes a new instance of the PatternAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RegexFlags Flags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.RegexFlags Flags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternAnalyzer.Flags" />
      <MemberSignature Language="VB.NET" Value="Public Property Flags As RegexFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : Microsoft.Azure.Search.Models.RegexFlags with get, set" Usage="Microsoft.Azure.Search.Models.PatternAnalyzer.Flags" />
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
            <span data-ttu-id="ff4de-113">Ermittelt oder definiert Flags für reguläre Ausdrücke.</span><span class="sxs-lookup"><span data-stu-id="ff4de-113">Gets or sets regular expression flags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowerCaseTerms">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LowerCaseTerms { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LowerCaseTerms" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternAnalyzer.LowerCaseTerms" />
      <MemberSignature Language="VB.NET" Value="Public Property LowerCaseTerms As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LowerCaseTerms : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternAnalyzer.LowerCaseTerms" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lowercase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff4de-114">Ruft ab oder legt einen Wert, der angibt, ob die Begriffe untere-Schreibweise verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff4de-114">Gets or sets a value indicating whether terms should be lower-cased.</span></span> <span data-ttu-id="ff4de-115">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="ff4de-115">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternAnalyzer.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternAnalyzer.Pattern" />
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
            <span data-ttu-id="ff4de-116">Ermittelt oder definiert ein Muster eines regulären Ausdrucks token-Trennzeichen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ff4de-116">Gets or sets a regular expression pattern to match token separators.</span></span> <span data-ttu-id="ff4de-117">Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="ff4de-117">Default is an expression that matches one or more whitespace characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternAnalyzer.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternAnalyzer.Stopwords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff4de-118">Ruft ab oder legt eine Liste von Stoppwörtern.</span><span class="sxs-lookup"><span data-stu-id="ff4de-118">Gets or sets a list of stopwords.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternAnalyzer.Validate " />
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
            <span data-ttu-id="ff4de-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ff4de-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ff4de-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ff4de-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>