<Type Name="WordDelimiterTokenFilter" FullName="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter">
  <TypeSignature Language="C#" Value="public class WordDelimiterTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WordDelimiterTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class WordDelimiterTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type WordDelimiterTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.WordDelimiterTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3a3f4-101">Subwords Wörter teilt, und führt optionale Transformationen auf Subword Gruppen.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-101">Splits words into subwords and performs optional transformations on subword groups.</span></span> <span data-ttu-id="3a3f4-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/WordDelimiterFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor" />
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
            <span data-ttu-id="3a3f4-103">Initialisiert eine neue Instanz der WordDelimiterTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-103">Initializes a new instance of the WordDelimiterTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter (string name, Nullable&lt;bool&gt; generateWordParts = null, Nullable&lt;bool&gt; generateNumberParts = null, Nullable&lt;bool&gt; catenateWords = null, Nullable&lt;bool&gt; catenateNumbers = null, Nullable&lt;bool&gt; catenateAll = null, Nullable&lt;bool&gt; splitOnCaseChange = null, Nullable&lt;bool&gt; preserveOriginal = null, Nullable&lt;bool&gt; splitOnNumerics = null, Nullable&lt;bool&gt; stemEnglishPossessive = null, System.Collections.Generic.IList&lt;string&gt; protectedWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; generateWordParts, valuetype System.Nullable`1&lt;bool&gt; generateNumberParts, valuetype System.Nullable`1&lt;bool&gt; catenateWords, valuetype System.Nullable`1&lt;bool&gt; catenateNumbers, valuetype System.Nullable`1&lt;bool&gt; catenateAll, valuetype System.Nullable`1&lt;bool&gt; splitOnCaseChange, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal, valuetype System.Nullable`1&lt;bool&gt; splitOnNumerics, valuetype System.Nullable`1&lt;bool&gt; stemEnglishPossessive, class System.Collections.Generic.IList`1&lt;string&gt; protectedWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional generateWordParts As Nullable(Of Boolean) = null, Optional generateNumberParts As Nullable(Of Boolean) = null, Optional catenateWords As Nullable(Of Boolean) = null, Optional catenateNumbers As Nullable(Of Boolean) = null, Optional catenateAll As Nullable(Of Boolean) = null, Optional splitOnCaseChange As Nullable(Of Boolean) = null, Optional preserveOriginal As Nullable(Of Boolean) = null, Optional splitOnNumerics As Nullable(Of Boolean) = null, Optional stemEnglishPossessive As Nullable(Of Boolean) = null, Optional protectedWords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter : string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" Usage="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter (name, generateWordParts, generateNumberParts, catenateWords, catenateNumbers, catenateAll, splitOnCaseChange, preserveOriginal, splitOnNumerics, stemEnglishPossessive, protectedWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="generateWordParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="generateNumberParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateWords" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateNumbers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateAll" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnCaseChange" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnNumerics" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="stemEnglishPossessive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="protectedWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3a3f4-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-104">The name of the token filter.</span></span> <span data-ttu-id="3a3f4-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="generateWordParts"><span data-ttu-id="3a3f4-106">Ein Wert, der angibt, ob Rahmen Wörter zu generieren.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-106">A value indicating whether to generate part words.</span></span> <span data-ttu-id="3a3f4-107">Wenn festgelegt, Ursachen Teile von Wörtern, die generiert werden. So wird z. B. "AzureSearch", "Azure" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-107">If set, causes parts of words to be generated; for example "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="3a3f4-108">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-108">Default is true.</span></span></param>
        <param name="generateNumberParts"><span data-ttu-id="3a3f4-109">Ein Wert, der angibt, ob Anzahl Subwords zu generieren.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-109">A value indicating whether to generate number subwords.</span></span> <span data-ttu-id="3a3f4-110">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-110">Default is true.</span></span></param>
        <param name="catenateWords"><span data-ttu-id="3a3f4-111">Ein Wert, der angibt, ob die maximale Ausführungen des Word-Teile catenated werden werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-111">A value indicating whether maximum runs of word parts will be catenated.</span></span> <span data-ttu-id="3a3f4-112">Wenn diese Option festgelegt ist z. B. "true", "Azure Search" wird "AzureSearch".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-112">For example, if this is set to true, "Azure-Search" becomes "AzureSearch".</span></span> <span data-ttu-id="3a3f4-113">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-113">Default is false.</span></span></param>
        <param name="catenateNumbers"><span data-ttu-id="3a3f4-114">Ein Wert, der angibt, ob die maximale Anzahl von Teilen ausgeführt wird, wird catenated sein.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-114">A value indicating whether maximum runs of number parts will be catenated.</span></span> <span data-ttu-id="3a3f4-115">Wenn dies auf "true", "1-2" festgelegt ist wird z. B. "12".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-115">For example, if this is set to true, "1-2" becomes "12".</span></span> <span data-ttu-id="3a3f4-116">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-116">Default is false.</span></span></param>
        <param name="catenateAll"><span data-ttu-id="3a3f4-117">Ein Wert, der angibt, ob alle Subword Teile catenated werden werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-117">A value indicating whether all subword parts will be catenated.</span></span> <span data-ttu-id="3a3f4-118">Wenn diese Option festgelegt ist z. B. "true", "Azure-Suche-1" wird "AzureSearch1".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-118">For example, if this is set to true, "Azure-Search-1" becomes "AzureSearch1".</span></span> <span data-ttu-id="3a3f4-119">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-119">Default is false.</span></span></param>
        <param name="splitOnCaseChange"><span data-ttu-id="3a3f4-120">Ein Wert, der angibt, ob Wörter auf CaseChange teilen.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-120">A value indicating whether to split words on caseChange.</span></span> <span data-ttu-id="3a3f4-121">Wenn diese Option festgelegt ist z. B. "true", "AzureSearch" wird "Azure" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-121">For example, if this is set to true, "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="3a3f4-122">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-122">Default is true.</span></span></param>
        <param name="preserveOriginal"><span data-ttu-id="3a3f4-123">Ein Wert, der angibt, ob die ursprünglichen Wörter werden beibehalten und die Liste der Subword hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-123">A value indicating whether original words will be preserved and added to the subword list.</span></span> <span data-ttu-id="3a3f4-124">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-124">Default is false.</span></span></param>
        <param name="splitOnNumerics"><span data-ttu-id="3a3f4-125">Ein Wert, der angibt, ob anhand von Zahlen unterteilt werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-125">A value indicating whether to split on numbers.</span></span> <span data-ttu-id="3a3f4-126">Wenn diese Option festgelegt ist z. B. "true", "Azure1Search" wird "Azure", "1" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-126">For example, if this is set to true, "Azure1Search" becomes "Azure" "1" "Search".</span></span> <span data-ttu-id="3a3f4-127">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-127">Default is true.</span></span></param>
        <param name="stemEnglishPossessive"><span data-ttu-id="3a3f4-128">Ein Wert, der angibt, ob für jede Subword nachfolgende "des" zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-128">A value indicating whether to remove trailing "'s" for each subword.</span></span> <span data-ttu-id="3a3f4-129">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-129">Default is true.</span></span></param>
        <param name="protectedWords"><span data-ttu-id="3a3f4-130">Eine Liste mit Token zu verhindern, dass getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-130">A list of tokens to protect from being delimited.</span></span></param>
        <summary>
            <span data-ttu-id="3a3f4-131">Initialisiert eine neue Instanz der WordDelimiterTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-131">Initializes a new instance of the WordDelimiterTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateAll">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateAll { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateAll" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateAll As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateAll : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateAll")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-132">Ruft ab oder legt einen Wert, der angibt, ob alle Subword Teile catenated werden werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-132">Gets or sets a value indicating whether all subword parts will be catenated.</span></span> <span data-ttu-id="3a3f4-133">Wenn diese Option festgelegt ist z. B. "true", "Azure-Suche-1" wird "AzureSearch1".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-133">For example, if this is set to true, "Azure-Search-1" becomes "AzureSearch1".</span></span> <span data-ttu-id="3a3f4-134">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-134">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateNumbers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateNumbers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateNumbers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateNumbers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateNumbers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateNumbers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-135">Ruft ab oder legt einen Wert, der angibt, ob die maximale ausgeführt wird, der Anzahl der Teile catenated werden werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-135">Gets or sets a value indicating whether maximum runs of number parts will be catenated.</span></span> <span data-ttu-id="3a3f4-136">Wenn dies auf "true", "1-2" festgelegt ist wird z. B. "12".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-136">For example, if this is set to true, "1-2" becomes "12".</span></span> <span data-ttu-id="3a3f4-137">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-137">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-138">Ruft ab oder legt einen Wert, der angibt, ob die maximale Ausführungen des Word-Teile catenated werden werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-138">Gets or sets a value indicating whether maximum runs of word parts will be catenated.</span></span> <span data-ttu-id="3a3f4-139">Wenn diese Option festgelegt ist z. B. "true", "Azure Search" wird "AzureSearch".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-139">For example, if this is set to true, "Azure-Search" becomes "AzureSearch".</span></span> <span data-ttu-id="3a3f4-140">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-140">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateNumberParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateNumberParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateNumberParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateNumberParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateNumberParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateNumberParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-141">Ruft ab oder legt einen Wert, der angibt, ob Anzahl Subwords generiert.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-141">Gets or sets a value indicating whether to generate number subwords.</span></span> <span data-ttu-id="3a3f4-142">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-142">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateWordParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateWordParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateWordParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateWordParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateWordParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateWordParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-143">Ruft ab oder legt einen Wert, der angibt, ob Rahmen Wörter zu generieren.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-143">Gets or sets a value indicating whether to generate part words.</span></span> <span data-ttu-id="3a3f4-144">Wenn festgelegt, Ursachen Teile von Wörtern, die generiert werden. So wird z. B. "AzureSearch", "Azure" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-144">If set, causes parts of words to be generated; for example "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="3a3f4-145">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-145">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-146">Ruft ab oder legt einen Wert, der angibt, ob die ursprünglichen Wörter werden beibehalten und die Liste der Subword hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-146">Gets or sets a value indicating whether original words will be preserved and added to the subword list.</span></span> <span data-ttu-id="3a3f4-147">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-147">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ProtectedWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ProtectedWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ProtectedWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-148">Ruft ab oder legt eine Liste mit Token zu verhindern, dass getrennt wird.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-148">Gets or sets a list of tokens to protect from being delimited.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnCaseChange">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnCaseChange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnCaseChange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnCaseChange As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnCaseChange : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnCaseChange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-149">Ruft ab oder legt einen Wert, der angibt, ob zum Aufteilen von Wörtern bei CaseChange fest.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-149">Gets or sets a value indicating whether to split words on caseChange.</span></span> <span data-ttu-id="3a3f4-150">Wenn diese Option festgelegt ist z. B. "true", "AzureSearch" wird "Azure" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-150">For example, if this is set to true, "AzureSearch" becomes "Azure" "Search".</span></span> <span data-ttu-id="3a3f4-151">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-151">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnNumerics">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnNumerics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnNumerics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnNumerics As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnNumerics : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnNumerics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-152">Ruft ab oder legt einen Wert, der angibt, ob anhand von Zahlen unterteilt werden.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-152">Gets or sets a value indicating whether to split on numbers.</span></span> <span data-ttu-id="3a3f4-153">Wenn diese Option festgelegt ist z. B. "true", "Azure1Search" wird "Azure", "1" "Suchen".</span><span class="sxs-lookup"><span data-stu-id="3a3f4-153">For example, if this is set to true, "Azure1Search" becomes "Azure" "1" "Search".</span></span> <span data-ttu-id="3a3f4-154">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-154">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StemEnglishPossessive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StemEnglishPossessive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StemEnglishPossessive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberSignature Language="VB.NET" Value="Public Property StemEnglishPossessive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StemEnglishPossessive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stemEnglishPossessive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3f4-155">Ruft ab oder legt einen Wert, der angibt, ob für jede Subword nachfolgende "des" entfernen.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-155">Gets or sets a value indicating whether to remove trailing "'s" for each subword.</span></span> <span data-ttu-id="3a3f4-156">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-156">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="wordDelimiterTokenFilter.Validate " />
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
            <span data-ttu-id="3a3f4-157">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3a3f4-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3a3f4-158">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3a3f4-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>