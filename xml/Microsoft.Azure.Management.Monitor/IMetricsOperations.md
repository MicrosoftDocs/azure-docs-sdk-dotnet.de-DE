<Type Name="IMetricsOperations" FullName="Microsoft.Azure.Management.Monitor.IMetricsOperations">
  <TypeSignature Language="C#" Value="public interface IMetricsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMetricsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IMetricsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMetricsOperations" />
  <TypeSignature Language="F#" Value="type IMetricsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="55224-101">MetricsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="55224-101">MetricsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery = null, string timespan = null, Nullable&lt;TimeSpan&gt; interval = null, string metric = null, string aggregation = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; odataQuery, string timespan, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval, string metric, string aggregation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Models.ResultType&gt; resultType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IMetricsOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.MetadataValue},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Models.ResultType},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt;" Usage="iMetricsOperations.ListWithHttpMessagesAsync (resourceUri, odataQuery, timespan, interval, metric, aggregation, resultType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Models.Response&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.MetadataValue&gt;" />
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="metric" Type="System.String" />
        <Parameter Name="aggregation" Type="System.String" />
        <Parameter Name="resultType" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Models.ResultType&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="55224-102">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="55224-102">The identifier of the resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="55224-103">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="55224-103">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="timespan">
            <span data-ttu-id="55224-104">Der Zeitpunkt der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="55224-104">The timespan of the query.</span></span> <span data-ttu-id="55224-105">Es ist eine Zeichenfolge mit dem folgenden Format "StartDateTime_ISO/EndDateTime_ISO".</span><span class="sxs-lookup"><span data-stu-id="55224-105">It is a string with the following format 'startDateTime_ISO/endDateTime_ISO'.</span></span>
            </param>
        <param name="interval">
            <span data-ttu-id="55224-106">Das Intervall (d. h. timegrain-Wert) der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="55224-106">The interval (i.e. timegrain) of the query.</span></span>
            </param>
        <param name="metric">
            <span data-ttu-id="55224-107">Der Name der abzurufenden Metrik.</span><span class="sxs-lookup"><span data-stu-id="55224-107">The name of the metric to retrieve.</span></span>
            </param>
        <param name="aggregation">
            <span data-ttu-id="55224-108">Die Liste der Aggregationstypen (durch Kommas getrennt) abgerufen.</span><span class="sxs-lookup"><span data-stu-id="55224-108">The list of aggregation types (comma separated) to retrieve.</span></span>
            </param>
        <param name="resultType">
            <span data-ttu-id="55224-109">Reduziert die Menge der gesammelten Daten.</span><span class="sxs-lookup"><span data-stu-id="55224-109">Reduces the set of data collected.</span></span> <span data-ttu-id="55224-110">Die Syntax zulässig, hängt von den Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="55224-110">The syntax allowed depends on the operation.</span></span> <span data-ttu-id="55224-111">Finden Sie unter der vorgangsbeschreibung für Details.</span><span class="sxs-lookup"><span data-stu-id="55224-111">See the operation's description for details.</span></span>
            <span data-ttu-id="55224-112">Folgende Werte sind möglich: "Daten", "Metadaten"</span><span class="sxs-lookup"><span data-stu-id="55224-112">Possible values include: 'Data', 'Metadata'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="55224-113">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="55224-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55224-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="55224-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55224-115">**Listet die metrischen Werte für eine Ressource**.</span><span class="sxs-lookup"><span data-stu-id="55224-115">**Lists the metric values for a resource**.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="55224-116">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="55224-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="55224-117">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="55224-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="55224-118">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="55224-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>