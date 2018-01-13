<Type Name="RangeFacetResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangeFacetResult&lt;T&gt; where T : struct" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangeFacetResult`1&lt;struct .ctor (class System.ValueType) T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.RangeFacetResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangeFacetResult(Of T)" />
  <TypeSignature Language="F#" Value="type RangeFacetResult&lt;'T (requires 'T : struct)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <ParameterAttribute>NotNullableValueTypeConstraint</ParameterAttribute>
        <BaseTypeName>System.ValueType</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            Ein Typ, der den Typ des Felds entspricht, der das Facet angewendet wurde. Gültige Typen sind <c cref="T:System.DateTimeOffset">"DateTimeOffset"</c>, <c cref="T:System.Double">doppelte</c>, und <c cref="T:System.Int64">Int64</c> (lang in c#).
            </typeparam>
    <summary>
            Ein einzelner Bucket des Bereichs Abfrageergebnisses eines Facets, das die Anzahl von Dokumenten mit einem Feldwert meldet, das in einem bestimmten Bereich angibt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;T&gt; From { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;!T&gt; From" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.From" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property From As Nullable(Of T)" />
      <MemberSignature Language="F#" Value="member this.From : Nullable&lt;'T (requires 'T : struct)&gt;" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.From" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;T&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;T&gt; To { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;!T&gt; To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.To" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property To As Nullable(Of T)" />
      <MemberSignature Language="F#" Value="member this.To : Nullable&lt;'T (requires 'T : struct)&gt;" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, die exklusive obere Grenze für des Facets Bereich oder Null, um anzugeben, dass es keine obere Grenze (z. B. für den letzten Bucket).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>