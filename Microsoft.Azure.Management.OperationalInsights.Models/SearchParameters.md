<Type Name="SearchParameters" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters">
  <TypeSignature Language="C#" Value="public class SearchParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchParameters" />
  <TypeSignature Language="F#" Value="type SearchParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter, die die Suchabfrage und den Zeitraum angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SearchParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParameters (string query, Nullable&lt;long&gt; top = null, Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight highlight = null, Nullable&lt;DateTime&gt; start = null, Nullable&lt;DateTime&gt; end = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string query, valuetype System.Nullable`1&lt;int64&gt; top, class Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight highlight, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; start, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.#ctor(System.String,System.Nullable{System.Int64},Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As String, Optional top As Nullable(Of Long) = null, Optional highlight As SearchHighlight = null, Optional start As Nullable(Of DateTime) = null, Optional end As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters : string * Nullable&lt;int64&gt; * Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters (query, top, highlight, start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="highlight" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight" />
        <Parameter Name="start" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="end" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="query">Die Abfrage zu suchen.</param>
        <param name="top">Die Zahl, die von der obersten Position abrufen.</param>
        <param name="highlight">Die Hervorhebung, die für alle Vorkommen einer Zeichenfolge aussieht.</param>
        <param name="start">Der Datumsfilter starten, damit nach diesem Datum die einzige Abfrageergebnisse zurückgegeben werden.</param>
        <param name="end">Die End Datumsfilter, damit vor diesem Datum die einzige Abfrageergebnisse zurückgegeben werden.</param>
        <summary>
            Initialisiert eine neue Instanz der SearchParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.End : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Datumsfilter End so vor diesem Datum die einzige Abfrageergebnisse zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Highlight">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight Highlight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight Highlight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Highlight" />
      <MemberSignature Language="VB.NET" Value="Public Property Highlight As SearchHighlight" />
      <MemberSignature Language="F#" Value="member this.Highlight : Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Highlight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchHighlight</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Hervorhebung, die für alle Vorkommen einer Zeichenfolge aussieht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Abfrage zu suchen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Start : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Datumsfilter starten, damit nach diesem Datum die einzige Abfrageergebnisse zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="top")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von der obersten Position abrufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="searchParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>