<Type Name="SuggestParametersPayload" FullName="Microsoft.Azure.Search.Models.SuggestParametersPayload">
  <TypeSignature Language="C#" Value="public class SuggestParametersPayload" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SuggestParametersPayload extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SuggestParametersPayload" />
  <TypeSignature Language="VB.NET" Value="Public Class SuggestParametersPayload" />
  <TypeSignature Language="F#" Value="type SuggestParametersPayload = class" />
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
            <span data-ttu-id="6cd8f-101">Parameter zum Filtern, sortieren, Fuzzyübereinstimmung und andere Vorschläge Abfragen Verhalten.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-101">Parameters for filtering, sorting, fuzzy matching, and other suggestions query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParametersPayload ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParametersPayload.#ctor" />
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
            <span data-ttu-id="6cd8f-102">Initialisiert eine neue Instanz der SuggestParametersPayload-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-102">Initializes a new instance of the SuggestParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParametersPayload (string filter = null, Nullable&lt;bool&gt; fuzzy = null, string highlightPostTag = null, string highlightPreTag = null, Nullable&lt;double&gt; minimumCoverage = null, string orderBy = null, string search = null, string searchFields = null, string select = null, string suggesterName = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filter, valuetype System.Nullable`1&lt;bool&gt; fuzzy, string highlightPostTag, string highlightPreTag, valuetype System.Nullable`1&lt;float64&gt; minimumCoverage, string orderBy, string search, string searchFields, string select, string suggesterName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParametersPayload.#ctor(System.String,System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Double},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filter As String = null, Optional fuzzy As Nullable(Of Boolean) = null, Optional highlightPostTag As String = null, Optional highlightPreTag As String = null, Optional minimumCoverage As Nullable(Of Double) = null, Optional orderBy As String = null, Optional search As String = null, Optional searchFields As String = null, Optional select As String = null, Optional suggesterName As String = null, Optional top As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SuggestParametersPayload : string * Nullable&lt;bool&gt; * string * string * Nullable&lt;double&gt; * string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.SuggestParametersPayload" Usage="new Microsoft.Azure.Search.Models.SuggestParametersPayload (filter, fuzzy, highlightPostTag, highlightPreTag, minimumCoverage, orderBy, search, searchFields, select, suggesterName, top)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="fuzzy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="highlightPostTag" Type="System.String" />
        <Parameter Name="highlightPreTag" Type="System.String" />
        <Parameter Name="minimumCoverage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="orderBy" Type="System.String" />
        <Parameter Name="search" Type="System.String" />
        <Parameter Name="searchFields" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="6cd8f-103">Die OData-$filter-Ausdruck, der für die Abfrage Vorschläge gelten.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-103">The OData $filter expression to apply to the suggestions query.</span></span></param>
        <param name="fuzzy"><span data-ttu-id="6cd8f-104">Ein Wert, der angibt, ob verwenden die Fuzzyübereinstimmung für die vorschlagsabfrage.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-104">A value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="6cd8f-105">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="6cd8f-105">Default is false.</span></span> <span data-ttu-id="6cd8f-106">Bei Festlegung auf "true", die Abfrage findet Vorschläge auch wenn es eine Zeichen anders ist oder fehlende in den Suchtext ein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-106">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="6cd8f-107">Dies führt in einigen Szenarien zwar zu besseren Ergebnissen, geht jedoch zulasten der Leistung, da Fuzzysuchen von Vorschlägen langsamer sind und mehr Ressourcen belegen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-107">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span></param>
        <param name="highlightPostTag"><span data-ttu-id="6cd8f-108">Ein zeichenfolgentag, die angefügt wird, um Treffer wird hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-108">A string tag that is appended to hit highlights.</span></span> <span data-ttu-id="6cd8f-109">Muss mit HighlightPreTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-109">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="6cd8f-110">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-110">If omitted, hit highlighting of suggestions is disabled.</span></span></param>
        <param name="highlightPreTag"><span data-ttu-id="6cd8f-111">Ein zeichenfolgentag, die vorangestellt wird, um Treffer wird hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-111">A string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="6cd8f-112">Muss mit HighlightPostTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-112">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="6cd8f-113">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-113">If omitted, hit highlighting of suggestions is disabled.</span></span></param>
        <param name="minimumCoverage"><span data-ttu-id="6cd8f-114">Eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer vorschlagsabfrage in der Reihenfolge für die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-114">A number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="6cd8f-115">Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-115">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="6cd8f-116">Der Standardwert ist 80.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-116">The default is 80.</span></span></param>
        <param name="orderBy"><span data-ttu-id="6cd8f-117">Die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-117">The comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="6cd8f-118">Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-118">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="6cd8f-119">Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-119">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="6cd8f-120">Standardmäßig wird in aufsteigender Reihenfolge sortiert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-120">The default is ascending order.</span></span> <span data-ttu-id="6cd8f-121">Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-121">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="6cd8f-122">Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-122">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="6cd8f-123">Es kann höchstens 32 Orderby-Klausel.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-123">There can be at most 32 Orderby clauses.</span></span></param>
        <param name="search"><span data-ttu-id="6cd8f-124">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-124">The search text on which to base suggestions.</span></span></param>
        <param name="searchFields"><span data-ttu-id="6cd8f-125">Die durch Trennzeichen getrennte Liste von Feldnamen, berücksichtigen beim Abfragen der Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-125">The comma-separated list of field names to consider when querying for suggestions.</span></span></param>
        <param name="select"><span data-ttu-id="6cd8f-126">Die durch Trennzeichen getrennte Liste der Felder abrufen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-126">The comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="6cd8f-127">Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-127">If unspecified, all fields marked as retrievable in the schema are included.</span></span></param>
        <param name="suggesterName"><span data-ttu-id="6cd8f-128">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-128">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span></param>
        <param name="top"><span data-ttu-id="6cd8f-129">Die Anzahl der abzurufenden Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-129">The number of suggestions to retrieve.</span></span> <span data-ttu-id="6cd8f-130">Dies muss ein Wert zwischen 1 und 100 sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-130">This must be a value between 1 and 100.</span></span> <span data-ttu-id="6cd8f-131">Der Standardwert ist 5.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-131">The default is to 5.</span></span></param>
        <summary>
            <span data-ttu-id="6cd8f-132">Initialisiert eine neue Instanz der SuggestParametersPayload-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-132">Initializes a new instance of the SuggestParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-133">Abrufen oder festlegen den OData-$filter-Ausdruck, der für die Abfrage Vorschläge gelten.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-133">Gets or sets the OData $filter expression to apply to the suggestions query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fuzzy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Fuzzy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Fuzzy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Fuzzy" />
      <MemberSignature Language="VB.NET" Value="Public Property Fuzzy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Fuzzy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Fuzzy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fuzzy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-134">Ruft ab oder legt einen Wert, der angibt, ob verwenden die Fuzzyübereinstimmung für die vorschlagsabfrage.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-134">Gets or sets a value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="6cd8f-135">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="6cd8f-135">Default is false.</span></span> <span data-ttu-id="6cd8f-136">Bei Festlegung auf "true", die Abfrage findet Vorschläge auch wenn es eine Zeichen anders ist oder fehlende in den Suchtext ein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-136">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="6cd8f-137">Dies führt in einigen Szenarien zwar zu besseren Ergebnissen, geht jedoch zulasten der Leistung, da Fuzzysuchen von Vorschlägen langsamer sind und mehr Ressourcen belegen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-137">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPostTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlightPostTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-138">Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-138">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="6cd8f-139">Muss mit HighlightPreTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-139">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="6cd8f-140">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-140">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPreTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlightPreTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-141">Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-141">Gets or sets a string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="6cd8f-142">Muss mit HighlightPostTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-142">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="6cd8f-143">Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-143">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.MinimumCoverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimumCoverage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-144">Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer vorschlagsabfrage in der Reihenfolge für die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-144">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="6cd8f-145">Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-145">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="6cd8f-146">Der Standardwert ist 80.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-146">The default is 80.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public string OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As String" />
      <MemberSignature Language="F#" Value="member this.OrderBy : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orderby")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-147">Ruft ab oder legt die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-147">Gets or sets the comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="6cd8f-148">Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-148">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="6cd8f-149">Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-149">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="6cd8f-150">Standardmäßig wird in aufsteigender Reihenfolge sortiert.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-150">The default is ascending order.</span></span> <span data-ttu-id="6cd8f-151">Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-151">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="6cd8f-152">Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-152">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="6cd8f-153">Es kann höchstens 32 Orderby-Klausel.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-153">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public string Search { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Search" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Search" />
      <MemberSignature Language="VB.NET" Value="Public Property Search As String" />
      <MemberSignature Language="F#" Value="member this.Search : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Search" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="search")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-154">Ruft ab oder legt den Suchtext ein, auf denen Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-154">Gets or sets the search text on which to base suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public string SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As String" />
      <MemberSignature Language="F#" Value="member this.SearchFields : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.SearchFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchFields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-155">Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, berücksichtigen beim Abfragen der Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-155">Gets or sets the comma-separated list of field names to consider when querying for suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Select" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="select")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-156">Ruft ab oder legt die durch Trennzeichen getrennte Liste der abzurufenden Felder.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-156">Gets or sets the comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="6cd8f-157">Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-157">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggesterName">
      <MemberSignature Language="C#" Value="public string SuggesterName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SuggesterName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.SuggesterName" />
      <MemberSignature Language="VB.NET" Value="Public Property SuggesterName As String" />
      <MemberSignature Language="F#" Value="member this.SuggesterName : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.SuggesterName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="suggesterName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-158">Ruft ab oder legt den Namen des suggesters gemäß der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-158">Gets or sets the name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="top")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6cd8f-159">Ruft ab oder legt die Anzahl der abzurufenden Vorschläge.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-159">Gets or sets the number of suggestions to retrieve.</span></span> <span data-ttu-id="6cd8f-160">Dies muss ein Wert zwischen 1 und 100 sein.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-160">This must be a value between 1 and 100.</span></span> <span data-ttu-id="6cd8f-161">Der Standardwert ist 5.</span><span class="sxs-lookup"><span data-stu-id="6cd8f-161">The default is to 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>