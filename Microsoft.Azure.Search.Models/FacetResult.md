<Type Name="FacetResult" FullName="Microsoft.Azure.Search.Models.FacetResult">
  <TypeSignature Language="C#" Value="public class FacetResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FacetResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FacetResult" />
  <TypeSignature Language="VB.NET" Value="Public Class FacetResult" />
  <TypeSignature Language="F#" Value="type FacetResult = class" />
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
            Ein einzelner Bucket des Abfrageergebnisses eines Facets, das die Anzahl der Dokumente mit einem Feld kann ein bestimmter Wert oder ein Intervall oder innerhalb eines bestimmten Bereichs fallen meldet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FacetResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.#ctor" />
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
            Initialisiert eine neue Instanz der Facet-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsRangeFacetResult&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt; AsRangeFacetResult&lt;T&gt; () where T : struct;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.RangeFacetResult`1&lt;!!T&gt; AsRangeFacetResult&lt;struct .ctor (class System.ValueType) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.AsRangeFacetResult``1" />
      <MemberSignature Language="VB.NET" Value="Public Function AsRangeFacetResult(Of T As Structure) () As RangeFacetResult(Of T)" />
      <MemberSignature Language="F#" Value="member this.AsRangeFacetResult : unit -&gt; Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt; (requires 'T : struct)" Usage="facetResult.AsRangeFacetResult " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <ParameterAttribute>NotNullableValueTypeConstraint</ParameterAttribute>
            <BaseTypeName>System.ValueType</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            Ein Typ, der den Typ des Felds entspricht, der das Facet angewendet wurde. Gültige Typen sind <c cref="T:System.DateTimeOffset">"DateTimeOffset"</c>, <c cref="T:System.Double">doppelte</c>, und <c cref="T:System.Int64">Int64</c> (lang in c#).
            </typeparam>
        <summary>
            Versucht, das Facet in ein bereichsfacet des angegebenen Typs zu konvertieren.
            </summary>
        <returns>Eine neue stark typisierte bereichsfacetinstanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidCastException">Diese Instanz ist kein bereichsfacet des angegebenen Typs.</exception>
      </Docs>
    </Member>
    <Member MemberName="AsValueFacetResult&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt; AsValueFacetResult&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.ValueFacetResult`1&lt;!!T&gt; AsValueFacetResult&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FacetResult.AsValueFacetResult``1" />
      <MemberSignature Language="VB.NET" Value="Public Function AsValueFacetResult(Of T) () As ValueFacetResult(Of T)" />
      <MemberSignature Language="F#" Value="member this.AsValueFacetResult : unit -&gt; Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;" Usage="facetResult.AsValueFacetResult " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            Ein Typ, der den Typ des Felds entspricht, der das Facet angewendet wurde.
            </typeparam>
        <summary>
            Versucht, das Facet in ein wertfacet des angegebenen Typs zu konvertieren.
            </summary>
        <returns>Eine neue stark typisierte wertfacetinstanz.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidCastException">Diese Instanz ist kein wertfacet des angegebenen Typs.</exception>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ungefähre Anzahl der Dokumente, die in der durch dieses Facet beschrieben Bucket fallen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="From">
      <MemberSignature Language="C#" Value="public object From { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object From" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.From" />
      <MemberSignature Language="VB.NET" Value="Public Property From As Object" />
      <MemberSignature Language="F#" Value="member this.From : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.From" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("from")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die inklusive untere Grenze des Facets Bereichs, oder Null, um anzugeben, dass es keine untere Grenze (z. B. für den ersten Bucket).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public object To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As Object" />
      <MemberSignature Language="F#" Value="member this.To : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("to")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die exklusive obere Grenze für des Facets Bereich oder Null, um anzugeben, dass es keine obere Grenze (z. B. für den letzten Bucket).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FacetType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.FacetType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As FacetType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.FacetType" Usage="Microsoft.Azure.Search.Models.FacetResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FacetType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der den Typ dieses Facets angibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FacetResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Search.Models.FacetResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Wert des Facets oder die inklusive untere Grenze ab, wenn es sich um ein intervallfacet handelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>