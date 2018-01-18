<Type Name="IPipelineRunsOperations" FullName="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations">
  <TypeSignature Language="C#" Value="public interface IPipelineRunsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelineRunsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelineRunsOperations" />
  <TypeSignature Language="F#" Value="type IPipelineRunsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bc43d-101">PipelineRunsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="bc43d-101">PipelineRunsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string runId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string runId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt;" Usage="iPipelineRunsOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, runId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bc43d-102">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bc43d-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="bc43d-103">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="bc43d-103">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="bc43d-104">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="bc43d-104">The pipeline run identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bc43d-105">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="bc43d-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc43d-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bc43d-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc43d-107">Abrufen einer Pipeline ausführen, indem die Testlauf-ID.</span><span class="sxs-lookup"><span data-stu-id="bc43d-107">Get a pipeline run by its run ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="bc43d-108">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="bc43d-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bc43d-109">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="bc43d-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bc43d-110">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="bc43d-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="QueryByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt; QueryByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt; QueryByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations.QueryByFactoryWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member QueryByFactoryWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt;" Usage="iPipelineRunsOperations.QueryByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, filterParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="filterParameters" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bc43d-111">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bc43d-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="bc43d-112">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="bc43d-112">The factory name.</span></span>
            </param>
        <param name="filterParameters">
            <span data-ttu-id="bc43d-113">Führen Sie die Parameter zum Filtern der Pipelines.</span><span class="sxs-lookup"><span data-stu-id="bc43d-113">Parameters to filter the pipeline run.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bc43d-114">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="bc43d-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc43d-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bc43d-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc43d-116">Abfragepipeline wird in der Factory, die basierend auf den Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="bc43d-116">Query pipeline runs in the factory based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="bc43d-117">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="bc43d-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bc43d-118">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="bc43d-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bc43d-119">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="bc43d-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>