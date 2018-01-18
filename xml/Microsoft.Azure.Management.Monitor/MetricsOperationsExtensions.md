<Type Name="MetricsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MetricsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MetricsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MetricsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MetricsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9b927-101">Erweiterungsmethoden für MetricsOperations.</span><span class="sxs-lookup"><span data-stu-id="9b927-101">Extension methods for MetricsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Models.Response List (this Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Models.Response List(class Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IMetricsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IMetricsOperations, resourceUri As String, Optional odataQuery As ODataQuery(Of MetadataValue) = null, Optional timespan As String = null, Optional interval As Nullable(Of TimeSpan) = null, Optional metric As String = null, Optional aggregation As String = null, Optional resultType As Nullable(Of ResultType) = null) As Response" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IMetricsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Response" Usage="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.List (operations, resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.Response</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b927-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b927-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9b927-103">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9b927-103">The identifier of the resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9b927-104">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9b927-104">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="9b927-105">Der Zeitpunkt der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="9b927-105">The timespan of the query.</span></span> <span data-ttu-id="9b927-106">Es ist eine Zeichenfolge mit dem folgenden Format "StartDateTime_ISO/EndDateTime_ISO".</span><span class="sxs-lookup"><span data-stu-id="9b927-106">It is a string with the following format 'startDateTime_ISO/endDateTime_ISO'.</span></span>
            </param>
        <param name="interval">
            <span data-ttu-id="9b927-107">Das Intervall (d. h. timegrain-Wert) der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="9b927-107">The interval (i.e. timegrain) of the query.</span></span>
            </param>
        <param name="metric">
            <span data-ttu-id="9b927-108">Der Name der abzurufenden Metrik.</span><span class="sxs-lookup"><span data-stu-id="9b927-108">The name of the metric to retrieve.</span></span>
            </param>
        <param name="aggregation">
            <span data-ttu-id="9b927-109">Die Liste der Aggregationstypen (durch Kommas getrennt) abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9b927-109">The list of aggregation types (comma separated) to retrieve.</span></span>
            </param>
        <param name="resultType">
            <span data-ttu-id="9b927-110">Reduziert die Menge der gesammelten Daten.</span><span class="sxs-lookup"><span data-stu-id="9b927-110">Reduces the set of data collected.</span></span> <span data-ttu-id="9b927-111">Die Syntax zulässig, hängt von den Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="9b927-111">The syntax allowed depends on the operation.</span></span> <span data-ttu-id="9b927-112">Finden Sie unter der vorgangsbeschreibung für Details.</span><span class="sxs-lookup"><span data-stu-id="9b927-112">See the operation's description for details.</span></span> <span data-ttu-id="9b927-113">Folgende Werte sind möglich: "Daten", "Metadaten"</span><span class="sxs-lookup"><span data-stu-id="9b927-113">Possible values include: 'Data', 'Metadata'</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b927-114">**Listet die metrischen Werte für eine Ressource**.</span><span class="sxs-lookup"><span data-stu-id="9b927-114">**Lists the metric values for a resource**.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Models.Response&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IMetricsOperations operations, string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IMetricsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IMetricsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;" Usage="Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions.ListAsync (operations, resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.MetricsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9b927-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9b927-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9b927-116">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9b927-116">The identifier of the resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="9b927-117">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="9b927-117">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="9b927-118">Der Zeitpunkt der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="9b927-118">The timespan of the query.</span></span> <span data-ttu-id="9b927-119">Es ist eine Zeichenfolge mit dem folgenden Format "StartDateTime_ISO/EndDateTime_ISO".</span><span class="sxs-lookup"><span data-stu-id="9b927-119">It is a string with the following format 'startDateTime_ISO/endDateTime_ISO'.</span></span>
            </param>
        <param name="interval">
            <span data-ttu-id="9b927-120">Das Intervall (d. h. timegrain-Wert) der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="9b927-120">The interval (i.e. timegrain) of the query.</span></span>
            </param>
        <param name="metric">
            <span data-ttu-id="9b927-121">Der Name der abzurufenden Metrik.</span><span class="sxs-lookup"><span data-stu-id="9b927-121">The name of the metric to retrieve.</span></span>
            </param>
        <param name="aggregation">
            <span data-ttu-id="9b927-122">Die Liste der Aggregationstypen (durch Kommas getrennt) abgerufen.</span><span class="sxs-lookup"><span data-stu-id="9b927-122">The list of aggregation types (comma separated) to retrieve.</span></span>
            </param>
        <param name="resultType">
            <span data-ttu-id="9b927-123">Reduziert die Menge der gesammelten Daten.</span><span class="sxs-lookup"><span data-stu-id="9b927-123">Reduces the set of data collected.</span></span> <span data-ttu-id="9b927-124">Die Syntax zulässig, hängt von den Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="9b927-124">The syntax allowed depends on the operation.</span></span> <span data-ttu-id="9b927-125">Finden Sie unter der vorgangsbeschreibung für Details.</span><span class="sxs-lookup"><span data-stu-id="9b927-125">See the operation's description for details.</span></span> <span data-ttu-id="9b927-126">Folgende Werte sind möglich: "Daten", "Metadaten"</span><span class="sxs-lookup"><span data-stu-id="9b927-126">Possible values include: 'Data', 'Metadata'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b927-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9b927-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b927-128">**Listet die metrischen Werte für eine Ressource**.</span><span class="sxs-lookup"><span data-stu-id="9b927-128">**Lists the metric values for a resource**.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>