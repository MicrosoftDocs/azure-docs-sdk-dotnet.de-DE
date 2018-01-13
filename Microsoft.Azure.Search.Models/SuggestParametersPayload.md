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
            Parameter zum Filtern, sortieren, Fuzzyübereinstimmung und andere Vorschläge Abfragen Verhalten.
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
            Initialisiert eine neue Instanz der SuggestParametersPayload-Klasse.
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
        <param name="filter">Die OData-$filter-Ausdruck, der für die Abfrage Vorschläge gelten.</param>
        <param name="fuzzy">Ein Wert, der angibt, ob verwenden die Fuzzyübereinstimmung für die vorschlagsabfrage. Die Standardeinstellung ist "false". Bei Festlegung auf "true", die Abfrage findet Vorschläge auch wenn es eine Zeichen anders ist oder fehlende in den Suchtext ein. Dies führt in einigen Szenarien zwar zu besseren Ergebnissen, geht jedoch zulasten der Leistung, da Fuzzysuchen von Vorschlägen langsamer sind und mehr Ressourcen belegen.</param>
        <param name="highlightPostTag">Ein zeichenfolgentag, die angefügt wird, um Treffer wird hervorgehoben. Muss mit HighlightPreTag festgelegt werden. Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</param>
        <param name="highlightPreTag">Ein zeichenfolgentag, die vorangestellt wird, um Treffer wird hervorgehoben. Muss mit HighlightPostTag festgelegt werden. Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.</param>
        <param name="minimumCoverage">Eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer vorschlagsabfrage in der Reihenfolge für die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen. Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein. Der Standardwert ist 80.</param>
        <param name="orderBy">Die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse. Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein. Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen. Standardmäßig wird in aufsteigender Reihenfolge sortiert. Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt. Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend. Es kann höchstens 32 Orderby-Klausel.</param>
        <param name="search">Das Suchen von Text auf der Vorschläge basieren.</param>
        <param name="searchFields">Die durch Trennzeichen getrennte Liste von Feldnamen, berücksichtigen beim Abfragen der Vorschläge.</param>
        <param name="select">Die durch Trennzeichen getrennte Liste der Felder abrufen. Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.</param>
        <param name="suggesterName">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</param>
        <param name="top">Die Anzahl der abzurufenden Vorschläge. Dies muss ein Wert zwischen 1 und 100 sein. Der Standardwert ist 5.</param>
        <summary>
            Initialisiert eine neue Instanz der SuggestParametersPayload-Klasse.
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
            Abrufen oder festlegen den OData-$filter-Ausdruck, der für die Abfrage Vorschläge gelten.
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
            Ruft ab oder legt einen Wert, der angibt, ob verwenden die Fuzzyübereinstimmung für die vorschlagsabfrage. Die Standardeinstellung ist "false". Bei Festlegung auf "true", die Abfrage findet Vorschläge auch wenn es eine Zeichen anders ist oder fehlende in den Suchtext ein. Dies führt in einigen Szenarien zwar zu besseren Ergebnissen, geht jedoch zulasten der Leistung, da Fuzzysuchen von Vorschlägen langsamer sind und mehr Ressourcen belegen.
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
            Ermittelt oder definiert ein zeichenfolgentag, die angefügt wird, um Merkmale zu treffen. Muss mit HighlightPreTag festgelegt werden. Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.
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
            Ermittelt oder definiert ein zeichenfolgentag, die vorangestellt wird, um Merkmale zu treffen. Muss mit HighlightPostTag festgelegt werden. Wenn nicht angegeben, ist die Treffermarkierung von Vorschlägen deaktiviert.
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
            Ruft ab oder legt eine Zahl zwischen 0 und 100, der angibt, der des Prozentsatz des Indexes, die von einer vorschlagsabfrage in der Reihenfolge für die Abfrage als Erfolg gemeldet werden abgedeckt werden müssen. Dieser Parameter kann nützlich zum Sicherstellen der Verfügbarkeit der Suche selbst für Dienste mit nur ein Replikat sein. Der Standardwert ist 80.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste der OData-$orderby-Ausdrücke, nach denen zum Sortieren der Ergebnisse. Jeder Ausdruck kann entweder ein Feldname oder ein Aufruf der Funktion geo.distance() sein. Jeder Ausdruck kann Asc um aufsteigend und "DESC", um absteigend folgen. Standardmäßig wird in aufsteigender Reihenfolge sortiert. Verknüpfungen werden durch die Ergebnisstände von Dokumenten getrennt. Wenn keine OrderBy angegeben wird, ist der Standard-Sortierreihenfolge nach dokumentübereinstimmungsbewertung Absteigend. Es kann höchstens 32 Orderby-Klausel.
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
            Ruft ab oder legt den Suchtext ein, auf denen Vorschläge basieren.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste von Feldnamen, berücksichtigen beim Abfragen der Vorschläge.
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
            Ruft ab oder legt die durch Trennzeichen getrennte Liste der abzurufenden Felder. Wenn nicht anders angegeben, werden alle im Schema als abrufbar gekennzeichnete Felder einbezogen.
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
            Ruft ab oder legt den Namen des suggesters gemäß der suggester-Auflistung, die Teil der Indexdefinition ist.
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
            Ruft ab oder legt die Anzahl der abzurufenden Vorschläge. Dies muss ein Wert zwischen 1 und 100 sein. Der Standardwert ist 5.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>