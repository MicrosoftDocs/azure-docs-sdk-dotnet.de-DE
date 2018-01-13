<Type Name="SearchParametersPayload" FullName="Microsoft.Azure.Search.Models.SearchParametersPayload">
  <TypeSignature Language="C#" Value="public class SearchParametersPayload" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchParametersPayload extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchParametersPayload" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchParametersPayload" />
  <TypeSignature Language="F#" Value="type SearchParametersPayload = class" />
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
            <span data-ttu-id="216e1-101">Parameter zum Filtern, durchsuchen, sortieren, Faceting, Paging und andere Verhalten der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="216e1-101">Parameters for filtering, sorting, faceting, paging, and other search query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParametersPayload ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParametersPayload.#ctor" />
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
            <span data-ttu-id="216e1-102">Initialisiert eine neue Instanz der SearchParametersPayload-Klasse.</span><span class="sxs-lookup"><span data-stu-id="216e1-102">Initializes a new instance of the SearchParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParametersPayload (Nullable&lt;bool&gt; count = null, System.Collections.Generic.IList&lt;string&gt; facets = null, string filter = null, string highlight = null, string highlightPostTag = null, string highlightPreTag = null, Nullable&lt;double&gt; minimumCoverage = null, string orderBy = null, Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; queryType = null, System.Collections.Generic.IList&lt;string&gt; scoringParameters = null, string scoringProfile = null, string search = null, string searchFields = null, Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; searchMode = null, string select = null, Nullable&lt;int&gt; skip = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.IList`1&lt;string&gt; facets, string filter, string highlight, string highlightPostTag, string highlightPreTag, valuetype System.Nullable`1&lt;float64&gt; minimumCoverage, string orderBy, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.QueryType&gt; queryType, class System.Collections.Generic.IList`1&lt;string&gt; scoringParameters, string scoringProfile, string search, string searchFields, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.SearchMode&gt; searchMode, string select, valuetype System.Nullable`1&lt;int32&gt; skip, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParametersPayload.#ctor(System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Nullable{System.Double},System.String,System.Nullable{Microsoft.Azure.Search.Models.QueryType},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Search.Models.SearchMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Boolean) = null, Optional facets As IList(Of String) = null, Optional filter As String = null, Optional highlight As String = null, Optional highlightPostTag As String = null, Optional highlightPreTag As String = null, Optional minimumCoverage As Nullable(Of Double) = null, Optional orderBy As String = null, Optional queryType As Nullable(Of QueryType) = null, Optional scoringParameters As IList(Of String) = null, Optional scoringProfile As String = null, Optional search As String = null, Optional searchFields As String = null, Optional searchMode As Nullable(Of SearchMode) = null, Optional select As String = null, Optional skip As Nullable(Of Integer) = null, Optional top As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SearchParametersPayload : Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * Nullable&lt;double&gt; * string * Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.SearchParametersPayload" Usage="new Microsoft.Azure.Search.Models.SearchParametersPayload (count, facets, filter, highlight, highlightPostTag, highlightPreTag, minimumCoverage, orderBy, queryType, scoringParameters, scoringProfile, search, searchFields, searchMode, select, skip, top)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="facets" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="highlight" Type="System.String" />
        <Parameter Name="highlightPostTag" Type="System.String" />
        <Parameter Name="highlightPreTag" Type="System.String" />
        <Parameter Name="minimumCoverage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="orderBy" Type="System.String" />
        <Parameter Name="queryType" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt;" />
        <Parameter Name="scoringParameters" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="scoringProfile" Type="System.String" />
        <Parameter Name="search" Type="System.String" />
        <Parameter Name="searchFields" Type="System.String" />
        <Parameter Name="searchMode" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="skip" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="216e1-103">Ein Wert, der angibt, ob die Gesamtzahl der Ergebnisse abzurufen.</span><span class="sxs-lookup"><span data-stu-id="216e1-103">A value that specifies whether to fetch the total count of results.</span></span> <span data-ttu-id="216e1-104">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="216e1-104">Default is false.</span></span> <span data-ttu-id="216e1-105">Wenn dieser Wert auf "true" kann die Leistung auswirken.</span><span class="sxs-lookup"><span data-stu-id="216e1-105">Setting this value to true may have a performance impact.</span></span> <span data-ttu-id="216e1-106">Beachten Sie, dass die zurückgegebene Anzahl ein Näherungswert ist.</span><span class="sxs-lookup"><span data-stu-id="216e1-106">Note that the count returned is an approximation.</span></span></param>
        <param name="facets"><span data-ttu-id="216e1-107">Die Liste der Facet-Ausdrücke, die für die Suchabfrage gelten.</span><span class="sxs-lookup"><span data-stu-id="216e1-107">The list of facet expressions to apply to the search query.</span></span> <span data-ttu-id="216e1-108">Jedes Facet-Ausdruck enthält einen Feldnamen, optional gefolgt von einer durch Trennzeichen getrennte Liste von Name-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="216e1-108">Each facet expression contains a field name, optionally followed by a comma-separated list of name:value pairs.</span></span></param>
        <param name="filter"><span data-ttu-id="216e1-109">Die OData-$filter-Ausdruck, der für die Suchabfrage gelten.</span><span class="sxs-lookup"><span data-stu-id="216e1-109">The OData $filter expression to apply to the search query.</span></span></param>
        <param name="highlight"><span data-ttu-id="216e1-110">Die durch Trennzeichen getrennte Liste von Feldnamen, verwenden Sie für erreicht kennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="216e1-110">The comma-separated list of field names to use for hit highlights.</span></span> <span data-ttu-id="216e1-111">Nur durchsuchbare Feldern können für die Treffermarkierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-111">Only searchable fields can be used for hit highlighting.</span></span></param>
        <param name="highlightPostTag"><span data-ttu-id="216e1-112">Ein zeichenfolgentag, die angefügt wird, um Treffer wird hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="216e1-112">A string tag that is appended to hit highlights.</span></span> <span data-ttu-id="216e1-113">Muss mit HighlightPreTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-113">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="216e1-114">Standardmäßig wird &amp;Lt; / em&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="216e1-114">Default is &amp;lt;/em&amp;gt;.</span></span></param>
        <param name="highlightPreTag"><span data-ttu-id="216e1-115">Ein zeichenfolgentag, die vorangestellt wird, um Treffer wird hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="216e1-115">A string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="216e1-116">Muss mit HighlightPostTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-116">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="216e1-117">Standardmäßig wird &amp;Lt; Em&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="216e1-117">Default is &amp;lt;em&amp;gt;.</span></span></param>
        <param name="minimumCoverage"><span data-ttu-id="216e1-118">Eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer Suchabfrage, damit die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="216e1-118">A number between 0 and 100 indicating the percentage of the index that must be covered by a search query in order for the query to be reported as a success.</span></span> <span data-ttu-id="216e1-119">Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-119">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="216e1-120">Der Standardwert ist 100.</span><span class="sxs-lookup"><span data-stu-id="216e1-120">The default is 100.</span></span></param>
        <param name="orderBy"><span data-ttu-id="216e1-121">Die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-121">The comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="216e1-122">Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-122">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="216e1-123">Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen.</span><span class="sxs-lookup"><span data-stu-id="216e1-123">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="216e1-124">Standardmäßig wird in aufsteigender Reihenfolge sortiert.</span><span class="sxs-lookup"><span data-stu-id="216e1-124">The default is ascending order.</span></span> <span data-ttu-id="216e1-125">Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt.</span><span class="sxs-lookup"><span data-stu-id="216e1-125">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="216e1-126">Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend.</span><span class="sxs-lookup"><span data-stu-id="216e1-126">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="216e1-127">Es kann höchstens 32 Orderby-Klausel.</span><span class="sxs-lookup"><span data-stu-id="216e1-127">There can be at most 32 Orderby clauses.</span></span></param>
        <param name="queryType"><span data-ttu-id="216e1-128">Ruft ab oder legt einen Wert, der die Syntax der Suchabfrage angibt.</span><span class="sxs-lookup"><span data-stu-id="216e1-128">Gets or sets a value that specifies the syntax of the search query.</span></span> <span data-ttu-id="216e1-129">Der Standardwert ist 'einfach'.</span><span class="sxs-lookup"><span data-stu-id="216e1-129">The default is 'simple'.</span></span> <span data-ttu-id="216e1-130">Verwenden Sie 'full' aus, wenn die Abfrage die Lucene-Abfragesyntax verwendet.</span><span class="sxs-lookup"><span data-stu-id="216e1-130">Use 'full' if your query uses the Lucene query syntax.</span></span> <span data-ttu-id="216e1-131">Folgende Werte sind möglich: 'einfach', 'full'</span><span class="sxs-lookup"><span data-stu-id="216e1-131">Possible values include: 'simple', 'full'</span></span></param>
        <param name="scoringParameters"><span data-ttu-id="216e1-132">Die Liste der Parameterwerte zur Bewertung von Funktionen (z. B. ReferencePointParameter) mit dem Format Name: Wert verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="216e1-132">The list of parameter values to be used in scoring functions (for example, referencePointParameter) using the format name:value.</span></span> <span data-ttu-id="216e1-133">Beispielsweise, wenn das Bewertungsprofil eine Funktion mit einem Parameter namens "meinStandort" definiert die Parameterzeichenfolge wäre "meinStandort:-122.2,44.8"(without the quotes).</span><span class="sxs-lookup"><span data-stu-id="216e1-133">For example, if the scoring profile defines a function with a parameter called 'mylocation' the parameter string would be "mylocation:-122.2,44.8"(without the quotes).</span></span></param>
        <param name="scoringProfile"><span data-ttu-id="216e1-134">Der Name eines Bewertungsprofils zum Auswerten von übereinstimmungsbewertungen für den Vergleich von Dokumenten zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-134">The name of a scoring profile to evaluate match scores for matching documents in order to sort the results.</span></span></param>
        <param name="search"><span data-ttu-id="216e1-135">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="216e1-135">A full-text search query expression; Use null or "\*" to match all documents.</span></span></param>
        <param name="searchFields"><span data-ttu-id="216e1-136">Die durch Trennzeichen getrennte Liste von Feldnamen, die die Volltextsuche einschließt.</span><span class="sxs-lookup"><span data-stu-id="216e1-136">The comma-separated list of field names to include in the full-text search.</span></span></param>
        <param name="searchMode"><span data-ttu-id="216e1-137">Ein Wert, der angibt, ob einige oder alle Suchbegriffe übereinstimmen müssen, damit das Dokument als Übereinstimmung zu zählen.</span><span class="sxs-lookup"><span data-stu-id="216e1-137">A value that specifies whether any or all of the search terms must be matched in order to count the document as a match.</span></span> <span data-ttu-id="216e1-138">Folgende Werte sind möglich: 'beliebig', 'all'</span><span class="sxs-lookup"><span data-stu-id="216e1-138">Possible values include: 'any', 'all'</span></span></param>
        <param name="select"><span data-ttu-id="216e1-139">Die durch Trennzeichen getrennte Liste der Felder abrufen.</span><span class="sxs-lookup"><span data-stu-id="216e1-139">The comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="216e1-140">Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</span><span class="sxs-lookup"><span data-stu-id="216e1-140">If unspecified, all fields marked as retrievable in the schema are included.</span></span></param>
        <param name="skip"><span data-ttu-id="216e1-141">Die Anzahl der zu überspringenden Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-141">The number of search results to skip.</span></span> <span data-ttu-id="216e1-142">Dieser Wert darf nicht größer als 100.000 sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-142">This value cannot be greater than 100,000.</span></span> <span data-ttu-id="216e1-143">Wenn Sie Dokumente in Folge überprüfen müssen, aber nicht überspringen aufgrund dieser Einschränkung verwenden, sollten Sie OrderBy auf einen vollständig sortierten Schlüssel und Filter mit einer Bereichsabfrage stattdessen.</span><span class="sxs-lookup"><span data-stu-id="216e1-143">If you need to scan documents in sequence, but cannot use Skip due to this limitation, consider using OrderBy on a totally-ordered key and Filter with a range query instead.</span></span></param>
        <param name="top"><span data-ttu-id="216e1-144">Die Anzahl der abzurufenden Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-144">The number of search results to retrieve.</span></span> <span data-ttu-id="216e1-145">Dies kann in Verbindung mit Skip verwendet werden, zum Implementieren einer clientseitigen Auslagerung der Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-145">This can be used in conjunction with Skip to implement client-side paging of search results.</span></span> <span data-ttu-id="216e1-146">Wenn Ergebnisse aufgrund von serverseitiges Paging abgeschnitten werden, wird die Antwort ein Fortsetzungstoken enthalten, die zum Abrufen der nächsten Seite mit Ergebnissen ContinueSearch übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="216e1-146">If results are truncated due to server-side paging, the response will include a continuation token that can be passed to ContinueSearch to retrieve the next page of results.</span></span> <span data-ttu-id="216e1-147">Weitere Informationen finden Sie in der DocumentSearchResponse.ContinuationToken.</span><span class="sxs-lookup"><span data-stu-id="216e1-147">See DocumentSearchResponse.ContinuationToken for more information.</span></span></param>
        <summary>
            <span data-ttu-id="216e1-148">Initialisiert eine neue Instanz der SearchParametersPayload-Klasse.</span><span class="sxs-lookup"><span data-stu-id="216e1-148">Initializes a new instance of the SearchParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-149">Ruft ab oder legt einen Wert, der angibt, ob die Gesamtzahl der Ergebnisse abzurufen.</span><span class="sxs-lookup"><span data-stu-id="216e1-149">Gets or sets a value that specifies whether to fetch the total count of results.</span></span> <span data-ttu-id="216e1-150">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="216e1-150">Default is false.</span></span> <span data-ttu-id="216e1-151">Wenn dieser Wert auf "true" kann die Leistung auswirken.</span><span class="sxs-lookup"><span data-stu-id="216e1-151">Setting this value to true may have a performance impact.</span></span> <span data-ttu-id="216e1-152">Beachten Sie, dass die zurückgegebene Anzahl ein Näherungswert ist.</span><span class="sxs-lookup"><span data-stu-id="216e1-152">Note that the count returned is an approximation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Facets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Facets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="facets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-153">Ruft ab oder legt die Liste der Facet-Ausdrücke, die für die Suchabfrage gelten.</span><span class="sxs-lookup"><span data-stu-id="216e1-153">Gets or sets the list of facet expressions to apply to the search query.</span></span> <span data-ttu-id="216e1-154">Jedes Facet-Ausdruck enthält einen Feldnamen, optional gefolgt von einer durch Trennzeichen getrennte Liste von Name-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="216e1-154">Each facet expression contains a field name, optionally followed by a comma-separated list of name:value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Filter" />
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
            <span data-ttu-id="216e1-155">Ruft ab oder legt den OData-$filter Ausdruck für die Suchabfrage gelten.</span><span class="sxs-lookup"><span data-stu-id="216e1-155">Gets or sets the OData $filter expression to apply to the search query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Highlight">
      <MemberSignature Language="C#" Value="public string Highlight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Highlight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Highlight" />
      <MemberSignature Language="VB.NET" Value="Public Property Highlight As String" />
      <MemberSignature Language="F#" Value="member this.Highlight : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Highlight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-156">Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, die für treffermarkierungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="216e1-156">Gets or sets the comma-separated list of field names to use for hit highlights.</span></span> <span data-ttu-id="216e1-157">Nur durchsuchbare Feldern können für die Treffermarkierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-157">Only searchable fields can be used for hit highlighting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPostTag" />
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
            <span data-ttu-id="216e1-158">Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="216e1-158">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="216e1-159">Muss mit HighlightPreTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-159">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="216e1-160">Standardmäßig wird &amp;Amp; Lt; / em&amp;Amp; amp.</span><span class="sxs-lookup"><span data-stu-id="216e1-160">Default is &amp;amp;lt;/em&amp;amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPreTag" />
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
            <span data-ttu-id="216e1-161">Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen.</span><span class="sxs-lookup"><span data-stu-id="216e1-161">Gets or sets a string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="216e1-162">Muss mit HighlightPostTag festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="216e1-162">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="216e1-163">Standardmäßig wird &amp;Amp; Lt; Em&amp;Amp; amp.</span><span class="sxs-lookup"><span data-stu-id="216e1-163">Default is &amp;amp;lt;em&amp;amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.MinimumCoverage" />
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
            <span data-ttu-id="216e1-164">Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer Suchabfrage, damit die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="216e1-164">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a search query in order for the query to be reported as a success.</span></span> <span data-ttu-id="216e1-165">Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-165">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="216e1-166">Der Standardwert ist 100.</span><span class="sxs-lookup"><span data-stu-id="216e1-166">The default is 100.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public string OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As String" />
      <MemberSignature Language="F#" Value="member this.OrderBy : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.OrderBy" />
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
            <span data-ttu-id="216e1-167">Ruft ab oder legt die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-167">Gets or sets the comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="216e1-168">Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-168">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="216e1-169">Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen.</span><span class="sxs-lookup"><span data-stu-id="216e1-169">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="216e1-170">Standardmäßig wird in aufsteigender Reihenfolge sortiert.</span><span class="sxs-lookup"><span data-stu-id="216e1-170">The default is ascending order.</span></span> <span data-ttu-id="216e1-171">Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt.</span><span class="sxs-lookup"><span data-stu-id="216e1-171">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="216e1-172">Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend.</span><span class="sxs-lookup"><span data-stu-id="216e1-172">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="216e1-173">Es kann höchstens 32 Orderby-Klausel.</span><span class="sxs-lookup"><span data-stu-id="216e1-173">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; QueryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.QueryType&gt; QueryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.QueryType" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryType As Nullable(Of QueryType)" />
      <MemberSignature Language="F#" Value="member this.QueryType : Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.QueryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-174">Ruft ab oder legt einen Wert, der die Syntax der Suchabfrage angibt.</span><span class="sxs-lookup"><span data-stu-id="216e1-174">Gets or sets a value that specifies the syntax of the search query.</span></span>
            <span data-ttu-id="216e1-175">Der Standardwert ist 'einfach'.</span><span class="sxs-lookup"><span data-stu-id="216e1-175">The default is 'simple'.</span></span> <span data-ttu-id="216e1-176">Verwenden Sie 'full' aus, wenn die Abfrage die Lucene-Abfragesyntax verwendet.</span><span class="sxs-lookup"><span data-stu-id="216e1-176">Use 'full' if your query uses the Lucene query syntax.</span></span> <span data-ttu-id="216e1-177">Folgende Werte sind möglich: 'einfach', 'full'</span><span class="sxs-lookup"><span data-stu-id="216e1-177">Possible values include: 'simple', 'full'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ScoringParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ScoringParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringParameters As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ScoringParameters : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scoringParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-178">Ruft ab oder legt die Liste der Parameterwerte zur Bewertung von Funktionen (z. B. ReferencePointParameter) mit dem Format Name: Wert verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="216e1-178">Gets or sets the list of parameter values to be used in scoring functions (for example, referencePointParameter) using the format name:value.</span></span> <span data-ttu-id="216e1-179">Beispielsweise, wenn das Bewertungsprofil eine Funktion mit einem Parameter namens "meinStandort" definiert die Parameterzeichenfolge wäre "meinStandort:-122.2,44.8"(without the quotes).</span><span class="sxs-lookup"><span data-stu-id="216e1-179">For example, if the scoring profile defines a function with a parameter called 'mylocation' the parameter string would be "mylocation:-122.2,44.8"(without the quotes).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringProfile">
      <MemberSignature Language="C#" Value="public string ScoringProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScoringProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringProfile As String" />
      <MemberSignature Language="F#" Value="member this.ScoringProfile : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scoringProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-180">Ruft ab oder legt den Namen des Bewertungsprofils zum Auswerten von übereinstimmungsbewertungen für den Abgleich Dokumente, um die Ergebnisse zu sortieren.</span><span class="sxs-lookup"><span data-stu-id="216e1-180">Gets or sets the name of a scoring profile to evaluate match scores for matching documents in order to sort the results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public string Search { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Search" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Search" />
      <MemberSignature Language="VB.NET" Value="Public Property Search As String" />
      <MemberSignature Language="F#" Value="member this.Search : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Search" />
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
            <span data-ttu-id="216e1-181">Ruft ab, oder legt ihn fest ein Abfrageausdrucks Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="216e1-181">Gets or sets a full-text search query expression; Use null or "\*" to match all documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public string SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As String" />
      <MemberSignature Language="F#" Value="member this.SearchFields : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.SearchFields" />
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
            <span data-ttu-id="216e1-182">Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, die die Volltextsuche einschließt.</span><span class="sxs-lookup"><span data-stu-id="216e1-182">Gets or sets the comma-separated list of field names to include in the full-text search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; SearchMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.SearchMode&gt; SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchMode As Nullable(Of SearchMode)" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="216e1-183">Ruft ab oder legt einen Wert, der angibt, ob einige oder alle Suchbegriffe übereinstimmen müssen, damit das Dokument als Übereinstimmung zu zählen.</span><span class="sxs-lookup"><span data-stu-id="216e1-183">Gets or sets a value that specifies whether any or all of the search terms must be matched in order to count the document as a match.</span></span> <span data-ttu-id="216e1-184">Folgende Werte sind möglich: 'beliebig', 'all'</span><span class="sxs-lookup"><span data-stu-id="216e1-184">Possible values include: 'any', 'all'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Select" />
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
            <span data-ttu-id="216e1-185">Ruft ab oder legt die durch Trennzeichen getrennte Liste der abzurufenden Felder.</span><span class="sxs-lookup"><span data-stu-id="216e1-185">Gets or sets the comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="216e1-186">Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</span><span class="sxs-lookup"><span data-stu-id="216e1-186">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Skip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Skip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Skip" />
      <MemberSignature Language="VB.NET" Value="Public Property Skip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Skip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Skip" />
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
            <span data-ttu-id="216e1-187">Ruft ab oder legt die Anzahl der zu überspringenden Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-187">Gets or sets the number of search results to skip.</span></span> <span data-ttu-id="216e1-188">Dieser Wert darf nicht größer als 100.000 sein.</span><span class="sxs-lookup"><span data-stu-id="216e1-188">This value cannot be greater than 100,000.</span></span> <span data-ttu-id="216e1-189">Wenn Sie Dokumente in Folge überprüfen müssen, aber nicht überspringen aufgrund dieser Einschränkung verwenden, sollten Sie OrderBy auf einen vollständig sortierten Schlüssel und Filter mit einer Bereichsabfrage stattdessen.</span><span class="sxs-lookup"><span data-stu-id="216e1-189">If you need to scan documents in sequence, but cannot use Skip due to this limitation, consider using OrderBy on a totally-ordered key and Filter with a range query instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Top" />
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
            <span data-ttu-id="216e1-190">Ruft ab oder legt die Anzahl der abzurufenden Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-190">Gets or sets the number of search results to retrieve.</span></span> <span data-ttu-id="216e1-191">Dies kann in Verbindung mit Skip verwendet werden, zum Implementieren einer clientseitigen Auslagerung der Suchergebnisse.</span><span class="sxs-lookup"><span data-stu-id="216e1-191">This can be used in conjunction with Skip to implement client-side paging of search results.</span></span> <span data-ttu-id="216e1-192">Wenn Ergebnisse aufgrund von serverseitiges Paging abgeschnitten werden, wird die Antwort ein Fortsetzungstoken enthalten, die zum Abrufen der nächsten Seite mit Ergebnissen ContinueSearch übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="216e1-192">If results are truncated due to server-side paging, the response will include a continuation token that can be passed to ContinueSearch to retrieve the next page of results.</span></span> <span data-ttu-id="216e1-193">Weitere Informationen finden Sie in der DocumentSearchResponse.ContinuationToken.</span><span class="sxs-lookup"><span data-stu-id="216e1-193">See DocumentSearchResponse.ContinuationToken for more information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>