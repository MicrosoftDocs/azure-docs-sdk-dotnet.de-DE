<Type Name="ShingleTokenFilter" FullName="Microsoft.Azure.Search.Models.ShingleTokenFilter">
  <TypeSignature Language="C#" Value="public class ShingleTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ShingleTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ShingleTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class ShingleTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type ShingleTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.ShingleTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="50fa8-101">Kombinationen von Token erstellt als ein einzelnes Token.</span><span class="sxs-lookup"><span data-stu-id="50fa8-101">Creates combinations of tokens as a single token.</span></span> <span data-ttu-id="50fa8-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="50fa8-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/shingle/ShingleFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShingleTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ShingleTokenFilter.#ctor" />
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
            <span data-ttu-id="50fa8-103">Initialisiert eine neue Instanz der ShingleTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50fa8-103">Initializes a new instance of the ShingleTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShingleTokenFilter (string name, Nullable&lt;int&gt; maxShingleSize = null, Nullable&lt;int&gt; minShingleSize = null, Nullable&lt;bool&gt; outputUnigrams = null, Nullable&lt;bool&gt; outputUnigramsIfNoShingles = null, string tokenSeparator = null, string filterToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxShingleSize, valuetype System.Nullable`1&lt;int32&gt; minShingleSize, valuetype System.Nullable`1&lt;bool&gt; outputUnigrams, valuetype System.Nullable`1&lt;bool&gt; outputUnigramsIfNoShingles, string tokenSeparator, string filterToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ShingleTokenFilter.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxShingleSize As Nullable(Of Integer) = null, Optional minShingleSize As Nullable(Of Integer) = null, Optional outputUnigrams As Nullable(Of Boolean) = null, Optional outputUnigramsIfNoShingles As Nullable(Of Boolean) = null, Optional tokenSeparator As String = null, Optional filterToken As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ShingleTokenFilter : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Search.Models.ShingleTokenFilter" Usage="new Microsoft.Azure.Search.Models.ShingleTokenFilter (name, maxShingleSize, minShingleSize, outputUnigrams, outputUnigramsIfNoShingles, tokenSeparator, filterToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxShingleSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minShingleSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="outputUnigrams" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outputUnigramsIfNoShingles" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tokenSeparator" Type="System.String" />
        <Parameter Name="filterToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="50fa8-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="50fa8-104">The name of the token filter.</span></span> <span data-ttu-id="50fa8-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="50fa8-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="maxShingleSize"><span data-ttu-id="50fa8-106">Die maximale Shingle Größe.</span><span class="sxs-lookup"><span data-stu-id="50fa8-106">The maximum shingle size.</span></span> <span data-ttu-id="50fa8-107">Standard- und minimale Wert ist 2.</span><span class="sxs-lookup"><span data-stu-id="50fa8-107">Default and minimum value is 2.</span></span></param>
        <param name="minShingleSize"><span data-ttu-id="50fa8-108">Die minimale Shingle Größe.</span><span class="sxs-lookup"><span data-stu-id="50fa8-108">The minimum shingle size.</span></span> <span data-ttu-id="50fa8-109">Standard- und minimale Wert ist 2.</span><span class="sxs-lookup"><span data-stu-id="50fa8-109">Default and minimum value is 2.</span></span> <span data-ttu-id="50fa8-110">Kleiner als der Wert des MaxShingleSize muss sein.</span><span class="sxs-lookup"><span data-stu-id="50fa8-110">Must be less than the value of maxShingleSize.</span></span></param>
        <param name="outputUnigrams"><span data-ttu-id="50fa8-111">Ein Wert, der angibt, ob der Ausgabedatenstrom der Eingabetoken (monogramme) enthält sowie Schindeln.</span><span class="sxs-lookup"><span data-stu-id="50fa8-111">A value indicating whether the output stream will contain the input tokens (unigrams) as well as shingles.</span></span> <span data-ttu-id="50fa8-112">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="50fa8-112">Default is true.</span></span></param>
        <param name="outputUnigramsIfNoShingles"><span data-ttu-id="50fa8-113">Ein Wert, der angibt, ob monogramme für die Fälle ausgegeben, wenn keine Schindeln verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="50fa8-113">A value indicating whether to output unigrams for those times when no shingles are available.</span></span>
            <span data-ttu-id="50fa8-114">Diese Eigenschaft hat Vorrang vor, wenn OutputUnigrams auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="50fa8-114">This property takes precedence when outputUnigrams is set to false.</span></span>
            <span data-ttu-id="50fa8-115">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="50fa8-115">Default is false.</span></span></param>
        <param name="tokenSeparator"><span data-ttu-id="50fa8-116">Die Zeichenfolge, mit der Beitritt zu benachbarte Token ein Shingle bilden.</span><span class="sxs-lookup"><span data-stu-id="50fa8-116">The string to use when joining adjacent tokens to form a shingle.</span></span> <span data-ttu-id="50fa8-117">Standardmäßig wird ein einzelnes Leerzeichen ("").</span><span class="sxs-lookup"><span data-stu-id="50fa8-117">Default is a single space (" ").</span></span></param>
        <param name="filterToken"><span data-ttu-id="50fa8-118">Die Zeichenfolge, die für die einzelnen Positionen einzufügen, zu dem kein Token vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="50fa8-118">The string to insert for each position at which there is no token.</span></span> <span data-ttu-id="50fa8-119">Standard ist ein Unterstrich ("_").</span><span class="sxs-lookup"><span data-stu-id="50fa8-119">Default is an underscore ("_").</span></span></param>
        <summary>
            <span data-ttu-id="50fa8-120">Initialisiert eine neue Instanz der ShingleTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50fa8-120">Initializes a new instance of the ShingleTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterToken">
      <MemberSignature Language="C#" Value="public string FilterToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.FilterToken" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterToken As String" />
      <MemberSignature Language="F#" Value="member this.FilterToken : string with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.FilterToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filterToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-121">Ruft ab oder legt die Zeichenfolge einzufügende für die einzelnen Positionen, an dem keine Token vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="50fa8-121">Gets or sets the string to insert for each position at which there is no token.</span></span> <span data-ttu-id="50fa8-122">Standard ist ein Unterstrich ("_").</span><span class="sxs-lookup"><span data-stu-id="50fa8-122">Default is an underscore ("_").</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxShingleSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxShingleSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxShingleSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.MaxShingleSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxShingleSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxShingleSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.MaxShingleSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxShingleSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-123">Ruft ab oder legt die maximale Shingle Größe fest.</span><span class="sxs-lookup"><span data-stu-id="50fa8-123">Gets or sets the maximum shingle size.</span></span> <span data-ttu-id="50fa8-124">Standard- und minimale Wert ist</span><span class="sxs-lookup"><span data-stu-id="50fa8-124">Default and minimum value is</span></span>
            2.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinShingleSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinShingleSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinShingleSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.MinShingleSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinShingleSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinShingleSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.MinShingleSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minShingleSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-125">Ruft ab oder legt die minimale Shingle Größe fest.</span><span class="sxs-lookup"><span data-stu-id="50fa8-125">Gets or sets the minimum shingle size.</span></span> <span data-ttu-id="50fa8-126">Standard- und minimale Wert ist</span><span class="sxs-lookup"><span data-stu-id="50fa8-126">Default and minimum value is</span></span>
            2. <span data-ttu-id="50fa8-127">Kleiner als der Wert des MaxShingleSize muss sein.</span><span class="sxs-lookup"><span data-stu-id="50fa8-127">Must be less than the value of maxShingleSize.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUnigrams">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OutputUnigrams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OutputUnigrams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.OutputUnigrams" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUnigrams As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OutputUnigrams : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.OutputUnigrams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputUnigrams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-128">Ruft ab oder legt einen Wert, der angibt, ob der Ausgabedatenstrom der Eingabetoken (monogramme) enthält, sowie Schindeln.</span><span class="sxs-lookup"><span data-stu-id="50fa8-128">Gets or sets a value indicating whether the output stream will contain the input tokens (unigrams) as well as shingles.</span></span> <span data-ttu-id="50fa8-129">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="50fa8-129">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUnigramsIfNoShingles">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OutputUnigramsIfNoShingles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OutputUnigramsIfNoShingles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.OutputUnigramsIfNoShingles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUnigramsIfNoShingles As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OutputUnigramsIfNoShingles : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.OutputUnigramsIfNoShingles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputUnigramsIfNoShingles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-130">Ruft ab oder legt einen Wert, der angibt, ob monogramme für die Fälle ausgegeben, wenn keine Schindeln verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="50fa8-130">Gets or sets a value indicating whether to output unigrams for those times when no shingles are available.</span></span> <span data-ttu-id="50fa8-131">Diese Eigenschaft hat Vorrang vor, wenn OutputUnigrams auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="50fa8-131">This property takes precedence when outputUnigrams is set to false.</span></span> <span data-ttu-id="50fa8-132">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="50fa8-132">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenSeparator">
      <MemberSignature Language="C#" Value="public string TokenSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ShingleTokenFilter.TokenSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenSeparator As String" />
      <MemberSignature Language="F#" Value="member this.TokenSeparator : string with get, set" Usage="Microsoft.Azure.Search.Models.ShingleTokenFilter.TokenSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenSeparator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fa8-133">Ruft ab oder legt die Zeichenfolge, mit der Beitritt zu benachbarte Token ein Shingle bilden.</span><span class="sxs-lookup"><span data-stu-id="50fa8-133">Gets or sets the string to use when joining adjacent tokens to form a shingle.</span></span> <span data-ttu-id="50fa8-134">Standardmäßig wird ein einzelnes Leerzeichen ("").</span><span class="sxs-lookup"><span data-stu-id="50fa8-134">Default is a single space (" ").</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ShingleTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="shingleTokenFilter.Validate " />
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
            <span data-ttu-id="50fa8-135">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="50fa8-135">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="50fa8-136">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="50fa8-136">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>