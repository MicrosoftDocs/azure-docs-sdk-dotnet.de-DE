<Type Name="SearchMetadata" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata">
  <TypeSignature Language="C#" Value="public class SearchMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchMetadata" />
  <TypeSignature Language="F#" Value="type SearchMetadata = class" />
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
            Metadaten für Suchergebnisse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SearchMetadata-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchMetadata (string searchId = null, string resultType = null, Nullable&lt;long&gt; total = null, Nullable&lt;long&gt; top = null, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; coreSummaries = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; lastUpdated = null, string eTag = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; sort = null, Nullable&lt;long&gt; requestTime = null, string aggregatedValueField = null, string aggregatedGroupingFields = null, Nullable&lt;long&gt; sum = null, Nullable&lt;long&gt; max = null, Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema schema = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string searchId, string resultType, valuetype System.Nullable`1&lt;int64&gt; total, valuetype System.Nullable`1&lt;int64&gt; top, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; coreSummaries, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdated, string eTag, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; sort, valuetype System.Nullable`1&lt;int64&gt; requestTime, string aggregatedValueField, string aggregatedGroupingFields, valuetype System.Nullable`1&lt;int64&gt; sum, valuetype System.Nullable`1&lt;int64&gt; max, class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema schema) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.#ctor(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.OperationalInsights.Models.SearchSort},System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional searchId As String = null, Optional resultType As String = null, Optional total As Nullable(Of Long) = null, Optional top As Nullable(Of Long) = null, Optional id As String = null, Optional coreSummaries As IList(Of CoreSummary) = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional lastUpdated As Nullable(Of DateTime) = null, Optional eTag As String = null, Optional sort As IList(Of SearchSort) = null, Optional requestTime As Nullable(Of Long) = null, Optional aggregatedValueField As String = null, Optional aggregatedGroupingFields As String = null, Optional sum As Nullable(Of Long) = null, Optional max As Nullable(Of Long) = null, Optional schema As SearchMetadataSchema = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; * Nullable&lt;int64&gt; * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata (searchId, resultType, total, top, id, coreSummaries, status, startTime, lastUpdated, eTag, sort, requestTime, aggregatedValueField, aggregatedGroupingFields, sum, max, schema)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="searchId" Type="System.String" />
        <Parameter Name="resultType" Type="System.String" />
        <Parameter Name="total" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="coreSummaries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastUpdated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="sort" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt;" />
        <Parameter Name="requestTime" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="aggregatedValueField" Type="System.String" />
        <Parameter Name="aggregatedGroupingFields" Type="System.String" />
        <Parameter Name="sum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="max" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="schema" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema" />
      </Parameters>
      <Docs>
        <param name="searchId">Die Anforderungs-Id der Suche.</param>
        <param name="resultType">Der Ergebnistyp für die Suche.</param>
        <param name="total">Die Gesamtanzahl der Suchergebnisse.</param>
        <param name="top">Die Anzahl der obersten Suchergebnisse.</param>
        <param name="id">Die Id der Anforderung Ergebnisse suchen.</param>
        <param name="coreSummaries">Die Zusammenfassungen der Core.</param>
        <param name="status">Der Status der Suchergebnisse.</param>
        <param name="startTime">Die Startzeit für die Suche.</param>
        <param name="lastUpdated">Der Zeitpunkt der letzten Aktualisierung.</param>
        <param name="eTag">Das ETag der Suchergebnisse.</param>
        <param name="sort">Wie die Ergebnisse sortiert werden.</param>
        <param name="requestTime">Die Anforderungszeit.</param>
        <param name="aggregatedValueField">Das Feld aggregierten Wert.</param>
        <param name="aggregatedGroupingFields">Der aggregierte Gruppierungsfelder.</param>
        <param name="sum">Die Summe der alle Aggregate, die im Resultset zurückgegeben.</param>
        <param name="max">Die Maximalwerte für alle Aggregate werden im Resultset zurückgegeben.</param>
        <param name="schema">Das Schema.</param>
        <summary>
            Initialisiert eine neue Instanz der SearchMetadata-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedGroupingFields">
      <MemberSignature Language="C#" Value="public string AggregatedGroupingFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregatedGroupingFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.AggregatedGroupingFields" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregatedGroupingFields As String" />
      <MemberSignature Language="F#" Value="member this.AggregatedGroupingFields : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.AggregatedGroupingFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregatedGroupingFields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest aggregierte Gruppierungsfelder.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedValueField">
      <MemberSignature Language="C#" Value="public string AggregatedValueField { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregatedValueField" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.AggregatedValueField" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregatedValueField As String" />
      <MemberSignature Language="F#" Value="member this.AggregatedValueField : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.AggregatedValueField" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregatedValueField")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert das Feld aggregierten Wert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreSummaries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; CoreSummaries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; CoreSummaries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.CoreSummaries" />
      <MemberSignature Language="VB.NET" Value="Public Property CoreSummaries As IList(Of CoreSummary)" />
      <MemberSignature Language="F#" Value="member this.CoreSummaries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.CoreSummaries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="CoreSummaries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.CoreSummary&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Zusammenfassungen der Core.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag der Suchergebnisse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Id der Anforderung Ergebnisse suchen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.LastUpdated" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdated : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.LastUpdated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="LastUpdated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt des letzten Updates.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Max { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Max" />
      <MemberSignature Language="VB.NET" Value="Public Property Max As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Max : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Max" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="max")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Maximalwerte für alle Aggregate, die im Resultset zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.RequestTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTime As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestTime : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.RequestTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requestTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anforderungszeit fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultType">
      <MemberSignature Language="C#" Value="public string ResultType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResultType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.ResultType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultType As String" />
      <MemberSignature Language="F#" Value="member this.ResultType : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.ResultType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resultType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Ergebnistyp für die Suche.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema Schema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Schema" />
      <MemberSignature Language="VB.NET" Value="Public Property Schema As SearchMetadataSchema" />
      <MemberSignature Language="F#" Value="member this.Schema : Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadataSchema</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Schema.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchId">
      <MemberSignature Language="C#" Value="public string SearchId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.SearchId" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchId As String" />
      <MemberSignature Language="F#" Value="member this.SearchId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.SearchId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="RequestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anforderungs-Id der Suche.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sort">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; Sort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; Sort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Sort" />
      <MemberSignature Language="VB.NET" Value="Public Property Sort As IList(Of SearchSort)" />
      <MemberSignature Language="F#" Value="member this.Sort : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Sort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchSort&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie die Ergebnisse sortiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="StartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit für die Suche fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status der Suchergebnisse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Sum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Sum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Sum" />
      <MemberSignature Language="VB.NET" Value="Public Property Sum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Sum : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Sum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Summe für alle Aggregate, die im Resultset zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Top" />
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
            Ruft ab oder legt die Anzahl der obersten Suchergebnisse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Total { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Total" />
      <MemberSignature Language="VB.NET" Value="Public Property Total As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Total : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchMetadata.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="total")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Gesamtanzahl der Suchergebnisse fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>