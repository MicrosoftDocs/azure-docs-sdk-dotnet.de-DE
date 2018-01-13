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
            Parameter zum Filtern, durchsuchen, sortieren, Faceting, Paging und andere Verhalten der Abfrage.
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
            Initialisiert eine neue Instanz der SearchParametersPayload-Klasse.
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
        <param name="count">Ein Wert, der angibt, ob die Gesamtzahl der Ergebnisse abzurufen. Die Standardeinstellung ist "false". Wenn dieser Wert auf "true" kann die Leistung auswirken. Beachten Sie, dass die zurückgegebene Anzahl ein Näherungswert ist.</param>
        <param name="facets">Die Liste der Facet-Ausdrücke, die für die Suchabfrage gelten. Jedes Facet-Ausdruck enthält einen Feldnamen, optional gefolgt von einer durch Trennzeichen getrennte Liste von Name-Wert-Paaren.</param>
        <param name="filter">Die OData-$filter-Ausdruck, der für die Suchabfrage gelten.</param>
        <param name="highlight">Die durch Trennzeichen getrennte Liste von Feldnamen, verwenden Sie für erreicht kennzeichnet. Nur durchsuchbare Feldern können für die Treffermarkierung verwendet werden.</param>
        <param name="highlightPostTag">Ein zeichenfolgentag, die angefügt wird, um Treffer wird hervorgehoben. Muss mit HighlightPreTag festgelegt werden. Standardmäßig wird &amp;Lt; / em&amp;Gt;.</param>
        <param name="highlightPreTag">Ein zeichenfolgentag, die vorangestellt wird, um Treffer wird hervorgehoben. Muss mit HighlightPostTag festgelegt werden. Standardmäßig wird &amp;Lt; Em&amp;Gt;.</param>
        <param name="minimumCoverage">Eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer Suchabfrage, damit die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen. Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein. Der Standardwert ist 100.</param>
        <param name="orderBy">Die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse. Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein. Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen. Standardmäßig wird in aufsteigender Reihenfolge sortiert. Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt. Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend. Es kann höchstens 32 Orderby-Klausel.</param>
        <param name="queryType">Ruft ab oder legt einen Wert, der die Syntax der Suchabfrage angibt. Der Standardwert ist 'einfach'. Verwenden Sie 'full' aus, wenn die Abfrage die Lucene-Abfragesyntax verwendet. Folgende Werte sind möglich: 'einfach', 'full'</param>
        <param name="scoringParameters">Die Liste der Parameterwerte zur Bewertung von Funktionen (z. B. ReferencePointParameter) mit dem Format Name: Wert verwendet werden soll. Beispielsweise, wenn das Bewertungsprofil eine Funktion mit einem Parameter namens "meinStandort" definiert die Parameterzeichenfolge wäre "meinStandort:-122.2,44.8"(without the quotes).</param>
        <param name="scoringProfile">Der Name eines Bewertungsprofils zum Auswerten von übereinstimmungsbewertungen für den Vergleich von Dokumenten zum Sortieren der Ergebnisse.</param>
        <param name="search">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen.</param>
        <param name="searchFields">Die durch Trennzeichen getrennte Liste von Feldnamen, die die Volltextsuche einschließt.</param>
        <param name="searchMode">Ein Wert, der angibt, ob einige oder alle Suchbegriffe übereinstimmen müssen, damit das Dokument als Übereinstimmung zu zählen. Folgende Werte sind möglich: 'beliebig', 'all'</param>
        <param name="select">Die durch Trennzeichen getrennte Liste der Felder abrufen. Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</param>
        <param name="skip">Die Anzahl der zu überspringenden Suchergebnisse. Dieser Wert darf nicht größer als 100.000 sein. Wenn Sie Dokumente in Folge überprüfen müssen, aber nicht überspringen aufgrund dieser Einschränkung verwenden, sollten Sie OrderBy auf einen vollständig sortierten Schlüssel und Filter mit einer Bereichsabfrage stattdessen.</param>
        <param name="top">Die Anzahl der abzurufenden Suchergebnisse. Dies kann in Verbindung mit Skip verwendet werden, zum Implementieren einer clientseitigen Auslagerung der Suchergebnisse. Wenn Ergebnisse aufgrund von serverseitiges Paging abgeschnitten werden, wird die Antwort ein Fortsetzungstoken enthalten, die zum Abrufen der nächsten Seite mit Ergebnissen ContinueSearch übergeben werden kann. Weitere Informationen finden Sie in der DocumentSearchResponse.ContinuationToken.</param>
        <summary>
            Initialisiert eine neue Instanz der SearchParametersPayload-Klasse.
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
            Ruft ab oder legt einen Wert, der angibt, ob die Gesamtzahl der Ergebnisse abzurufen. Die Standardeinstellung ist "false". Wenn dieser Wert auf "true" kann die Leistung auswirken. Beachten Sie, dass die zurückgegebene Anzahl ein Näherungswert ist.
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
            Ruft ab oder legt die Liste der Facet-Ausdrücke, die für die Suchabfrage gelten. Jedes Facet-Ausdruck enthält einen Feldnamen, optional gefolgt von einer durch Trennzeichen getrennte Liste von Name-Wert-Paaren.
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
            Ruft ab oder legt den OData-$filter Ausdruck für die Suchabfrage gelten.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, die für treffermarkierungen verwendet. Nur durchsuchbare Feldern können für die Treffermarkierung verwendet werden.
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
            Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen. Muss mit HighlightPreTag festgelegt werden. Standardmäßig wird &amp;Amp; Lt; / em&amp;Amp; amp.
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
            Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen. Muss mit HighlightPostTag festgelegt werden. Standardmäßig wird &amp;Amp; Lt; Em&amp;Amp; amp.
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
            Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer Suchabfrage, damit die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen. Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein. Der Standardwert ist 100.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse. Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein. Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen. Standardmäßig wird in aufsteigender Reihenfolge sortiert. Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt. Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend. Es kann höchstens 32 Orderby-Klausel.
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
            Ruft ab oder legt einen Wert, der die Syntax der Suchabfrage angibt.
            Der Standardwert ist 'einfach'. Verwenden Sie 'full' aus, wenn die Abfrage die Lucene-Abfragesyntax verwendet. Folgende Werte sind möglich: 'einfach', 'full'
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
            Ruft ab oder legt die Liste der Parameterwerte zur Bewertung von Funktionen (z. B. ReferencePointParameter) mit dem Format Name: Wert verwendet werden soll. Beispielsweise, wenn das Bewertungsprofil eine Funktion mit einem Parameter namens "meinStandort" definiert die Parameterzeichenfolge wäre "meinStandort:-122.2,44.8"(without the quotes).
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
            Ruft ab oder legt den Namen des Bewertungsprofils zum Auswerten von übereinstimmungsbewertungen für den Abgleich Dokumente, um die Ergebnisse zu sortieren.
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
            Ruft ab, oder legt ihn fest ein Abfrageausdrucks Volltextsuche; Verwenden Sie Null oder "*" alle Dokumente übereinstimmen.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, die die Volltextsuche einschließt.
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
            Ruft ab oder legt einen Wert, der angibt, ob einige oder alle Suchbegriffe übereinstimmen müssen, damit das Dokument als Übereinstimmung zu zählen. Folgende Werte sind möglich: 'beliebig', 'all'
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste der abzurufenden Felder. Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.
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
            Ruft ab oder legt die Anzahl der zu überspringenden Suchergebnisse. Dieser Wert darf nicht größer als 100.000 sein. Wenn Sie Dokumente in Folge überprüfen müssen, aber nicht überspringen aufgrund dieser Einschränkung verwenden, sollten Sie OrderBy auf einen vollständig sortierten Schlüssel und Filter mit einer Bereichsabfrage stattdessen.
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
            Ruft ab oder legt die Anzahl der abzurufenden Suchergebnisse. Dies kann in Verbindung mit Skip verwendet werden, zum Implementieren einer clientseitigen Auslagerung der Suchergebnisse. Wenn Ergebnisse aufgrund von serverseitiges Paging abgeschnitten werden, wird die Antwort ein Fortsetzungstoken enthalten, die zum Abrufen der nächsten Seite mit Ergebnissen ContinueSearch übergeben werden kann. Weitere Informationen finden Sie in der DocumentSearchResponse.ContinuationToken.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>