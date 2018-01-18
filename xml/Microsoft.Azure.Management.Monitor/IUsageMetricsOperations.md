<Type Name="IUsageMetricsOperations" FullName="Microsoft.Azure.Management.Monitor.IUsageMetricsOperations">
  <TypeSignature Language="C#" Value="public interface IUsageMetricsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageMetricsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IUsageMetricsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageMetricsOperations" />
  <TypeSignature Language="F#" Value="type IUsageMetricsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="108fb-101">UsageMetricsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="108fb-101">UsageMetricsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, string apiVersion, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, string apiVersion, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IUsageMetricsOperations.ListWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Monitor.Models.UsageMetric},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt;" Usage="iUsageMetricsOperations.ListWithHttpMessagesAsync (resourceUri, apiVersion, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Monitor.Models.UsageMetric&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="108fb-102">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="108fb-102">The identifier of the resource.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="108fb-103">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="108fb-103">Client Api Version.</span></span> <span data-ttu-id="108fb-104">Hinweis: Dies ist eine Eigenschaft des Clients, muss er explizit im Aufruf, und es ist kein Standardwert.</span><span class="sxs-lookup"><span data-stu-id="108fb-104">NOTE: This is not a client property, it must be explicit in the call and there is no default value.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="108fb-105">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="108fb-105">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="108fb-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="108fb-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="108fb-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="108fb-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="108fb-108">Der List-Vorgang Listet die Nutzungsdaten für die Ressource. &lt;Br&gt;**Warnung**: Dieser Vorgang wird nicht *veraltet* in der nächsten Version.</span><span class="sxs-lookup"><span data-stu-id="108fb-108">The List operation lists the usage metrics for the resource.&lt;br&gt;**WARNING**: This operation will be *deprecated* in the next release.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="108fb-109">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="108fb-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="108fb-110">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="108fb-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="108fb-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="108fb-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>