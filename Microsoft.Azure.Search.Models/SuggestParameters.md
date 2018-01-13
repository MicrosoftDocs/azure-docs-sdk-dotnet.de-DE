<Type Name="SuggestParameters" FullName="Microsoft.Azure.Search.Models.SuggestParameters">
  <TypeSignature Language="C#" Value="public class SuggestParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SuggestParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SuggestParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SuggestParameters" />
  <TypeSignature Language="F#" Value="type SuggestParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f54f5-101">Parameter zum Filtern, sortieren, Fuzzyübereinstimmung und andere Vorschläge Abfragen Verhalten.</span><span class="sxs-lookup"><span data-stu-id="f54f5-101">Parameters for filtering, sorting, fuzzy matching, and other suggestions query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParameters.#ctor" />
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
            <span data-ttu-id="f54f5-102">Initialisiert eine neue Instanz der SuggestParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f54f5-102">Initializes a new instance of the SuggestParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-103">Abrufen oder festlegen den OData-$filter-Ausdruck, der für die Abfrage Vorschläge gelten.</span><span class="sxs-lookup"><span data-stu-id="f54f5-103">Gets or sets the OData $filter expression to apply to the suggestions query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.HighlightPostTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-104">Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-104">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="f54f5-105">Muss mit HighlightPreTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f54f5-105">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="f54f5-106">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="f54f5-106">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.HighlightPreTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-107">Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-107">Gets or sets a string tag that is prepended to hit highlights.</span></span>
            <span data-ttu-id="f54f5-108">Muss mit HighlightPostTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f54f5-108">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="f54f5-109">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="f54f5-109">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.MinimumCoverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-110">Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer vorschlagsabfrage in der Reihenfolge für die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-110">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="f54f5-111">Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein.</span><span class="sxs-lookup"><span data-stu-id="f54f5-111">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="f54f5-112">Der Standardwert ist 80.</span><span class="sxs-lookup"><span data-stu-id="f54f5-112">The default is 80.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OrderBy : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-113">Ruft ab oder legt die Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="f54f5-113">Gets or sets the list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="f54f5-114">Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein.</span><span class="sxs-lookup"><span data-stu-id="f54f5-114">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="f54f5-115">Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-115">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="f54f5-116">Standardmäßig wird in aufsteigender Reihenfolge sortiert.</span><span class="sxs-lookup"><span data-stu-id="f54f5-116">The default is ascending order.</span></span> <span data-ttu-id="f54f5-117">Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt.</span><span class="sxs-lookup"><span data-stu-id="f54f5-117">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="f54f5-118">Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend.</span><span class="sxs-lookup"><span data-stu-id="f54f5-118">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="f54f5-119">Es kann höchstens 32 Orderby-Klausel.</span><span class="sxs-lookup"><span data-stu-id="f54f5-119">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SearchFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.SearchFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-120">Ruft ab oder legt die Liste von Feldnamen, berücksichtigen beim Abfragen der Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="f54f5-120">Gets or sets the list of field names to consider when querying for suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Select" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-121">Ruft ab oder legt die Liste der Felder abrufen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-121">Gets or sets the list of fields to retrieve.</span></span> <span data-ttu-id="f54f5-122">Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-122">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-123">Ruft ab oder legt die Anzahl der abzurufenden Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="f54f5-123">Gets or sets the number of suggestions to retrieve.</span></span> <span data-ttu-id="f54f5-124">Dies muss ein Wert zwischen 1 und 100 sein.</span><span class="sxs-lookup"><span data-stu-id="f54f5-124">This must be a value between 1 and 100.</span></span> <span data-ttu-id="f54f5-125">Der Standardwert ist 5.</span><span class="sxs-lookup"><span data-stu-id="f54f5-125">The default is to 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="suggestParameters.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-126">Konvertiert die SuggestParameters-Instanz in einer URL-Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f54f5-126">Converts the SuggestParameters instance to a URL query string.</span></span>
            </summary>
        <returns><span data-ttu-id="f54f5-127">Eine URL-Abfragezeichenfolge, die den Vorschlag-Parameter enthält.</span><span class="sxs-lookup"><span data-stu-id="f54f5-127">A URL query string containing all the suggestion parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseFuzzyMatching">
      <MemberSignature Language="C#" Value="public bool UseFuzzyMatching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseFuzzyMatching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.UseFuzzyMatching" />
      <MemberSignature Language="VB.NET" Value="Public Property UseFuzzyMatching As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseFuzzyMatching : bool with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.UseFuzzyMatching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f54f5-128">Ruft ab oder legt einen Wert, der angibt, ob verwenden die Fuzzyübereinstimmung für die vorschlagsabfrage.</span><span class="sxs-lookup"><span data-stu-id="f54f5-128">Gets or sets a value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="f54f5-129">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="f54f5-129">Default is false.</span></span> <span data-ttu-id="f54f5-130">Bei Festlegung auf "true", die Abfrage findet Vorschläge auch wenn es eine Zeichen anders ist oder fehlende in den Suchtext ein.</span><span class="sxs-lookup"><span data-stu-id="f54f5-130">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="f54f5-131">Dies führt in einigen Szenarien zwar zu besseren Ergebnissen, geht jedoch zulasten der Leistung, da Fuzzysuchen von Vorschlägen langsamer sind und mehr Ressourcen belegen.</span><span class="sxs-lookup"><span data-stu-id="f54f5-131">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>