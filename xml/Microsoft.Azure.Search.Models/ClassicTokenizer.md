<Type Name="ClassicTokenizer" FullName="Microsoft.Azure.Search.Models.ClassicTokenizer">
  <TypeSignature Language="C#" Value="public class ClassicTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClassicTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ClassicTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class ClassicTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type ClassicTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.ClassicTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c5fce-101">Grammatik basierende Tokenizer, der für die Verarbeitung von Dokumenten für die meisten europäischen Sprachen geeignet ist.</span><span class="sxs-lookup"><span data-stu-id="c5fce-101">Grammar-based tokenizer that is suitable for processing most European-language documents.</span></span> <span data-ttu-id="c5fce-102">Diese Tokenizer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="c5fce-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/ClassicTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClassicTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ClassicTokenizer.#ctor" />
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
            <span data-ttu-id="c5fce-103">Initialisiert eine neue Instanz der ClassicTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c5fce-103">Initializes a new instance of the ClassicTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClassicTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ClassicTokenizer.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ClassicTokenizer : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.ClassicTokenizer" Usage="new Microsoft.Azure.Search.Models.ClassicTokenizer (name, maxTokenLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c5fce-104">Der Name des tokenizers.</span><span class="sxs-lookup"><span data-stu-id="c5fce-104">The name of the tokenizer.</span></span> <span data-ttu-id="c5fce-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="c5fce-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxTokenLength"><span data-ttu-id="c5fce-106">Die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="c5fce-106">The maximum token length.</span></span> <span data-ttu-id="c5fce-107">Standardwert ist</span><span class="sxs-lookup"><span data-stu-id="c5fce-107">Default is</span></span>
            255. <span data-ttu-id="c5fce-108">Token, die die maximale Länge überschreiten, werden geteilt.</span><span class="sxs-lookup"><span data-stu-id="c5fce-108">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="c5fce-109">Die maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="c5fce-109">The maximum token length that can be used is 300 characters.</span></span></param>
        <summary>
            <span data-ttu-id="c5fce-110">Initialisiert eine neue Instanz der ClassicTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c5fce-110">Initializes a new instance of the ClassicTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ClassicTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ClassicTokenizer.MaxTokenLength" />
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
            <span data-ttu-id="c5fce-111">Ruft ab oder legt die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="c5fce-111">Gets or sets the maximum token length.</span></span> <span data-ttu-id="c5fce-112">Standardwert ist 255.</span><span class="sxs-lookup"><span data-stu-id="c5fce-112">Default is 255.</span></span> <span data-ttu-id="c5fce-113">Token, die die maximale Länge überschreiten, werden geteilt.</span><span class="sxs-lookup"><span data-stu-id="c5fce-113">Tokens longer than the maximum length are split.</span></span> <span data-ttu-id="c5fce-114">Die maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen.</span><span class="sxs-lookup"><span data-stu-id="c5fce-114">The maximum token length that can be used is 300 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ClassicTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="classicTokenizer.Validate " />
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
            <span data-ttu-id="c5fce-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c5fce-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c5fce-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c5fce-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>