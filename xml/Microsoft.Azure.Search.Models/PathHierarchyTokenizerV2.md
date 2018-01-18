<Type Name="PathHierarchyTokenizerV2" FullName="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2">
  <TypeSignature Language="C#" Value="public class PathHierarchyTokenizerV2 : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PathHierarchyTokenizerV2 extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2" />
  <TypeSignature Language="VB.NET" Value="Public Class PathHierarchyTokenizerV2&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type PathHierarchyTokenizerV2 = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PathHierarchyTokenizerV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="235ba-101">Der Tokenizer für Path-ähnliche Hierarchien.</span><span class="sxs-lookup"><span data-stu-id="235ba-101">Tokenizer for path-like hierarchies.</span></span> <span data-ttu-id="235ba-102">Diese Tokenizer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="235ba-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/path/PathHierarchyTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PathHierarchyTokenizerV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.#ctor" />
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
            <span data-ttu-id="235ba-103">Initialisiert eine neue Instanz der PathHierarchyTokenizerV2-Klasse.</span><span class="sxs-lookup"><span data-stu-id="235ba-103">Initializes a new instance of the PathHierarchyTokenizerV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PathHierarchyTokenizerV2 (string name, Nullable&lt;char&gt; delimiter = null, Nullable&lt;char&gt; replacement = null, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; reverseTokenOrder = null, Nullable&lt;int&gt; numberOfTokensToSkip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;char&gt; delimiter, valuetype System.Nullable`1&lt;char&gt; replacement, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; reverseTokenOrder, valuetype System.Nullable`1&lt;int32&gt; numberOfTokensToSkip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.#ctor(System.String,System.Nullable{System.Char},System.Nullable{System.Char},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional delimiter As Nullable(Of Char) = null, Optional replacement As Nullable(Of Char) = null, Optional maxTokenLength As Nullable(Of Integer) = null, Optional reverseTokenOrder As Nullable(Of Boolean) = null, Optional numberOfTokensToSkip As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2 : string * Nullable&lt;char&gt; * Nullable&lt;char&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2" Usage="new Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2 (name, delimiter, replacement, maxTokenLength, reverseTokenOrder, numberOfTokensToSkip)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="delimiter" Type="System.Nullable&lt;System.Char&gt;" />
        <Parameter Name="replacement" Type="System.Nullable&lt;System.Char&gt;" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="reverseTokenOrder" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="numberOfTokensToSkip" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="235ba-104">Der Name des tokenizers.</span><span class="sxs-lookup"><span data-stu-id="235ba-104">The name of the tokenizer.</span></span> <span data-ttu-id="235ba-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="235ba-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="delimiter"><span data-ttu-id="235ba-106">Das Trennzeichen verwenden.</span><span class="sxs-lookup"><span data-stu-id="235ba-106">The delimiter character to use.</span></span> <span data-ttu-id="235ba-107">Standardwert ist "/".</span><span class="sxs-lookup"><span data-stu-id="235ba-107">Default is "/".</span></span></param>
        <param name="replacement"><span data-ttu-id="235ba-108">Ein Wert festgelegt ist, ersetzt das Trennzeichen.</span><span class="sxs-lookup"><span data-stu-id="235ba-108">A value that, if set, replaces the delimiter character.</span></span> <span data-ttu-id="235ba-109">Standardwert ist "/".</span><span class="sxs-lookup"><span data-stu-id="235ba-109">Default is "/".</span></span></param>
        <param name="maxTokenLength"><span data-ttu-id="235ba-110">Die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="235ba-110">The maximum token length.</span></span> <span data-ttu-id="235ba-111">Standard- und ist 300.</span><span class="sxs-lookup"><span data-stu-id="235ba-111">Default and maximum is 300.</span></span></param>
        <param name="reverseTokenOrder"><span data-ttu-id="235ba-112">Ein Wert, der angibt, ob zum Generieren von Token in umgekehrter Reihenfolge.</span><span class="sxs-lookup"><span data-stu-id="235ba-112">A value indicating whether to generate tokens in reverse order.</span></span> <span data-ttu-id="235ba-113">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="235ba-113">Default is false.</span></span></param>
        <param name="numberOfTokensToSkip"><span data-ttu-id="235ba-114">Die Anzahl der anfänglichen Token zu überspringen.</span><span class="sxs-lookup"><span data-stu-id="235ba-114">The number of initial tokens to skip.</span></span> <span data-ttu-id="235ba-115">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="235ba-115">Default is 0.</span></span></param>
        <summary>
            <span data-ttu-id="235ba-116">Initialisiert eine neue Instanz der PathHierarchyTokenizerV2-Klasse.</span><span class="sxs-lookup"><span data-stu-id="235ba-116">Initializes a new instance of the PathHierarchyTokenizerV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public Nullable&lt;char&gt; Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;char&gt; Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Nullable(Of Char)" />
      <MemberSignature Language="F#" Value="member this.Delimiter : Nullable&lt;char&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="delimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Char&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="235ba-117">Ermittelt oder definiert das Trennzeichen verwenden.</span><span class="sxs-lookup"><span data-stu-id="235ba-117">Gets or sets the delimiter character to use.</span></span> <span data-ttu-id="235ba-118">Standardwert ist "/".</span><span class="sxs-lookup"><span data-stu-id="235ba-118">Default is "/".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.MaxTokenLength" />
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
            <span data-ttu-id="235ba-119">Ruft ab oder legt die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="235ba-119">Gets or sets the maximum token length.</span></span> <span data-ttu-id="235ba-120">Standard- und ist 300.</span><span class="sxs-lookup"><span data-stu-id="235ba-120">Default and maximum is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfTokensToSkip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfTokensToSkip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfTokensToSkip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.NumberOfTokensToSkip" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfTokensToSkip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfTokensToSkip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.NumberOfTokensToSkip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skip")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="235ba-121">Ruft ab oder legt die Anzahl der anfänglichen Token zu überspringen.</span><span class="sxs-lookup"><span data-stu-id="235ba-121">Gets or sets the number of initial tokens to skip.</span></span> <span data-ttu-id="235ba-122">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="235ba-122">Default is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replacement">
      <MemberSignature Language="C#" Value="public Nullable&lt;char&gt; Replacement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;char&gt; Replacement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Replacement" />
      <MemberSignature Language="VB.NET" Value="Public Property Replacement As Nullable(Of Char)" />
      <MemberSignature Language="F#" Value="member this.Replacement : Nullable&lt;char&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Replacement" />
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
        <ReturnType>System.Nullable&lt;System.Char&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="235ba-123">Ruft ab oder legt einen Wert fest, die, wenn festgelegt ist, ersetzt das Trennzeichen.</span><span class="sxs-lookup"><span data-stu-id="235ba-123">Gets or sets a value that, if set, replaces the delimiter character.</span></span> <span data-ttu-id="235ba-124">Standardwert ist "/".</span><span class="sxs-lookup"><span data-stu-id="235ba-124">Default is "/".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseTokenOrder">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReverseTokenOrder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReverseTokenOrder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.ReverseTokenOrder" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseTokenOrder As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReverseTokenOrder : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.ReverseTokenOrder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverse")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="235ba-125">Ruft ab oder legt einen Wert, der angibt, ob zum Generieren von Token in umgekehrter Reihenfolge.</span><span class="sxs-lookup"><span data-stu-id="235ba-125">Gets or sets a value indicating whether to generate tokens in reverse order.</span></span> <span data-ttu-id="235ba-126">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="235ba-126">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="pathHierarchyTokenizerV2.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="235ba-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="235ba-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="235ba-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="235ba-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>