<Type Name="OperationalInsightsDataClientExtensions" FullName="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions">
  <TypeSignature Language="C#" Value="public static class OperationalInsightsDataClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationalInsightsDataClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationalInsightsDataClientExtensions" />
  <TypeSignature Language="F#" Value="type OperationalInsightsDataClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2c47b-101">Erweiterungsmethoden für OperationalInsightsDataClient.</span><span class="sxs-lookup"><span data-stu-id="2c47b-101">Extension methods for OperationalInsightsDataClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.OperationalInsights.Models.QueryResults Query (this Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient operations, string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.OperationalInsights.Models.QueryResults Query(class Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient operations, string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions.Query(Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Query (operations As IOperationalInsightsDataClient, query As String, Optional timespan As Nullable(Of TimeSpan) = null, Optional workspaces As IList(Of String) = null) As QueryResults" />
      <MemberSignature Language="F#" Value="static member Query : Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient * string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.OperationalInsights.Models.QueryResults" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions.Query (operations, query, timespan, workspaces)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.QueryResults</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient" RefType="this" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c47b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c47b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="2c47b-103">Die auszuführende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2c47b-103">The query to execute.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="2c47b-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="2c47b-104">Optional.</span></span> <span data-ttu-id="2c47b-105">Die Zeitspanne für die zum Abfragen von Daten.</span><span class="sxs-lookup"><span data-stu-id="2c47b-105">The timespan over which to query data.</span></span> <span data-ttu-id="2c47b-106">Dies ist ein Wert für den Zeitraum ISO8601.</span><span class="sxs-lookup"><span data-stu-id="2c47b-106">This is an ISO8601 time period value.</span></span>  <span data-ttu-id="2c47b-107">Diese Zeitspanne wird zusätzlich zu anderen angewendet, die im Abfrageausdruck angegeben sind.</span><span class="sxs-lookup"><span data-stu-id="2c47b-107">This timespan is applied in addition to any that are specified in the query expression.</span></span>
            </param>
        <param name="workspaces">
            <span data-ttu-id="2c47b-108">Eine Liste der Arbeitsbereiche, die in der Abfrage enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="2c47b-108">A list of workspaces that are included in the query.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c47b-109">Führen Sie eine Analyseabfrage</span><span class="sxs-lookup"><span data-stu-id="2c47b-109">Execute an Analytics query</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2c47b-110">Führt eine Analyseabfrage für Daten.</span><span class="sxs-lookup"><span data-stu-id="2c47b-110">Executes an Analytics query for data.</span></span>
            <span data-ttu-id="2c47b-111">[Hier](/documentation/2-Using-the-API/Query) ist ein Beispiel für eine Analyseabfrage mit POST.</span><span class="sxs-lookup"><span data-stu-id="2c47b-111">[Here](/documentation/2-Using-the-API/Query) is an example for using POST with an Analytics query.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt; QueryAsync (this Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient operations, string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.OperationalInsights.Models.QueryResults&gt; QueryAsync(class Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient operations, string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions.QueryAsync(Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member QueryAsync : Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient * string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions.QueryAsync (operations, query, timespan, workspaces, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.OperationalInsights.OperationalInsightsDataClientExtensions/&lt;QueryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient" RefType="this" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c47b-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c47b-112">The operations group for this extension method.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="2c47b-113">Die auszuführende Abfrage.</span><span class="sxs-lookup"><span data-stu-id="2c47b-113">The query to execute.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="2c47b-114">Optional.</span><span class="sxs-lookup"><span data-stu-id="2c47b-114">Optional.</span></span> <span data-ttu-id="2c47b-115">Die Zeitspanne für die zum Abfragen von Daten.</span><span class="sxs-lookup"><span data-stu-id="2c47b-115">The timespan over which to query data.</span></span> <span data-ttu-id="2c47b-116">Dies ist ein Wert für den Zeitraum ISO8601.</span><span class="sxs-lookup"><span data-stu-id="2c47b-116">This is an ISO8601 time period value.</span></span>  <span data-ttu-id="2c47b-117">Diese Zeitspanne wird zusätzlich zu anderen angewendet, die im Abfrageausdruck angegeben sind.</span><span class="sxs-lookup"><span data-stu-id="2c47b-117">This timespan is applied in addition to any that are specified in the query expression.</span></span>
            </param>
        <param name="workspaces">
            <span data-ttu-id="2c47b-118">Eine Liste der Arbeitsbereiche, die in der Abfrage enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="2c47b-118">A list of workspaces that are included in the query.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c47b-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c47b-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c47b-120">Führen Sie eine Analyseabfrage</span><span class="sxs-lookup"><span data-stu-id="2c47b-120">Execute an Analytics query</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="2c47b-121">Führt eine Analyseabfrage für Daten.</span><span class="sxs-lookup"><span data-stu-id="2c47b-121">Executes an Analytics query for data.</span></span>
            <span data-ttu-id="2c47b-122">[Hier](/documentation/2-Using-the-API/Query) ist ein Beispiel für eine Analyseabfrage mit POST.</span><span class="sxs-lookup"><span data-stu-id="2c47b-122">[Here](/documentation/2-Using-the-API/Query) is an example for using POST with an Analytics query.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>