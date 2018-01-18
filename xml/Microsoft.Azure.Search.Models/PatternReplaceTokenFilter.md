<Type Name="PatternReplaceTokenFilter" FullName="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter">
  <TypeSignature Language="C#" Value="public class PatternReplaceTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternReplaceTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternReplaceTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PatternReplaceTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternReplaceTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0190d-101">Ein Zeichen-Filter, der Zeichen in der Eingabezeichenfolge ersetzt.</span><span class="sxs-lookup"><span data-stu-id="0190d-101">A character filter that replaces characters in the input string.</span></span> <span data-ttu-id="0190d-102">Er verwendet einen regulären Ausdruck zur Identifizierung von Zeichensequenzen erhalten bleiben und einem Ersetzungsmuster zum Identifizieren von Zeichen ersetzen.</span><span class="sxs-lookup"><span data-stu-id="0190d-102">It uses a regular expression to identify character sequences to preserve and a replacement pattern to identify characters to replace.</span></span> <span data-ttu-id="0190d-103">Beispielsweise Muster zugewiesen Eingabetext "aa-bb-aa-bb", "(aa)\s+(bb)", und ersetzen "$1#$ 2", "aa #bb aa #bb" ergeben würde.</span><span class="sxs-lookup"><span data-stu-id="0190d-103">For example, given the input text "aa bb aa bb", pattern "(aa)\s+(bb)", and replacement "$1#$2", the result would be "aa#bb aa#bb".</span></span> <span data-ttu-id="0190d-104">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="0190d-104">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternReplaceFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.#ctor" />
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
            <span data-ttu-id="0190d-105">Initialisiert eine neue Instanz der PatternReplaceTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0190d-105">Initializes a new instance of the PatternReplaceTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceTokenFilter (string name, string pattern, string replacement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, string replacement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, pattern As String, replacement As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternReplaceTokenFilter : string * string * string -&gt; Microsoft.Azure.Search.Models.PatternReplaceTokenFilter" Usage="new Microsoft.Azure.Search.Models.PatternReplaceTokenFilter (name, pattern, replacement)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="replacement" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0190d-106">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="0190d-106">The name of the token filter.</span></span> <span data-ttu-id="0190d-107">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="0190d-107">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="pattern"><span data-ttu-id="0190d-108">Das Muster eines regulären Ausdrucks.</span><span class="sxs-lookup"><span data-stu-id="0190d-108">A regular expression pattern.</span></span></param>
        <param name="replacement"><span data-ttu-id="0190d-109">Der Ersetzungstext.</span><span class="sxs-lookup"><span data-stu-id="0190d-109">The replacement text.</span></span></param>
        <summary>
            <span data-ttu-id="0190d-110">Initialisiert eine neue Instanz der PatternReplaceTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0190d-110">Initializes a new instance of the PatternReplaceTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Pattern" />
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
            <span data-ttu-id="0190d-111">Ruft ab, oder legt ihn fest Muster eines regulären Ausdrucks.</span><span class="sxs-lookup"><span data-stu-id="0190d-111">Gets or sets a regular expression pattern.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replacement">
      <MemberSignature Language="C#" Value="public string Replacement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Replacement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Replacement" />
      <MemberSignature Language="VB.NET" Value="Public Property Replacement As String" />
      <MemberSignature Language="F#" Value="member this.Replacement : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Replacement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replacement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0190d-112">Ruft ab oder legt den Ersetzungstext.</span><span class="sxs-lookup"><span data-stu-id="0190d-112">Gets or sets the replacement text.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternReplaceTokenFilter.Validate " />
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
            <span data-ttu-id="0190d-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0190d-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0190d-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0190d-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>