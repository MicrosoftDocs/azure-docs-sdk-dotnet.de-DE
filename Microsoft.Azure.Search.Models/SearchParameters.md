<Type Name="SearchParameters" FullName="Microsoft.Azure.Search.Models.SearchParameters">
  <TypeSignature Language="C#" Value="public class SearchParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchParameters" />
  <TypeSignature Language="F#" Value="type SearchParameters = class" />
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
      <MemberSignature Language="C#" Value="public SearchParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParameters.#ctor" />
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
            Initialisiert eine neue Instanz der SearchParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Facets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Facets" />
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
            Ruft ab oder legt die Liste der Facet-Ausdrücke, die für die Suchabfrage gelten. Jedes Facet-Ausdruck enthält einen Feldnamen, optional gefolgt von einer durch Trennzeichen getrennte Liste von Name-Wert-Paaren.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Filter" />
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
            Ruft ab oder legt den OData-$filter Ausdruck für die Suchabfrage gelten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HighlightFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HighlightFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightFields" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HighlightFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightFields" />
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
            Ruft ab oder legt die Liste von Feldnamen, die für treffermarkierungen verwendet.
            Nur durchsuchbare Feldern können für die Treffermarkierung verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightPostTag" />
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
            Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen. Muss mit HighlightPreTag festgelegt werden. Standardmäßig wird &amp;Lt; / em&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightPreTag" />
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
            Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen.
            Muss mit HighlightPostTag festgelegt werden. Standardmäßig wird &amp;Lt; Em&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalResultCount">
      <MemberSignature Language="C#" Value="public bool IncludeTotalResultCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeTotalResultCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.IncludeTotalResultCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeTotalResultCount As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeTotalResultCount : bool with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.IncludeTotalResultCount" />
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
            Ruft ab oder legt einen Wert, der angibt, ob die Gesamtzahl der Ergebnisse abzurufen. Die Standardeinstellung ist "false". Wenn dieser Wert auf "true" kann die Leistung auswirken. Beachten Sie, dass die zurückgegebene Anzahl ein Näherungswert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.MinimumCoverage" />
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
            Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer Suchabfrage, damit die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen. Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein. Der Standardwert ist 100.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OrderBy : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.OrderBy" />
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
            Ruft ab oder legt die Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse. Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein. Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen. Standardmäßig wird in aufsteigender Reihenfolge sortiert. Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt. Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend. Es kann höchstens 32 Orderby-Klausel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.QueryType QueryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.QueryType QueryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.QueryType" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryType As QueryType" />
      <MemberSignature Language="F#" Value="member this.QueryType : Microsoft.Azure.Search.Models.QueryType with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.QueryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.QueryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der die Syntax der Suchabfrage angibt.
            Der Standardwert ist 'einfach'. Verwenden Sie 'full' aus, wenn die Abfrage die Lucene-Abfragesyntax verwendet. Mögliche Werte für diese Eigenschaft sind: 'einfach', 'full'.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt; ScoringParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringParameter&gt; ScoringParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.ScoringParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringParameters As IList(Of ScoringParameter)" />
      <MemberSignature Language="F#" Value="member this.ScoringParameters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.ScoringParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Parameterwerte zur Bewertung von Funktionen (z. B. ReferencePointParameter) verwendet werden soll. Jeder Parameter ist ein Name/Wert-Paar, das in einem "scoringparameter"-Objekt gekapselt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringProfile">
      <MemberSignature Language="C#" Value="public string ScoringProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScoringProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.ScoringProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringProfile As String" />
      <MemberSignature Language="F#" Value="member this.ScoringProfile : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.ScoringProfile" />
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
            Ruft ab oder legt den Namen des Bewertungsprofils zum Auswerten von übereinstimmungsbewertungen für den Abgleich Dokumente, um die Ergebnisse zu sortieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SearchFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.SearchFields" />
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
            Ruft ab oder legt die Liste von Feldnamen, die die Volltextsuche einschließt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SearchMode SearchMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.SearchMode SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchMode As SearchMode" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Microsoft.Azure.Search.Models.SearchMode with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SearchMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob einige oder alle Suchbegriffe übereinstimmen müssen, damit das Dokument als Übereinstimmung zu zählen. Mögliche Werte für diese Eigenschaft sind: "alle", "all".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Select" />
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
            Ruft ab oder legt die Liste der Felder abrufen. Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Skip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Skip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Skip" />
      <MemberSignature Language="VB.NET" Value="Public Property Skip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Skip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Skip" />
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
            Ruft ab oder legt die Anzahl der zu überspringenden Suchergebnisse. Dieser Wert darf nicht größer als 100.000 sein. Wenn Sie Dokumente in Folge überprüfen müssen, aber nicht überspringen aufgrund dieser Einschränkung verwenden, sollten Sie OrderBy auf einen vollständig sortierten Schlüssel und Filter mit einer Bereichsabfrage stattdessen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Top" />
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
            Ruft ab oder legt die Anzahl der abzurufenden Suchergebnisse. Dies kann in Verbindung mit Skip verwendet werden, zum Implementieren einer clientseitigen Auslagerung der Suchergebnisse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="searchParameters.ToString " />
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
            Konvertiert die SearchParameters-Instanz in einer URL-Abfragezeichenfolge.
            </summary>
        <returns>Eine URL-Abfragezeichenfolge mit die Suchparameter angegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>