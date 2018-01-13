<Type Name="IActivityRunsOperations" FullName="Microsoft.Azure.Management.DataFactory.IActivityRunsOperations">
  <TypeSignature Language="C#" Value="public interface IActivityRunsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityRunsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityRunsOperations" />
  <TypeSignature Language="F#" Value="type IActivityRunsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c61f4-101">ActivityRunsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c61f4-101">ActivityRunsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByPipelineRunNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt; ListByPipelineRunNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt; ListByPipelineRunNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IActivityRunsOperations.ListByPipelineRunNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByPipelineRunNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt;" Usage="iActivityRunsOperations.ListByPipelineRunNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c61f4-102">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c61f4-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c61f4-103">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c61f4-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c61f4-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c61f4-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c61f4-105">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c61f4-105">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="c61f4-106">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c61f4-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c61f4-107">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c61f4-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c61f4-108">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c61f4-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineRunWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt; ListByPipelineRunWithHttpMessagesAsync (string resourceGroupName, string factoryName, string runId, DateTime startTime, DateTime endTime, string status = null, string activityName = null, string linkedServiceName = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt; ListByPipelineRunWithHttpMessagesAsync(string resourceGroupName, string factoryName, string runId, valuetype System.DateTime startTime, valuetype System.DateTime endTime, string status, string activityName, string linkedServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IActivityRunsOperations.ListByPipelineRunWithHttpMessagesAsync(System.String,System.String,System.String,System.DateTime,System.DateTime,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByPipelineRunWithHttpMessagesAsync : string * string * string * DateTime * DateTime * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt;" Usage="iActivityRunsOperations.ListByPipelineRunWithHttpMessagesAsync (resourceGroupName, factoryName, runId, startTime, endTime, status, activityName, linkedServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityRun&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c61f4-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c61f4-109">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="c61f4-110">Die Factory-Namen.</span><span class="sxs-lookup"><span data-stu-id="c61f4-110">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="c61f4-111">Die Pipeline Bezeichner ausführen.</span><span class="sxs-lookup"><span data-stu-id="c61f4-111">The pipeline run identifier.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="c61f4-112">Die Startzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c61f4-112">The start time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="c61f4-113">Die Endzeit der Aktivität wird im ISO8601-Format ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c61f4-113">The end time of activity runs in ISO8601 format.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="c61f4-114">Führen Sie der Status der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="c61f4-114">The status of the pipeline run.</span></span>
            </param>
        <param name="activityName">
            <span data-ttu-id="c61f4-115">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="c61f4-115">The name of the activity.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="c61f4-116">Der Name des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="c61f4-116">The linked service name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c61f4-117">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c61f4-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c61f4-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c61f4-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c61f4-119">Liste Aktivität wird basierend auf Eingabefilter Bedingungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c61f4-119">List activity runs based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="c61f4-120">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="c61f4-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c61f4-121">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="c61f4-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c61f4-122">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="c61f4-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>