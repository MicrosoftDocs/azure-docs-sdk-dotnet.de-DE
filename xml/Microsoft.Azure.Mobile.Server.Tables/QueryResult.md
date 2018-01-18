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
            <span data-ttu-id="0ad2e-101">Stellt die Ergebnisse einer Abfrage Anforderung sowie die Gesamtzahl der Entitäten, die durch die Anforderungs-URI identifiziert wird, nachdem alle $filter-systemabfrageoptionen angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-101">Represents the results of a query request along with the total count of entities identified by the request URI after all $filter system query options have been applied.</span></span> 
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
        <param name="results"><span data-ttu-id="0ad2e-102">Die Teilmenge, die das Ergebnis der Abfrage darstellt.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-102">The subset representing the query result.</span></span></param>
        <param name="totalCount"><span data-ttu-id="0ad2e-103">Optional die Gesamtzahl oder Elemente verfügbar.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-103">Optionally the total count or elements available.</span></span></param>
        <summary>
            <span data-ttu-id="0ad2e-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Tables.QueryResult" /> mit einer bestimmten Teilmenge der <paramref name="results" /> und optional eine <paramref name="totalCount" />.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.QueryResult" /> with a given subset of <paramref name="results" /> and optionally a <paramref name="totalCount" />.</span></span>
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
            <span data-ttu-id="0ad2e-105">Die Gesamtanzahl der Entitäten, die durch die Anforderungs-URI identifiziert wird, nachdem alle $filter-systemabfrageoptionen angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-105">The total count of entities identified by the request URI after all $filter system query options have been applied.</span></span> 
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
            <span data-ttu-id="0ad2e-106">Die Ergebnisse der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0ad2e-106">The results of the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>