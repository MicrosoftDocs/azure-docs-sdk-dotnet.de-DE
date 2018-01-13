<Type Name="QueryResult" FullName="Microsoft.Azure.Mobile.Server.Tables.QueryResult">
  <TypeSignature Language="C#" Value="public class QueryResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueryResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.QueryResult" />
  <TypeSignature Language="VB.NET" Value="Public Class QueryResult" />
  <TypeSignature Language="F#" Value="type QueryResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Ergebnisse einer Abfrage Anforderung sowie die Gesamtzahl der Entitäten, die durch die Anforderungs-URI identifiziert wird, nachdem alle $filter-systemabfrageoptionen angewendet wurden. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryResult (System.Collections.IEnumerable results, Nullable&lt;long&gt; totalCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.IEnumerable results, valuetype System.Nullable`1&lt;int64&gt; totalCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.QueryResult.#ctor(System.Collections.IEnumerable,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (results As IEnumerable, totalCount As Nullable(Of Long))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Tables.QueryResult : System.Collections.IEnumerable * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Mobile.Server.Tables.QueryResult" Usage="new Microsoft.Azure.Mobile.Server.Tables.QueryResult (results, totalCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="results" Type="System.Collections.IEnumerable" />
        <Parameter Name="totalCount" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="results">Die Teilmenge, die das Ergebnis der Abfrage darstellt.</param>
        <param name="totalCount">Optional die Gesamtzahl oder Elemente verfügbar.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Tables.QueryResult" /> mit einer bestimmten Teilmenge der <paramref name="results" /> und optional eine <paramref name="totalCount" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.QueryResult.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.QueryResult.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Gesamtanzahl der Entitäten, die durch die Anforderungs-URI identifiziert wird, nachdem alle $filter-systemabfrageoptionen angewendet wurden. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.IEnumerable Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.IEnumerable Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.QueryResult.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IEnumerable" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.IEnumerable with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.QueryResult.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerable</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Ergebnisse der Abfrage.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>