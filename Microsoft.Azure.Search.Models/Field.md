<Type Name="Field" FullName="Microsoft.Azure.Search.Models.Field">
  <TypeSignature Language="C#" Value="public class Field" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Field extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Field" />
  <TypeSignature Language="VB.NET" Value="Public Class Field" />
  <TypeSignature Language="F#" Value="type Field = class" />
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
            Stellt ein Feld in einer Definition des Indexes in Azure Search dar, der Name, Datentyp und Suchverhalten eines Felds beschreibt.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor" />
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
            Initialisiert eine neue Instanz der Feld-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.AnalyzerName analyzerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.AnalyzerName analyzerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.AnalyzerName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.AnalyzerName -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, analyzerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="analyzerName" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Felds.</param>
        <param name="analyzerName">Der Name des Analyzers für das Feld verwendet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der Feld-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>Das neue Feld werden automatisch die durchsuchbar und des Typs Edm.String.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.DataType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.DataType -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, dataType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="Microsoft.Azure.Search.Models.DataType" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Felds.</param>
        <param name="dataType">Der Datentyp des Felds.</param>
        <summary>
            Initialisiert eine neue Instanz der Feld-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.DataType dataType, Microsoft.Azure.Search.Models.AnalyzerName analyzerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataType dataType, class Microsoft.Azure.Search.Models.AnalyzerName analyzerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.DataType,Microsoft.Azure.Search.Models.AnalyzerName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.DataType * Microsoft.Azure.Search.Models.AnalyzerName -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, dataType, analyzerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="Microsoft.Azure.Search.Models.DataType" />
        <Parameter Name="analyzerName" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Felds.</param>
        <param name="dataType">Der Datentyp des Felds.</param>
        <param name="analyzerName">Der Name des Analyzers für das Feld verwendet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der Feld-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>Das neue Feld wird automatisch durchsuchbar sein.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName Analyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName Analyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Analyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.Analyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.Analyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="analyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Analyzers für die Zeit für Suche und Indizierung für das Feld verwenden. Diese Option kann nur mit durchsuchbaren Felder verwendet werden, und es kann nicht zusammen mit SearchAnalyzer oder IndexAnalyzer festgelegt werden. Eine einmal für ein Feld gewählte Analysemethode kann nicht mehr geändert werden.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexAnalyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName IndexAnalyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName IndexAnalyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IndexAnalyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexAnalyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.IndexAnalyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.IndexAnalyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexAnalyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Analyzers für bei der Indizierung für das Feld verwendet. Diese Option kann nur mit durchsuchbaren Felder verwendet werden. Er muss zusammen mit SearchAnalyzer festgelegt werden, und es kann nicht zusammen mit der Option Analyzer festgelegt werden. Eine einmal für ein Feld gewählte Analysemethode kann nicht mehr geändert werden.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFacetable">
      <MemberSignature Language="C#" Value="public bool IsFacetable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFacetable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsFacetable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsFacetable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFacetable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsFacetable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("facetable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob es möglich, das Facet für dieses Feld ist fest. Gilt nicht für Geo-Point-Felder. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFilterable">
      <MemberSignature Language="C#" Value="public bool IsFilterable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFilterable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsFilterable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsFilterable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFilterable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsFilterable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("filterable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob das Feld in Filterausdrücken verwendet werden kann. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsKey">
      <MemberSignature Language="C#" Value="public bool IsKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsKey" />
      <MemberSignature Language="VB.NET" Value="Public Property IsKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsKey : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob das Feld den Schlüssel des Indexes ist. Nur für Zeichenfolgenfelder gültig. Jeder Index muss genau ein Schlüsselfeld haben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetrievable">
      <MemberSignature Language="C#" Value="public bool IsRetrievable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRetrievable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsRetrievable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRetrievable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRetrievable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsRetrievable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("retrievable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob das Feld in einem Suchergebnis zurückgegeben werden kann. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchable">
      <MemberSignature Language="C#" Value="public bool IsSearchable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSearchable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsSearchable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSearchable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsSearchable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("searchable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob das Feld in Volltextsuchen enthalten ist. Nur für String oder Auflistung Zeichenfolgenfelder gültig. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSortable">
      <MemberSignature Language="C#" Value="public bool IsSortable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSortable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsSortable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSortable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSortable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsSortable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("sortable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob das Feld in Orderby-Ausdrücken verwendet werden kann. Gilt nicht für Zeichenfolgenfelder-Auflistung.
            Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Field.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Felds ab oder legt ihn fest.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAnalyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName SearchAnalyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName SearchAnalyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.SearchAnalyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchAnalyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.SearchAnalyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.SearchAnalyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchAnalyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Analyzers für das Feld bei der Suche verwendet. Diese Option kann nur mit durchsuchbaren Felder verwendet werden. Er muss zusammen mit IndexAnalyzer festgelegt werden, und es kann nicht zusammen mit der Option Analyzer festgelegt werden. Dieses Analyseprogramm kann für ein vorhandenes Feld aktualisiert werden.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynonymMaps">
      <MemberSignature Language="C#" Value="public string[] SynonymMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] SynonymMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.SynonymMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property SynonymMaps As String()" />
      <MemberSignature Language="F#" Value="member this.SynonymMaps : string[] with get, set" Usage="Microsoft.Azure.Search.Models.Field.SynonymMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonymMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Namen der Synonym Zuordnungen für das Feld fest. Diese Option ermöglicht Abfrage Zeit Synonym Erweiterung für Suchvorgänge für das Feld und kann nur auf durchsuchbaren Felder verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataType with get, set" Usage="Microsoft.Azure.Search.Models.Field.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Datentyp des Felds fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="field.Validate " />
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
            Überprüfen Sie das Objekt. Löst ValidationException aus, wenn die Validierung fehlschlägt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>